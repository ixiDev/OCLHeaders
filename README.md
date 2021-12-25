# OCLHeaders
OpenCL (C/C++) Headers to use it with Termux Android App


### How to use 

First clone the project 
```shell
  cd $HOME && git clone https://github.com/ixiDev/OCLHeaders.git
```
then build and install headers

```shell
cmake -S . -B build -DCMAKE_INSTALL_PREFIX=$PREFIX/include
cmake --build build --target install
```
