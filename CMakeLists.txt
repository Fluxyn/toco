cmake_minimum_required(VERSION 3.15)

project(toco)

set(SOURCES
    src/main.cpp
    src/lex.cpp
)

add_executable(toco ${SOURCES})

install(TARGETS toco DESTINATION bin)