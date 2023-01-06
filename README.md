# Cascade Public Monorepo

![](https://github.com/cascade-gmbh/cascade-public/actions/workflows/ci.yml/badge.svg)

Open source software components based on C++23 and embedded Python packages.

- Windows, Ubuntu, macOS, iOS, Android, WebAssembly 
- GCC, Clang, MSVC

**Cascade Metal**: Compiler generator library based upon [Coco/R](https://github.com/mingodad/CocoR-CPP) for implementing domain specific languages (DSL) using attributed grammars directly in C++ sourcecode.

---

External C++ libraries**:
  [pybind11](https://github.com/pybind/pybind11),
  [namedtype](https://github.com/joboccara/NamedType),
  [botan](https://github.com/randombit/botan),
  [zlib](https://github.com/madler/zlib),
  [entt](https://github.com/skypjack/entt),
  [asio](https://github.com/chriskohlhoff/asio),
  [sdl](https://github.com/libsdl-org/SDL),
  [opencv](https://github.com/opencv/opencv),
  [imgui](https://github.com/ocornut/imgui.git)  
  *Repositories are cloned into the working directory of the
  executing ci/cd-runners.*

External Python packages:
  [numpy](https://github.com/numpy/numpy),
  [pandas](https://github.com/pandas-dev/pandas),
  [matplotlib](https://github.com/matplotlib/matplotlib),
  [seaborn](https://github.com/mwaskom/seaborn)  
  *Packages are installed into the executing ci/cd-runners.*

External tools:
  [cmake],
  [conan],
  [cppcheck],
  [clang-format],
  [clang-tidy],
  [gcc sanitizers],
  [clang sanitizers],
  [heaptrack],
  [lcov],
  [gcov],
  [coverity],  
  [klee](https://github.com/klee/klee),
  [catch2](https://github.com/catchorg/Catch2),
  [asciidoctor](https://github.com/asciidoctor/asciidoctor),
  [doxygen](https://github.com/doxygen/doxygen),
  [coco/r](https://github.com/mingodad/CocoR-CPP)

---

Copyright (C) 2021 Cascade Informationssysteme GmbH, all rights reserved.

![](https://img.shields.io/badge/License-MIT-yellow.svg)
