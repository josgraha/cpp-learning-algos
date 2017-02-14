# Learning STL Algoritms

## Description
This is a C++ project to learn the STL algorithms header.  Based off the boilerplate Google Test and Cmake (http://cmake.org)

## How to build

1. mkdir build
2. cd build
3. cmake ..
4. cmake --build .
5. ctest -VV


## Known issues:

- Google Test (master branch) was broken for MinGW (see https://github.com/google/googletest/issues/606)
  As workaround we'll use -Dgtest_disable_pthreads=ON as suggested per https://github.com/google/shaderc/pull/174
