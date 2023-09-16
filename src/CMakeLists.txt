cmake_minimum_required(VERSION 3.6)

add_subdirectory(YgEngine)

add_executable(PINN main.cxx)
target_link_libraries(PINN PUBLIC)
