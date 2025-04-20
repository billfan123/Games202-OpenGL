cmake_minimum_required(VERSION 3.17)

set(CMAKE_CXX_COMPILER "C:/Users/59901/Documents/lib/mingw64/bin/g++.exe")
set(CMAKE_C_COMPILER "C:/Users/59901/Documents/lib/mingw64/bin/gcc.exe")

project(Games202 LANGUAGES CXX C)

# set(CMAKE_ARCHIVE_OUTPUT_DIRECTORY ${PROJECT_SOURCE_DIR}/bin)
# set(CMAKE_LIBRARY_OUTPUT_DIRECTORY ${PROJECT_SOURCE_DIR}/bin)
# set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${PROJECT_SOURCE_DIR}/bin)

set(BUILD_ENABLE_OPENGL ON)
add_subdirectory(ext/CGUtils)

add_subdirectory(src/1.ShadowMap)
add_subdirectory(src/2.PRT)
add_subdirectory(src/3.SSRT)
add_subdirectory(src/4.KullaContyBRDF)