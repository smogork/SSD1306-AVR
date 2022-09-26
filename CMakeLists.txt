#####################################################################
# simple AVR library
#####################################################################
add_avr_library(
        SSD1306-AVR
        SSD1306.cpp SSD1306.h
        Framebuffer.cpp Framebuffer.h
        I2C.cpp I2C.h
)