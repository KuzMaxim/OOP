cmake_minimum_required(VERSION 3.10)
project(2ndTask)

# ��������� �������� C++
set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED True)

# ��������� ����� � ��������
include_directories(stc)

# ��������� ����������� ����, ���������� ��� cpp �����
add_executable(test_basic
    src/library.cpp
    src/library.hpp
    tests/test_basic.cpp
)
