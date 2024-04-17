cmake_minimum_required(VERSION 3.5)
project(helloApp
        VERSION 0.0.1
        DESCRIPTION "The Hi World App"
        LANGUAGES CXX)

add_executable(helloAppBinary main.cpp)
target_compile_features(helloAppBinary PRIVATE cxx_std_20)