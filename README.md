# cradar5
cradar5 is an adaptation of the legendary RADAR5, a routine for solving stiff delay differential equations, written in modern C++. 

This project is entirely new and currently has no functionality. If you'd like to use RADAR5 right now and somehow found this page, go to http://www.unige.ch/~hairer/software.html. 

# installation/building

First install meson: https://mesonbuild.com/Getting-meson.html 

Then run these commands from the root directory compile the project.

```
meson setup build && cd build
meson compile
```

Currently, the only thing that will compile is an eigen hello world program. To test, go to the src directory inside the build directory and run the hello binary. 



