Awesome C
=========

A curated non-opinionated list of opensource C libraries, frameworks, tools and
other resources.

Items marked with ⚠️ symbol aren't opensource or covered under or proprietary
license.

Libraries
=========

AI
--

Artificial intelligence.

- [sod][library-sod]: embedded computer vision and machine learning library.
  [GPL-3.0-only][license-gpl-3.0-only].

GUI
---

Graphical user interface toolkits to create end user applications.

- [EFL][library-efl]: enlightenment foundation library.
  [LGPL-2.1-only][license-lgpl-2.1-only].
- [GTK][library-gtk]: GNOME graphical toolkit.
  [LGPL-2.1-or-later][license-lgpl-2.1-or-later].
- [nuklear][library-nuklear]: platform agnostic immediate mode UI library.
  [MIT][license-mit].

Databases
---------

Frameworks to access SQL, NoSQL and other engines.

- [mariadb C connector][library-mariadb-c-connector]: official MariaDB
  connector. [LGPL-2.1-or-later][license-lgpl-2.1-or-later].
- [libpq][library-libpq]: official PostgreSQL client library.
  [PostgreSQL][license-postgresql].
- [sqlite][library-sqlite]: file based SQL engine, most used in the world.
  [Public domain][license-public-domain].

JSON
----

Libraries to decode, parse and generate [JSON][other-json].

- [jansson][library-jansson]: encode, decode and manipulate JSON data.
  [MIT][license-mit].
- [jsmn][library-jsmn]: allocationless JSON decoder. [MIT][license-mit].
- [json-c][library-json-c]: a JSON implementation in C. [MIT][license-mit].

Game programming
----------------

- [Allegro][library-allegro]: cross-platform library mainly aimed at video game
  and multimedia programming. [BSD-3-Clause][license-bsd-3-clause].
- [SDL2][library-sdl2]: cross platform development library with audio, video, input,
  OpenGL and more. [Zlib][license-zlib].

Scripting languages
-------------------

Scripting languages designed to be embedded into C to extend your applications.

- [Duktape][library-duktape]: ECMAScript 5.1 engine with an API similar to Lua.
  [MIT][license-mit].
- [Gravity][library-gravity]: simple language with a Swift like syntax.
  [MIT][license-mit].
- [Lua][library-lua]: embeddable scripting language. [MIT][license-mit].
- [Wren][library-wren]: class-based scripting language. [MIT][license-mit].

Strings
-------

Libraries and frameworks to create and manipulate safe strings in C.

- [libbuf][library-libbuf]: minimal set of 13 functions to manipulate strings.
  [ISC][license-isc].
- [sds][library-sds]: Simple Dynamic Strings library for C.
  [BSD-2-Clause][license-bsd-2-clause].

Unicode
-------

Handling of unicode character classes, conversion between unicode
representations (e.g. UTF-8, UTF-16, UTF-32) and more.

- [icu][library-icu]: international components for Unicode. [ICU][license-icu].
- [libunicode][library-libunicode]: conversion and classifications in only 18
  functions. [ISC][license-isc].
- [utf8.h][library-utf8.h]: header only set of functions for UTF-8 strings.
  [Unlicense][license-unlicense].
- [utf8proc][library-utf8proc]: library for handling UTF-8 strings.
  [MIT][license-mit].

Text manipulation
-----------------

Other text manipulation that consists of encoding and decoding to different
formats.

- [libbase64][library-libbase64]: minimal set of 6 functions to encode and
  decode base64 data. [ISC][license-isc].

Web frameworks
--------------

List of libraries that let you create websites in CGI or as HTTP servers.

- [facil.io][library-facio.io]: web application framework. [MIT][license-mit].
- [kcgi][library-kcgi]: opinionated minimal CGI/FastCGI library.
  [ISC][license-isc].
- [kore][library-kore]: web application framework. [ISC][license-isc].

Tools
=====

Set of tools, IDE and code helpers.

Compilers
---------

- [cproc][tool-cproc]: C11 compiler based on QBE. [ISC][license-isc].
- [GCC][tool-gcc]: GNU Compiler Collection.
  [GPL-3.0-or-later][license-GPL-3.0-or-later].
- [LLVM][tool-llvm]: comprehensive toolchain for various languages, cross
  platform and cross-compilation built-in. [NCSA][license-ncsa].

Environment
-----------

- [MSYS2][tool-msys2]: easy to use environment for windows including gcc, clang
  and the Arch Linux's pacman package manager. [^1].
