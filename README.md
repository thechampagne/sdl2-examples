SDL2 Examples
=============

[![sdl2-examples](https://github.com/xyproto/sdl2-examples/actions/workflows/main.yml/badge.svg)](https://github.com/xyproto/sdl2-examples/actions/workflows/main.yml)

"hello world" for SDL2 for various programming languages.

Each sample creates a window, displays an image, then waits two seconds and quits.


Requirements
------------

* The SDL 2 library.
* See the README.md file per sample for more information.


Requirements for some of the languages
--------------------------------------

* C compiler that supports C89 (ANSI C), C99 or C11, for the C samples
* A C++ compiler for the C++ sample
* GCC 4.8 or later (or clang++) for the C++11 sample
* [Alire](https://alire.ada.dev/docs/) for the Ada example
* Go 1.1 or later and the sdl2 go package (`go get github.com/veandco/go-sdl2/sdl`)
* MRuby with SDL2 added to the configuration file
* Nim 0.9.4 and sdl2 installed with babel
* Python 2 or 3 and PySDL2
* FPC 2.6.4 (or later than 2.4.0, must have Uint8, Uint16 and Uint32)
* Lua (tested with Lua 5.3) and lua-sdl2
* If `tcc` is used for compiling one of the C examples, make sure to add [`-DSDL_DISABLE_IMMINTRIN_H=1`](https://www.mail-archive.com/tinycc-devel@nongnu.org/msg08821.html).

Languages that are not added yet
--------------------------------

- [ ] Fortran
- [ ] F#
- [ ] Java
- [ ] Scheme

Pull requests are welcome.

General information
----------------------

* License: BSD-3
