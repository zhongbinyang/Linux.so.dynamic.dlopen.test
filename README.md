# Linux.so.dynamic.dlopen.test
使用dlopen显式调用动态链接库

1. 建立一个libhello.so动态库

g++ -fPIC -shared -o libhello.so hello.cpp

2. 使用dlopen显式调用动态链接库

g++ test.cpp -o test -ldl

