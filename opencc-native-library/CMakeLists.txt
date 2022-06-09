cmake_minimum_required(VERSION 3.7)
project(opencc_android CXX)

add_subdirectory(OpenCC build)

set(OPENCC_TARGET libopencc)

target_sources(${OPENCC_TARGET} PRIVATE ${CMAKE_CURRENT_SOURCE_DIR}/interface.cpp ${CMAKE_CURRENT_SOURCE_DIR}/interface.def)