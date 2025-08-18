add_library(usb INTERFACE)

target_sources(usb INTERFACE
        ${CMAKE_CURRENT_SOURCE_DIR}/msc_disk.c
        ${CMAKE_CURRENT_SOURCE_DIR}/usb_descriptors.c)

target_include_directories(usb INTERFACE
                            ${CMAKE_CURRENT_SOURCE_DIR}
                            )