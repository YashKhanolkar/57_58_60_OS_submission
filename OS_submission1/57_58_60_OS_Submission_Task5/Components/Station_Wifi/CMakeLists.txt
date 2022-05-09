idf_component_register(SRCS "Station_Wifi.c"
                       INCLUDE_DIRS "include"
                       REQUIRES driver
                       REQUIRES freertos
                       REQUIRES lwip
                       REQUIRES nvs_flash
                       )