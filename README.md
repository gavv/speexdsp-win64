# speexdsp-win64 [![build](https://github.com/gavv/speexdsp-win64/actions/workflows/build.yml/badge.svg)](https://github.com/gavv/speexdsp-win64/actions/workflows/build.yml)

Prebuilt [SpeexDSP](https://github.com/xiph/speexdsp) static library for 64-bit MSVC.

Binaries are built and published automatically using Github Actions. You can either use binaries from this repo, or fork the repo and configure your own build, so that you can completely trust the build results.

Branch    | Description
--------- | ------
[`main`](https://github.com/gavv/speexdsp-win64) | build script and github actions config
[`pkg`](https://github.com/gavv/speexdsp-win64/tree/pkg) | built binaries

The list of published versions is [available here](https://github.com/gavv/speexdsp-win64/tags).

The library is built using [MSYS2](https://www.msys2.org/) and [cccl](https://github.com/swig/cccl) wrapper on top of Microsoft Visual C++ command-line tools.
