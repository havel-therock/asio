cmake_minimum_required(VERSION 3.25.1)


project(asio)


add_library(${PROJECT_NAME} INTERFACE)
target_include_directories(${PROJECT_NAME} INTERFACE ${CMAKE_CURRENT_SOURCE_DIR}/asio/include)
