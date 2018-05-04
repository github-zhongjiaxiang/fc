# fc
FC stands for fast-compiling c++ library and provides a set of utility libraries useful for the development of asynchronous libraries. Some of the highlights include:

Cooperative Multi-Tasking Library with support for Futures, mutexes, signals.
Wrapper on Boost ASIO for handling async opperations cooperatively with easy to code synchronous style.
Reflection for C++ allowing automatic serialization in Json & Binary of C++ Structs
Automatic generation of client / server stubs for reflected interfaces with support for JSON-RPC
Cryptographic Primitives for a variaty of hashes and encryption algorithms
Logging Infrastructure
Wraps many Boost APIs, such as boost::filesystem, boost::thread, and boost::exception to acceleate compiles
Support for unofficial Boost.Process library.

## What did we do？
1. We add EOS testing example;
2. We add bithumb coin testing example;
3. FC will be a module for bithumb coin；

## Compile environment:
ubuntu 16.04,cmake 3.11, boost 1.66

## Compile steps:
1. cd fc, and mkdir build
2. cmake ..
3. make(In order to compile fc under c++14 standard, we need add add_compile_options(-std=c++14))