- [⚠️ Visual Studio][tool-visual-studio]: reference IDE for Microsoft Windows.

Build systems
-------------

List of build systems.

- [BSD Make][tool-bsd-make]: portable implementation of NetBSD make.
  [BSD-2-Clause][license-bsd-2-clause].
- [CMake][tool-cmake]: cross platform build system that generates IDE and build
  system files. [BSD-3-Clause][license-bsd-3-clause].
- [GNU Make][tool-gnu-make]: GNU variant of the POSIX make utility.
  [GPL-3.0-or-later][license-gpl-3.0-or-later].
- [Meson][tool-meson]: build system aimed at speed.
  [Apache-2.0][license-apache-2.0].
- [Premake][tool-premake]: build utility based on Lua.
  [BSD-3-Clause][license-bsd-3-clause].
- [xmake][tool-xmake]: cross platform build utility based on Lua.
  [Apache-2.0][license-apache-2.0].

---

[^1]: No license applicable because the project may consist of dozens of
      different individual elements.

[library-allegro]: https://liballeg.org
[library-duktape]: https://duktape.org
[library-efl]: https://www.enlightenment.org/about-efl
[library-facio.io]: https://facil.io
[library-gravity]: https://marcobambini.github.io/gravity
[library-gtk]: https://gtk.org
[library-icu]: https://icu.unicode.org
[library-jansson]: https://github.com/akheron/jansson
[library-jsmn]: https://zserge.com/jsmn
[library-json-c]: http://json-c.github.io/json-c
[library-kcgi]: https://kristaps.bsd.lv/kcgi
[library-kore]: https://kore.io
[library-libbase64]: https://projects.malikania.fr/libbase64
[library-libbuf]: https://projects.malikania.fr/libbuf
[library-libpq]: https://www.postgresql.org/docs/current/libpq.html
[library-libunicode]: https://projects.malikania.fr/libunicode
[library-lua]: https://www.lua.org
[library-mariadb-c-connector]: https://github.com/mariadb-corporation/mariadb-connector-c
[library-mariadb]: https://mariadb.org
[library-nuklear]: https://github.com/Immediate-Mode-UI/Nuklear
[library-sdl2]: https://libsdl.org
[library-sds]: https://github.com/antirez/sds
[library-sod]: https://sod.pixlab.io
[library-sqlite]: https://sqlite.org
[library-utf8.h]: https://github.com/sheredom/utf8.h
[library-utf8proc]: https://github.com/JuliaStrings/utf8proc
[library-wren]: https://wren.io

[tool-bsd-make]: https://www.crufty.net/help/sjg/bmake.htm
[tool-cmake]: https://cmake.org
[tool-cproc]: https://git.sr.ht/~mcf/cproc
[tool-gcc]: https://gcc.gnu.org
[tool-gnu-make]: https://www.gnu.org/software/make
[tool-llvm]: https://llvm.org
[tool-msys2]: https://www.msys2.org
[tool-visual-studio]: https://visualstudio.microsoft.com
[tool-xmake]: https://xmake.io

[license-apache-2.0]: https://spdx.org/licenses/Apache-2.0.html
[license-bsd-2-clause]: https://spdx.org/licenses/BSD-2-Clause.html
[license-bsd-3-clause]: https://spdx.org/licenses/BSD-3-Clause.html
[license-gpl-3.0-only]: https://spdx.org/licenses/GPL-3.0-only.html
[license-gpl-3.0-or-later]: https://spdx.org/licenses/GPL-3.0-or-later.html
[license-icu]: https://spdx.org/licenses/ICU.html
[license-isc]: https://spdx.org/licenses/ISC.html
[license-lgpl-2.1-only]: https://spdx.org/licenses/LGPL-2.1-only.html
[license-lgpl-2.1-or-later]: https://spdx.org/licenses/LGPL-2.1-or-later.html
[license-mit]: https://spdx.org/licenses/MIT.html
[license-ncsa]: https://spdx.org/licenses/NCSA.html
[license-postgresql]: https://spdx.org/licenses/PostgreSQL.html
[license-public-domain]: https://en.wikipedia.org/wiki/Public_domain
[license-unlicense]: https://spdx.org/licenses/Unlicense.html
[license-zlib]: https://spdx.org/licenses/Zlib.html

[other-json]: https://en.wikipedia.org/wiki/JavaScript_Object_Notation
