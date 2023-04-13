# VSCode C++ OpenCV

- 🚀 VSCode, C++ and Opencv installation notes for windows are explained step by step.

# Downloads

- `VSCode` - https://code.visualstudio.com/download
- `OpenCV` - https://opencv.org/releases/
- `CMake` - https://cmake.org/download/
- `MinGW` - https://sourceforge.net/projects/mingw/

# Environment Variables

👾The paths of the opencv library must be introduced to the system.

- `...\opencv\build\x64\vc15\bin`
- `...\opencv\build\x64\vc15\lib`

# Extensions

- `C/C++ Extension Pack`
- `CMake`
- `CMake Tools`
- `GitHub Pull Requests and Issues`
- `GitLens — Git supercharged`

# CMakeLists.txt

Short (Ctrl + shft + P) or View (Command Palette..)

- `CMake Quick Start`
- `Relase - amd64`
- `Enter Your Project Folder Name`
- `And Choose External`

# 

| CMakeLists.txt |
| --- |
|  💠 cmake_minimum_required(VERSION 3.0.0)
|  💠 project(Project Folder Name VERSION 0.1.0)
|  💠 include(CTest)
|  💠enable_testing()
|  💠 find_package(OpenCV REQUIRED)
|  💠 include_directories(${OpenCV_INCLUDE_DIRS})
|  💠 add_executable(Projec Folder Name  main.cpp)
|  💠 target_link_libraries(Projec Folder Name  ${OpenCV_LIBS})
|  💠 set(CPACK_PROJECT_NAME ${PROJECT_NAME})
|  💠 set(CPACK_PROJECT_VERSION ${PROJECT_VERSION})
|  💠 include(CPack)
<!--  -->
