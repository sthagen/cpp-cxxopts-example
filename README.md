# cpp-cxxopts-example

Experimental example for cxxopts C++ library (from user jarro2783) per CMake package management.

## Usage

Generate build files:

```console
❯ cmake -S . -B build
# ...
```

Build:
```console
❯ cmake --build build
[ 50%] Building CXX object CMakeFiles/cxxopts_example.dir/main.cpp.o
[100%] Linking CXX executable cxxopts_example
[100%] Built target cxxopts_example
```

Execute:
```console
❯ build/cxxopts_example -h
One line description of the commandline app
Usage:
  App [OPTION...]

  -h, --help      Show help
  -d, --debug     Enable debugging
  -f, --file arg  File name
```

... or:
```console
❯ build/cxxopts_example -d -f value
option: debug: true
option: file: value
```

## Status

Experimental

**Note**: The default branch is `default`.
