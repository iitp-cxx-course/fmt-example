cmake_minimum_required(VERSION 3.10.0)

add_executable(proj main.cpp)
target_link_libraries(proj PUBLIC default CONAN_PKG::cpr)
