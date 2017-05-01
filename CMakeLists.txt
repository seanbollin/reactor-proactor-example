cmake_minimum_required(VERSION 3.7)
project(reactor-proactor-example C CXX)

set(CMAKE_CXX_STANDARD 14)

set(SOURCE_FILES reactor.cpp)
add_executable(reactor-proactor-example ${SOURCE_FILES})
target_link_libraries(reactor-proactor-example)