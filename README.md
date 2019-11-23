# travis_qmake_gcc_cpp14_clang-tidy

Branch |[![Travis CI logo](pics/TravisCI.png)](https://travis-ci.org)
-------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
master |[![Build Status](https://travis-ci.org/richelbilderbeek/travis_qmake_gcc_cpp14_clang-tidy.svg?branch=master)](https://travis-ci.org/richelbilderbeek/travis_qmake_gcc_cpp14_clang-tidy)
develop|[![Build Status](https://travis-ci.org/richelbilderbeek/travis_qmake_gcc_cpp14_clang-tidy.svg?branch=develop)](https://travis-ci.org/richelbilderbeek/travis_qmake_gcc_cpp14_clang-tidy)

This GitHub is part of:

 * [the Travis C++ Tutorial](https://github.com/richelbilderbeek/travis_cpp_tutorial)
 
The goal of this project is to have a clean Travis CI build, with specs:
 * Build system: `qmake`
 * C++ compiler: `gcc`
 * C++ version: `C++14`
 * Libraries: `STL` only
 * Code coverage: none
 * Static code analysis: `clang-tidy`
 * Source: one single file, `main.cpp`

More complex builds:

 * [![Build Status](https://travis-ci.org/richelbilderbeek/travis_qmake_gcc_cpp17_clang-tidy.svg?branch=master)](https://travis-ci.org/richelbilderbeek/travis_qmake_gcc_cpp17_clang-tidy) Add `clang-tidy`: [travis_qmake_gcc_cpp17_clang-tidy](https://www.github.com/richelbilderbeek/travis_qmake_gcc_cpp17_clang-tidy)

Builds of similar complexity:

 * [none]

Less complex builds:

 * [![Build Status](https://travis-ci.org/richelbilderbeek/travis_qmake_gcc_cpp14.svg?branch=master)](https://travis-ci.org/richelbilderbeek/travis_qmake_gcc_cpp14) No `clang-tidy`: [travis_qmake_gcc_cpp14](https://www.github.com/richelbilderbeek/travis_qmake_gcc_cpp14)

