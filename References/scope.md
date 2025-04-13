---
author: Vuzuu
tags:
  - cppreference
link: https://en.cppreference.com/w/cpp/language/scope
---
Each declaration that appears in a C++ program is only visible in some possibly discontiguous _scopes_. Within a scope, unqualified name lookup can be used to associate a name with its declaration. 

### General 
Each program has a _global scope_, which contains the entire program. 
Every other scope S is introduced by 
- a [[declaration]] 
- a parameter in [[parameter list]]. 
- a [[statement]], or 
- a [[handler]]
S always appear in a another scope, which thereby contains S.

```cpp
//                global  scope  scope
//                scope     S      T
int x;         //   ─┐                 // program point X
               //    │
{              //    │     ─┐
    {          //    │      │     ─┐
        int y; //    │      │      │   // program point Y
    }          //    │      │     ─┘
}              //   ─┘     ─┘
```

#### Block scope
Each

- selection statement (if, switch),
- iteration statement   for,  range-for(since C++11), while,  do-while
- [handler](https://en.cppreference.com/w/cpp/language/catch "cpp/language/catch"), or
- [compound statement](https://en.cppreference.com/w/cpp/language/statements#Compound_statements "cpp/language/statements") that is not the compound-statement of a handler
introduces a _block scope_ that includes the statement or handler.
A variable that belongs to a block scope is a _block variable_.
```cpp
int i = 42;
int a[10];
 
for (int i = 0; i < 10; i++) // inner “i” inhabits the block scope
    a[i] = i;                // introduced by the for-statement
 
int j = i; // j = 42
```

#### Function parameter scope 
```cpp
int f(int n) // the declaration of the parameter “n”
{            // introduces a function parameter scope
    /* ... */
}            // the function parameter scope ends here
```

#### Lambda scope
Each [[lambda expression]] introduces a lambda scope that starts immediately after captures and extends to the end of body. 
```cpp 
// Since C++14
auto lambda = [x = 1, y]() // this lambda expression introduces a lambda scope,
{                          // it is the target scope of capture “x”
    /* ... */
};                         // the lambda scope ends before the semicolon
```

#### Namespace scope
```cpp
namespace V   // the namespace definition of “V”
{             // introduces a namespace scope “S”
    // the first part of scope “S” begins here
    void f();
    // the first part of scope “S” ends here
}
 
void V::f()   // the portion after “f” is also a part of scope “S”
{
    void h(); // declares V::h
}             // the second part of scope “S” ends here
```

#### Class scope
```cpp
class C       // the class definition of “C”
{             // introduces a class scope “S”
    // the first part of scope “S” begins here
    void f();
    // the first part of scope “S” ends here
}
 
void C::f()   // the portion after “f” is also a part of scope “S”
{
    /* ... */
}             // the second part of scope “S” ends here
```

#### Enumeration scope
```cpp
enum class E // the enumeration declaration of “E”
{            // introduces an enumeration scope “S”
    // scope “S” begins here
    e1, e2, e3
    // scope “S” ends here
}
```

#### Template parameter scope
```cpp
// the class template declaration of “X”
// introduces a template parameter scope “S1”
template
<
    // scope “S1” begins here
    template // the template template parameter “T”
             // introduces another template parameter scope “S2”
    <
        typename T1
        typename T2
    > requires std::convertible_from<T1, T2> // scope “S2” ends here
    class T,
    typename U
>
class X; // scope “S1” ends before the semicolon
```

#### Point of declaration
In general, a name is visible after the locus of its first declaration.