# Hello, World! in Ada

This directory contains the source code for building a basic "Hello, World!" application in Ada on Linux.  In order to compile the source code, it will be necessary to utilize the GNU NYU Ada Translator (GNAT) make a.k.a. 'gnatmake' utility.  

Building
--------

Create compiled executable
```sh
gnatmake hello.adb 
```

Clean up build artifacts
```sh
gnatclean -c hello.adb
```
