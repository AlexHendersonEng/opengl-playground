# Add source to this project's executable.
add_executable(hello_window "main.cpp" "${CMAKE_SOURCE_DIR}/external/glad/src/gl.c")

# Add include directories
include_directories("${CMAKE_SOURCE_DIR}/external/glad/include")

# Link libraries
target_link_libraries(hello_window PRIVATE glfw)
