add_executable(main main.cpp)

pico_enable_stdio_usb(main 1)
pico_enable_stdio_uart(main 1)
pico_add_extra_outputs(main)

target_link_libraries(main pico_stdlib)