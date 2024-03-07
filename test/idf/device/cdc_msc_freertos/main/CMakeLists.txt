# This file is for ESP-IDF only
idf_component_register(SRCS "main.c"
                    INCLUDE_DIRS ".")

idf_component_get_property(tusb_lib tinyusb_src COMPONENT_LIB)

target_include_directories(${tusb_lib} PUBLIC "${CMAKE_CURRENT_LIST_DIR}")
target_sources(${tusb_lib} PUBLIC "${CMAKE_CURRENT_LIST_DIR}/usb_descriptors.c" "${CMAKE_CURRENT_LIST_DIR}/msc_disk.c")
