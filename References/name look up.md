---
author: Vuzuu
tags:
  - cppreference
link: https://en.cppreference.com/w/cpp/language/lookup
---
Name lookup is the procedure by which a [name](https://en.cppreference.com/w/cpp/language/name "cpp/language/name"), when encountered in a program, is associated with the [declaration](https://en.cppreference.com/w/cpp/language/declarations "cpp/language/declarations") that introduced it.

For example, to compile [std::cout](http://en.cppreference.com/w/cpp/io/cout) << [std::endl](http://en.cppreference.com/w/cpp/io/manip/endl);, the compiler performs:

- unqualified name lookup for the name `std`, which finds the declaration of namespace std in the header [iostream](https://en.cppreference.com/w/cpp/header/iostream "cpp/header/iostream")
- qualified name lookup for the name `cout`, which finds a variable declaration in the namespace `std`
- qualified name lookup for the name `endl`, which finds a function template declaration in the namespace `std`
- both [argument-dependent lookup](https://en.cppreference.com/w/cpp/language/adl "cpp/language/adl") for the name `operator<<`, which finds multiple function template declarations in the namespace `std`, and qualified name lookup for the name std::ostream::operator<<, which finds multiple member function declarations in class [std::ostream](https://en.cppreference.com/w/cpp/io/basic_ostream "cpp/io/basic ostream").
