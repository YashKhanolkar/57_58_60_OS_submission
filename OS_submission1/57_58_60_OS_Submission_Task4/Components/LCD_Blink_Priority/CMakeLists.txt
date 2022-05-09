idf_component_register(SRCS "LCD_Blink_Priority.c"
                       INCLUDE_DIRS "include"
                       REQUIRES driver
                       REQUIRES freertos
                       REQUIRES nvs_flash
                       )