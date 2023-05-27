cmake_minimum_required(VERSION 3.5)

project(homework_06 LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(homework_06
    main.cpp
    Containers.h
)

install(TARGETS homework_06
    LIBRARY DESTINATION ${CMAKE_INSTALL_LIBDIR})
