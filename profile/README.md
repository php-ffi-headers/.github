<p align="center">
    <a href="https://github.com/ffi-libs">
        <img src="https://avatars.githubusercontent.com/u/101121010?s=256" width="128" />
    </a>
</p>

# About

This repository contains a set of popular open source libraries adapted to
work in PHP through the FFI.

In the case that you think that any library should be added - please [create
an issue](https://github.com/php-ffi-libs/.github/issues).

Please note that if the library is cross-platform, then platforms are guaranteed
to be supported:

- Windows
- Linux
- MacOS (Darwin)

Other platforms are not guaranteed to be supported, even if they are claimed
to be supported by the source library's target platform.

In the case that you need support for any other platform, you can do any
testing yourself, later creating a pull request to the project you are
interested in with the addition of support for this target platform.

## Status

- **Library** - Name of the original C library.
- **Version** - Version of the PHP package.
- **Compat Version** - The version of the original C library that the PHP
  headers are compatible with.
- **Source Version** - Current latest release version of the original C library.
- **Status** - CI build status.

| Library                                                | Version                                                           | Compat Version                                                  | Source Version                                                                             | Status                                                                               |
|--------------------------------------------------------|-------------------------------------------------------------------|-----------------------------------------------------------------|--------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------|
| [GLFW3](https://github.com/php-ffi-libs/glfw3-headers) | ![version](https://poser.pugx.org/ffi-libs/glfw3-headers/version) | ![version](https://img.shields.io/badge/GLFW3-3.3.6-004953.svg) | ![version](https://img.shields.io/github/v/release/glfw/glfw?color=cc3c20&label=GLFW3)     | ![status](https://github.com/php-ffi-libs/glfw3-headers/workflows/build/badge.svg)   |
| [SDL2](https://github.com/php-ffi-libs/sdl2-headers)   | ![version](https://poser.pugx.org/ffi-libs/sdl2-headers/version)  | ![version](https://img.shields.io/badge/SDL2-2.0.20-004953.svg) | ![version](https://img.shields.io/github/v/release/libsdl-org/SDL?color=cc3c20&label=SDL2) | ![status](https://github.com/php-ffi-libs/sdl2-headers/workflows/build/badge.svg)    |
| [BASS](https://github.com/php-ffi-libs/bass-headers)   | ![version](https://poser.pugx.org/ffi-libs/bass-headers/version)  | ![version](https://img.shields.io/badge/BASS-2.4.x-004953.svg)  | ![version](https://img.shields.io/badge/BASS-2.4.16-cc3c20.svg)                            | ![status](https://github.com/php-ffi-libs/bass-headers/workflows/build/badge.svg)    |
