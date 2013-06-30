
set(yakka-cmd_SRCS
    yakka-cmd.cpp
)

add_executable(yakka ${yakka-cmd_SRCS})
target_link_libraries(yakka libyakka)