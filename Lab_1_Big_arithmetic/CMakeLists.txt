cmake_minimum_required(VERSION 3.16)

project(Lab_1_Big_arithmetic LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(Lab_1_Big_arithmetic main.cpp)

include(GNUInstallDirs)
install(TARGETS Lab_1_Big_arithmetic
    LIBRARY DESTINATION ${CMAKE_INSTALL_LIBDIR}
    RUNTIME DESTINATION ${CMAKE_INSTALL_BINDIR}
)
