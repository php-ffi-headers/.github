<p align="center">
    <a href="https://github.com/ffi-headers">
        <img src="https://avatars.githubusercontent.com/u/101121010?s=256" width="128" />
    </a>
</p>

# About

This repository contains a set of popular open source libraries adapted to
work in PHP through the FFI.

In the case that you think that any library should be added - please [create
an issue](https://github.com/php-ffi-headers/.github/issues).

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

<center>

| Library                                                             | Compat Version                                                                           | Source Version                                                                                                          | Status                                                                                     |
|---------------------------------------------------------------------|------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------|
| [GLFW3](https://github.com/php-ffi-headers/glfw3-headers)           | ![version](https://img.shields.io/badge/GLFW3-3.3.8-004953.svg?style=flat-square)        | ![version](https://img.shields.io/github/v/tag/glfw/glfw?color=cc3c20&label=GLFW3&style=flat-square)                    | ![status](https://github.com/php-ffi-headers/glfw3-headers/workflows/build/badge.svg)      |
| [SDL2](https://github.com/php-ffi-headers/sdl2-headers)             | ![version](https://img.shields.io/badge/SDL2-2.0.22-004953.svg?style=flat-square)        | ![version](https://img.shields.io/github/v/tag/libsdl-org/SDL?color=cc3c20&label=SDL2&style=flat-square)                | ![status](https://github.com/php-ffi-headers/sdl2-headers/workflows/build/badge.svg)       |
| [SDL2 Image](https://github.com/php-ffi-headers/sdl2-image-headers) | ![version](https://img.shields.io/badge/SDL2%20Image-2.6.1-004953.svg?style=flat-square) | ![version](https://img.shields.io/github/v/tag/libsdl-org/SDL_image?color=cc3c20&label=SDL2%20Image&style=flat-square)  | ![status](https://github.com/php-ffi-headers/sdl2-image-headers/workflows/build/badge.svg) |
| [SDL2 TTF](https://github.com/php-ffi-headers/sdl2-ttf-headers)     | ![version](https://img.shields.io/badge/SDL2%20TTF-2.20.0-004953.svg?style=flat-square)  | ![version](https://img.shields.io/github/v/tag/libsdl-org/SDL_ttf?color=cc3c20&label=SDL2%20TTF&style=flat-square)      | ![status](https://github.com/php-ffi-headers/sdl2-ttf-headers/workflows/build/badge.svg)   |
| [BASS](https://github.com/php-ffi-headers/bass-headers)             | ![version](https://img.shields.io/badge/BASS-2.4.16-004953.svg?style=flat-square)        | ![version](https://img.shields.io/badge/BASS-not%20available-lightgrey?style=flat-square)                               | ![status](https://github.com/php-ffi-headers/bass-headers/workflows/build/badge.svg)       |
| [BASS Mix](https://github.com/php-ffi-headers/bass-mix-headers)     | ![version](https://img.shields.io/badge/BASS%20Mix-2.4.16-004953.svg?style=flat-square)  | ![version](https://img.shields.io/badge/BASS%20Mix-not%20available-lightgrey?style=flat-square)                         | ![status](https://github.com/php-ffi-headers/bass-mix-headers/workflows/build/badge.svg)   |
| [Vulkan](https://github.com/php-ffi-headers/vulkan-headers)         | ![version](https://img.shields.io/badge/Vulkan-1.3.224-004953.svg?style=flat-square)     | ![version](https://img.shields.io/github/v/tag/KhronosGroup/Vulkan-Headers?color=cc3c20&label=Vulkan&style=flat-square) | ![status](https://github.com/php-ffi-headers/vulkan-headers/workflows/build/badge.svg)     |

</center>
