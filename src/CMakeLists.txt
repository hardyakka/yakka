project(Yakka)
cmake_minimum_required(VERSION 2.8)


include_directories(libyakka)
add_subdirectory(libyakka)
add_subdirectory(yakka-cmd)
add_subdirectory(yakka-gui)

