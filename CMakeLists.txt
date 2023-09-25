cmake_minimum_required(VERSION 3.20.0)

project(openGLExercise)

add_executable(${PROJECT_NAME}
src/main.cpp
src/glad.c
)
target_link_libraries(${PROJECT_NAME} glfw)

