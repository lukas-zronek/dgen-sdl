# dgen-sdl for macOS

## Synopsis

This is a bugfixed version of [dgen-sdl](http://dgen.sourceforge.net/) (Genesis/Mega Drive emulator) for macOS.

## Changes

* Proper detection of OpenGL support and libarchive
* Include generated files by GNU Autotools
* Fix detection of arrow keys and function keys

## Building

**Install dependencies:**

 * Using MacPorts:
```
sudo port install libsdl -x11 libarchive pkgconfig
```

**Generate Makefiles**

```
./configure
```

**Compile**

```
    make
```

## License

All files in this archive fall under 3 clause BSD license with the exceptions of
* musa: non-commercial license
* starscream: non-commercial license
* mz80: non-commercial license
* cz80: non-commercial license
* scale2x: GPLv2
* hqx: LGPL
