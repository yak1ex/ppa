PPA by yak\_ex
==============

Packages for Ubuntu 12.04 (precise).
Main purpose is to use in C++ Compiler Farm (https://ccf.myhome.cx:5000/).
Therefore, they are intended to co-exist with other versions of compilers. 

provides
--------

    /usr/bin/clang-3.3
    /usr/bin/clang++-3.3

usage
-----

    sudo add-apt-repository ppa:yak1ex/llvm
    sudo apt-get update
    sudo apt-get install clang-3.3

upstream
--------

https://launchpad.net/ubuntu/+source/llvm-toolchain-3.3/1:3.3-1

reference
---------

- https://github.com/hATrayflood/llvm-ppa Upstream is adjusted by referring this repo.
- https://launchpad.net/~ubuntu-toolchain-r/+archive/test Dependent on this ppa.

launchpad
---------

https://launchpad.net/~yak1ex/+archive/llvm

github
------

https://github.com/yak1ex/ppa
