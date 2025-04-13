---
author: Vuzuu
tags:
  - cppreference
link: https://en.cppreference.com/w/cpp/language/string_literal
---
|   |   |   |
|---|---|---|
|s-char-seq|-|A sequence of one or more s-char ﻿s|
|s-char|-|One of<br><br>- a basic-s-char<br>- an escape sequence, as defined in [escape sequences](https://en.cppreference.com/w/cpp/language/escape "cpp/language/escape")<br>- a universal character name, as defined in [escape sequences](https://en.cppreference.com/w/cpp/language/escape "cpp/language/escape")|
|basic-s-char|-|A character from the [translation character set](https://en.cppreference.com/w/cpp/language/charset#Translation_character_set "cpp/language/charset"), except the double-quote ", backslash \, or new-line character|
|d-char-seq|-|A sequence of one or more d-char ﻿s, at most 16 characters long|
|d-char|-|A character from the [basic character set](https://en.cppreference.com/w/cpp/language/charset#Basic_character_set "cpp/language/charset"), except parentheses, backslash and [spaces](https://en.cppreference.com/w/cpp/string/byte/isspace "cpp/string/byte/isspace")|
|r-char-seq|-|A sequence of one or more r-char ﻿s, except that it must not contain the closing sequence `**)**`d-char-seq`**"**`|
|r-char|-|A character from the [translation character set](https://en.cppreference.com/w/cpp/language/charset#Translation_character_set "cpp/language/charset")|