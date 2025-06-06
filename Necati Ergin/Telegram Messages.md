Necati Ergin, [16.01.2025 09:45]
İlk dersimizde C++ içindeki C çekirdeğinden bilinmesi gerekenlerin listesi istenmişti. Bu liste aşağıda. Buradaki başlıklardan bilmedikleriniz varsa bunları zaman içinde öğrenmeniz gerekiyor. Ben de yeri geldiğinde derslerde kısa da olsa listedeki bazı konulara değineceğim

Necati Ergin, [16.01.2025 09:45]
Temel Kavramlar
===============
- atom kavramı (tokens) 
- atom kategorileri (token categories)
- anahtar sözcükler (keywords)
- isimler (identifiers)
- sabitler (constants - literals)
- string literalleri (string literals)
- operatörler (operators)
- atomlarına ayırma (tokenizing)
- en uzun atom kuralı (maximum munch)

Necati Ergin, [16.01.2025 09:46]
Sayı Sistemleri
===============
- işaretli ve işaretsiz ikilik sayı sistemi (signed & unsigned binary systems)
- dönüşümler (conversions)
- bire tümleme işlemi (one's complement)
- ikiye tümleme işlemi (two's complement)
- onaltılık sayı sistemi (hexadecimal system)
- sekizlik sayı sistemi (octal system)

Necati Ergin, [16.01.2025 09:47]
- nesneler (objects)
- tür kavramı (data types)
- nesnelerin bellek alanları (storage)
- temel türler (fundemantal types)
- programcı tarafından tanımlanan türler (user-defined types)
- ifadeler (expressions)
- ifade kategorileri (value categories)
- sol taraf değeri ifadesi (L value expression)
- sağ taraf değeri ifadesi (R value expression)
- sabit ifadeleri (constant expression)

Necati Ergin, [16.01.2025 09:48]
Bir C ya da C++ Programı Oluşturmak
===============================
-metin düzenleyici programlar ve text dosyaları
-kaynak dosya ve çeviri birimi (source file & translation unit)
-derleyici program ve derleme süreci (compilers & compile-time)
-derleyici bulgu iletileri (diagnostic messages of compilers)
-tanımsız davranış (undefined behavior)
-derleyiciye bağlı durumlar (implementation defined behavior)
-derleyici programların lojik kontrolleri
-derleyiciler ve kod optimizasyonu (compilers & cod optimization)
-derleyici eklentileri (compiler extensions)
-önişlemci program (preprocessor)
-bağlayıcı program ve bağlama zamanı (linker program & link time) 
-ide’ler ve yardımcı programlar 
-statik kod analizi yapan programlar
-hata ayıklayıcı programlar (debuggers)

Necati Ergin, [16.01.2025 09:50]
Veri Türleri (Data Types)
========================
varsayılan türler (fundemental / basic types)
tamsayı türleri (integer types)
gerçek sayı türleri (floating types)
programcı tarafından oluşturulan türler (user defined types)

Necati Ergin, [16.01.2025 09:50]
Bildirim ve Tanımlama (Declarations & Definitions)
==================================================
- bildirimler ve deyimler (declarations and statements)
- ilk değer verme (initialization)
- bildirim listesi (declarations as comma-separated lists) 
- tanımlama (definition)

Necati Ergin, [16.01.2025 09:51]
Kapsam ve İsim arama (Scope & Name Lookup)
==========================================
- kapsam (scope)
- kapsam kategorileri (scope categories)
- blok kapsamı (block scope)
- dosya kapsamı (file scope)
- fonksiyon kapsamı (function prototype scope)
- işlev kapsamı (function scope)
- isim arama (name lookup)
- isim çakışmaları (name collision)

Necati Ergin, [16.01.2025 09:51]
Ömür Kavramı (Storage Duration)
===============================
- otomatik ömür (automatic storage class)
- statik ömür (static storage class)
- dinamik ömür (dynamic storage class)

Necati Ergin, [16.01.2025 09:53]
Fonksiyonlar (Functions)
========================
- fonksiyonların tanımlanması (function definitions)                    
- fonksiyonların parametre değişkenleri (formal parameters)
- fonksiyonların geri dönüş değerleri (return values)
- değerle çağrı (call by value)
- referansla çağrılan fonksiyonlar (call by reference)
- void fonksiyonlar (void functions)
- return deyimi (return statement)
- ifadeli ve ifadesiz return deyimleri (return statements with/without expression)
- saf ve saf olmayan fonksiyonlar (pure and impure functions)
- fonksiyonların çağrılması (function calls)
- fonksiyon çağrılarından elde edilen değerlerin kullanılması
- inline fonksiyonlar (inline functions)
- fonksiyonların bildirilmesi (function declarations)

Necati Ergin, [16.01.2025 09:55]
Standart Kütüphane (Standard Library)
=====================================
- standart kütüphanenin varlık nedenleri
- ortak arayüz ilkesi (common interface principle) 
- taşınabilirlik (portability)
- kodların tekrar kullanımı (code reuse)
- standart formatlı giriş çıkış işlevleri (standard formatted input/output functions)
- printf işlevi
- scanf işlevi
- standart giriş akımı (standard input stream)
- standart çıkış akımları (standard output stream)
- standart hata akımı (standard error stream)
- akımların yönlendirilmesi (direction of the streams)
- standart formatsız giriş ve çıkış işlemleri (standard unformatted input/output functions) 
- getchar
- putchar
- standart başlık dosyaları (standard headers)
- standart math kütüphanesi (standard math library)

Necati Ergin, [16.01.2025 09:55]
Operatörler (Operators)
=======================
- operatörlerin değer üretmesi (values generated by operators)
- operatör önceliği (priority of operators)
- öncelik yönü (associativity)
- yan etki (side effect)
- yan etki noktası (sequence point)
- aritmetik operatörler
- toplama, çıkarma, çarpma, bölme ve kalan operatörleri
- işaret operatörleri (sign operators)
- artırma ve eksiltme operatörleri (increment & decrement operators)
- karşılaştırma operatörleri (relational operators)
- karşılaştırma idiyomları 
- tipik hatalar (typical mistakes) 
- lojik operatörler (logical operators)
- lojik yorumlama
- kısa devre davranışı (short-circuit behavior)
- tipik hatalar (typical mistakes)
- lojik ifadeler (logical expressions)
- idiyomlar (idioms)
- atama operatörleri (assignment operators)
- atama operatörlerinin değer üretmesi (values generated by assignment operators)
- yalın atama operatörü
- işlemli atama operatörleri (compound assignment operators)
- idiyomlar (idioms)
- virgül operatörü (comma operator)
- öncelik parantezi

Necati Ergin, [16.01.2025 09:56]
Sabitler (Constants)
====================
- sabitlerin türleri (types of constants)
- tamsayı sabitleri (integer constants)
- gerçek sayı sabitleri (floating constants)
- üstel notasyon (scientific notation) 
- karakter sabitleri (character constants)
- kaçış sekansları (escape sequences)

Necati Ergin, [16.01.2025 09:56]
Kontrol Deyimleri
=================
if deyimi (if statement) 
else if merdiveni (else if ladders)
tipik yapılan hatalar (typical mistakes)
test işlevleri (test functions)
döngü deyimleri (loop statements)
while döngü deyimi (while statement)
do while döngü deyimi (do-while statement)
for döngü deyimi (for statement)
break deyimi (break statement)
continue deyimi (continue statement)
iç içe döngüler (nested loops) 
döngü idiyomları (loop idioms) 
switch deyimi (switch statement)
goto deyimi (goto statement)

Necati Ergin, [16.01.2025 09:58]
Koşul Operatörü (Ternary Operator)
==================================

Standart ctype Kütüphanesi
==========================
- karakter test işlevleri
- isupper, islower, isalpha, isdigit, isalnum, isxdigit, isspace, isblank, ispunct, isprint, isgraph, iscntrl
- karakter dönüşüm işlevleri
- toupper ve tolower işlevleri

Fonksiyon Bildirimleri (Function Declarations)
==============================================

Önişlemci Komutları (preprocessor directives)
=============================================
- önişlemci programın genel tanıtımı (introduction to preprocessing ) 
- include komutu (include directive) 
- define komutu ve makrolar (define directive & macros)
- sembolik sabitler (symbolic constants)
- işlevsel makrolar (functional macros)
- undef komutu (undef directive)
- koşullu derleme işlemleri ve koşullu derleme komutları (conditional compiling directives)
- if
- endif
- else
- elif
- ifdef
- ifndef
- standart limits kütüphanesi (standard limits header)

Necati Ergin, [16.01.2025 10:01]
Tür Dönüşümleri (Type Conversions)
===================================
otomatik tür dönüşümleri (implicit type conversions)
tür dönüştürme operatörü (type-cast operator)
tür dönüşümleri ve veri kaybı (narrowing conversions)
  
typedef bildirimleri
====================
tür eş isimleri ve taşınabilirlik (type alias & portability)  
standart typedef isimleri (standard typedef names)
size_t tür eş ismi
ptrdiff_t tür ismi
time_t ve clock_t tür isimleri
<stdint> başlık dosyası
<stdbool> başlık dosyası
  
Rastgele Sayı Üretimi ve Programlamadaki Önemi
===============================================
gerçek ve sözde rastgele sayı üretimi (truly and pseudo random number generation)
rastgele sayı üretim algoritmaları
tohum değeri (seed value)
standart rand ve srand fonksiyonları

sizeof Operatörü

Diziler (arrays)
================
- veri yapıları ve algoritmalara giriş (introduction to data structure & algorithms)
- veri yapıları (data structures)
- algoritmanın karmaşıklığı (complexity of algorithms)
- big O notasyonu (big O notation)
- tamsayı ve gerçek sayı dizileri
- dizilere ilk değer verme (initialization of arrays)
- diziler üstünde yürütülen temel algoritmalar
- yazılar ve yazı tutan char diziler
- null karakter (null character)
- yazılar üstünde yürütülen temel algoritmalar
- yazılara ilişkin temel algoritmalar

Necati Ergin, [16.01.2025 10:01]
Göstericiler (pointers)
=======================
- temel kavramlar
- adres ifadeleri (pointer expressions)
- gösterici değişkenler (pointer variables)
- göstericiler ve storage (pointers & storage duration)
- adres operatörü (address of operator)
- içerik operatörü (dereferencing operator)  
- diziden adrese dönüşüm (array to pointer conversion)
- geçerli ve geçersiz göstericiler (valid & invalid pointers)
- göstericiler ve const semantiği (pointers & const semantics)
- kendisi const göstericiler (const pointers)
- okuma amaçlı const göstericiler 
- const semantiği ve tür dönüşümleri (const semantics & type conversions)
- gösterici aritmetiği
- indeks operatörü (index/subscript operators)
- diziler üstünde işlem yapan fonksiyonlar 
- göstericiler ve karşılaştırma işlemleri (pointers & relational operators)
- adres döndüren fonksiyonlar (function returning pointers)
- NULL gösterici (NULL pointer)
- endianness, little endian, big endian kavramları (endianness, litlle & big endian)
- gösterici hataları (pointer mistakes)

Necati Ergin, [16.01.2025 10:03]
Standart string Kütüphanesi (string library)
============================================
- strlen, strcpy, strcat, strncpy, strncat fonksiyonları
- arama fonksiyonları: strchr, strnchr, strstr, strpbrk, strspn, strcspn
- karşılaştırma fonksiyonları : strcmp, strcoll, stricmp
- strtok işlevi

Standart stddef Kütüphanesi
============================

String Sabitleri (String Literals)
==================================
- string sabitleri ve const doğruluğu (string literals and const correctness)
- string sabitleri ve ömür (lifespan of string literals)
- özdeş string sabitleri 
- string sabitleri ve kaçış sekansları
- string sabitlerinin birden fazla satıra yayılması

Gösterici Dizileri (Pointer Arrays)
===================================

Gösterici Gösteren Gösterici (Pointer to pointer)
=================================================

void Göstericiler (void Pointers)
=================================
- türden bağımsız fonksiyonlar (generic functions)
- standart memset, memcpy, memmove, memchr, memcmp fonksiyonları
- void ** türü

Necati Ergin, [16.01.2025 10:08]
Fonksiyon Göstericileri (Function Pointers)
===========================================
- genel sentaks
- fonksiyondan adrese dönüşüm (function to pointer conversion)
- fonksiyon göstericileri ve typedef bildirimleri (function pointers and typedef declarations)
- geri çağrı fonksiyon yapısı (call-back functions)
- standart qsort ve bsearch fonksiyonları
- fonksiyon gösterici dizileri (function pointer arrays)

Çok Boyutlu Diziler (Multi-dimensional Arrays)
==============================================
- çok boyutlu dizileri gösteren göstericiler (pointer to multi-dimensional arrays)
- çok boyutlu dizilerin fonksiyonlara gönderilmesi (passing multi-dimensional arrays to functions)

Programların Sonlandırılması
=============================
- normal ve anormal sonlanma (normal & abnormal termination)
- standart exit, atexit ve abort fonksiyonları

Dinamik Bellek Yönetimi (Dynamic Memory Management)
===================================================
- dinamik bellek ihtiyacı ve dinamik ömür kavramı (dynamic storage)
- heap alanı ve yönetimi (heap and heap management)
- heap’in parçalara ayrılması (heap fragmentation)
- standart dinamik bellek yönetimi fonksiyonları (standard memory management functions)
- malloc
- calloc
- realloc
- free
- bellek sızıntısı (memory leak)
- dangling pointer
- boşa düşen göstericiler (dangling pointers)
- dinamik dizi veri yapısı (dynamic array data structure)
- dinamik gözterici dizileri (dynamic pointer arrays)

Necati Ergin, [16.01.2025 10:11]
Yer Belirleyiciler (Storage Class Specifiers)
=============================================
= yer belirleyiciler (storage  class specifiers) 
= auto anahtar sözcüğü
= register anahtar sözcüğü
= extern anahtar sözcüğü
= static anahtar sözcüğü
= modül ve bağlantı kategorileri
= iç bağlantı (internal linkage)
= dış bağlantı (external linkage)
= global isim alanının kirlenmesi problemi (global namespace pollution problem)

tür niteleyicileri (type modifiers)
===================================
- const anahtar sözcüğü ve const semantiği (const keyword & const semantics)
- volatile anahtar sözcüğü (volatile keyword)
- restrict anahtar sözcüğü (restrict keyword)

Yapılar (Structures)
====================
- genel sentaks
- yapı öğeleri (structure members)
- nokta operatörü (member selection - dot operator)
- ok operatörü (member selection - arrow operator)
- yapı nesnelerine ilk değer verilmesi (initialization of structure variables)
- yapı nesneleri ve fonksiyonlar (functions with structure parameters)
- tamamlanmış ve eksik türler (complete / incomplete types)
- içsel türler (nested types)
- yapı öğesinin kendi türünden gösterici olması
- düğüm kavramı (nodes) 
- bağlı liste (linked list) veri yapısı
- tekli bağlı listeler (singly linked lists)
- çifte bağlı listeler (double linked lists)
- döner bağlı isteler (rotating lists)
- ikili arama ağacı veri yapısı (binary search tree data structure) 
- yapı türlerinden sabitler (compound literals)
- handle kavramı ve nesne yönelimli C kütüphaneleri
- hizalama ve yapı türleri
- hizalama ile ilgili kodlama hataları
- offsetof makrosu 
- anonim yapılar (anonymous structures)
- yapıların içsel türleri (nested types of structures)

Necati Ergin, [16.01.2025 10:11]
Standart time Kütüphanesi (time Library)
========================================
- takvim zamanı ve ayrıştırılmış zaman (calender time & broken-down time)
- time_t türü
- clock_t türü
- struct tm yapısı
- time, localtime, gmtime, ctime, asctime, strftime, mktime, clock fonksiyonları

Necati Ergin, [16.01.2025 10:13]
Birlikler (Unions)
==================
- birliklerin kullanım temaları
- tagged unions
- birliklerin bit alanı öğeler ile kullanımı

Numaralandırmalar (Enumarations)
================================
- numaralandırma sabitleri (enumaration constants)
- enum idiyomları (enum idioms)

Bitsel İşlemler (Bitwise Operations)
====================================
- bitsel operatörler (bitwise operators)
- bitsel manipülasyon işlemleri (bitwise manipulations)
- yapıların bit alanı öğeleri (bitfield members of structures)
- bitsel işlemler ve birlikler (bitwise operations & unions)
- bit vektör kullanımı (bit vectors)
- bitsel düzeyde oluşturulan arama (lookup) tabloları

Necati Ergin, [16.01.2025 10:13]
Komut Satırı Argümanları (Command Line Arguments)
=================================================

Dosya İşlemleri (File Operations)
=================================
- dosyaların açılması ve kapatılması
- dosya açış modları
- okuma, yazma ve sona ekleme modları
- text modu ve binary mod
- fopen, freopen, fclose ve fcloseall fonksiyonları
- okuma ve yazma işlemleri
- formatlı okuma yazma işlemleri
- fprintf işlevi
- fscanf işlevi
- fputs işlevi
- fgets işlevi
- formatsız okuma yazma işlemleri
- fgetc işlevi
- fputc işlevi
- fread işlevi
- fwrite işlevi
- standart dosya konum göstericisi fonksiyonları
- fseek işlevi
- ftell işlevi
- rewind işlevi
- fsetpos işlevi
- fgetpos işlevi
- feof, ferror, clearerr, fflush fonksiyonları
- fsetbuf işlevi
- ungetc işlevi
- Diğer dosya fonksiyonları ve örnek uygulamalar

Necati Ergin, [16.01.2025 10:14]
Önişlemci Komutları – 2
========================
- önişlemci operatörleri (preprocessor operators)
- dizge yapma operatörü (stringification operator) 
- atom yapıştırma operatörü (token-pasting operator) 
- defined operatörü (defined operator)
- öntanımlı sembolik sabitler (predefined symbolic constants)
- line komutu (line directive)
- error komutu (error directive)
- pragma komutu _pragma directive)

- assert makrosu
- _Static_assert

Değişken Sayıda Argümanla Çağrılabilen İşlevler (Variadic Functions)
==========================================================