cmake_minimum_required(VERSION 3.29)
project(GameCA)

set(CMAKE_CXX_STANDARD 20)

set(SFML_DIR "C:/Program Files/JetBrains/CLion 2024.2.2/bin/mingw/lib/gcc/x86_64-w64-mingw32/13.1.0/include/SFML/lib/cmake/SFML")


find_package(SFML 3.0 COMPONENTS graphics window system REQUIRED)


add_executable(GameCA main.cpp)

target_link_libraries(GameCA sfml-graphics sfml-window sfml-system)