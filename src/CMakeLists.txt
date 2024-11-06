add_library(add STATIC add.c)
add_executable(add_run main.cpp)

target_include_directories(add PUBLIC ${PROJECT_SOURCE_DIR}/include)
target_link_libraries(add_run PUBLIC add)
