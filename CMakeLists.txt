cmake_minimum_required(VERSION 3.21)
project(Snake2 C)

set(CMAKE_C_STANDARD 23)

add_executable(Snake2 main.c)

target_link_libraries(Snake2 -lmingw32 -lSDL2main -lSDL2 -lSDL2_ttf -lSDL2_mixer -lSDL2_image)
