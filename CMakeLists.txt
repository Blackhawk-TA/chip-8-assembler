cmake_minimum_required(VERSION 3.26)
project(chip_8_assembler)

set(CMAKE_CXX_STANDARD 17)

add_executable(chip_8_assembler main.cpp
        src/assembler.cpp
        src/assembler.hpp
        src/disassembler.cpp
        src/disassembler.hpp
        src/file_handler.cpp
        src/file_handler.hpp
        src/parameters.cpp
        src/parameters.hpp
)
