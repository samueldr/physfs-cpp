cmake_minimum_required(VERSION 2.6)
project(PhysFS++)
find_package(PhysFS REQUIRED)
include_directories(${PHYSFS_INCLUDE_DIR})
include_directories(include)
add_subdirectory(src)
INSTALL(FILES include/physfs.hpp DESTINATION include)
