# Set minumum CMake version
cmake_minimum_required (VERSION 3.8)

# Set project name
project ("opengl-playground")

# Include sub-projects.
add_subdirectory("${CMAKE_SOURCE_DIR}/submodules/glfw")
add_subdirectory ("hello_window")
