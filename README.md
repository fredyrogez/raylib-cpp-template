# raylib-cpp-template

Raylib 4.0 Template C++17 for Visual Studio Code & MinGW-w64

## 1. Create environment variables
**mingw64** : Mingw64 bin folder - https://winlibs.com (e.g. : %mingw64% = C:\gamedev\mingw64\bin)

## 2. Visual Studio Code
### RUN
* DEBUG
### TASKS
* task-build-debug : make debug version /dist/game-debug.exe
* task-build-release : make release version /dist/game-release.exe
* task-clean : delete files \*.o and dist/\*.exe
* task-my-rc-build : build Windows resources file my.rc (icon...)
