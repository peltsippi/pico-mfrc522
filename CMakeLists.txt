add_library(pico_mfrc522
        mfrc522.c)


target_link_libraries(pico_mfrc522
        hardware_spi
        pico_stdlib
        )
        
target_include_directories (pico_mfrc522 PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})