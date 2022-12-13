# gfbuild-glslang

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![Build Status](https://github.com/google/gfbuild-glslang/workflows/.github/workflows/build.yml/badge.svg)](https://github.com/google/gfbuild-glslang/actions)


## gfbuild-glslang is a set of scripts for building [glslang](https://github.com/KhronosGroup/glslang) for the GraphicsFuzz project

[GraphicsFuzz](https://github.com/google/graphicsfuzz) is a set of tools for automatically finding bugs in graphics shader compilers. GraphicsFuzz invokes libraries and command line tools from other projects written in C++. These projects must be built in a specific and consistent way for Linux, Mac, and Windows, and the binaries must be released continuously and independently with each change, far more frequently than with a typical stable release schedule.

This is not an officially supported Google product.
