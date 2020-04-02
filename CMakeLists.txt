project(pugixml)
cmake_minimum_required(VERSION 3.8)

add_library(pugixml src/pugixml.cpp)
target_include_directories(pugixml SYSTEM PUBLIC src)
target_compile_features(pugixml PUBLIC cxx_std_11)
