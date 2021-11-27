# raylib-cpp-template

Raylib 4.0 Template C++17 for Visual Studio Code & MinGW-w64

## 1. Create environment variables
**mingw64** : Mingw64 bin folder - https://winlibs.com (e.g. : %mingw64% = C:\gamedev\mingw64\bin)

**raylib64** : Fork of Raylib (x64, bin/release & bin/debug folders) - https://github.com/rogez/raylib64 (e.g. : %raylib64% = C:\gamedev\libs\raylib64))

## 2. Build Raylib64
/raylib64/src/build-debug.bat

/raylib64/src/build-release.bat

This will create both version (i.e. : debug & release) of *libraylib.a* in raylib/bin folder

## 3. Visual Studio Code
### RUN
* DEBUG
### TASKS
* task-build-debug : make debug version in /dist
* task-build-release : make release version in /dist
* task-clean : delete files \*.o and dist/\*.exe
* task-my-rc-build : build Windows resources file my.rc (icon...)

