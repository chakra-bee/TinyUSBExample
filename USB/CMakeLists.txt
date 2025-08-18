add_library(usb)

target_sources(usb INTERFACE
                msc_disk.c
                usb_descriptors.c)

target_include_directories(usb INTERFACE ${CMAKE_CURRENT_SOURCE_DIR})