idf_component_register(SRCS "priority.c"
                       INCLUDE_DIRS "include"
                       REQUIRES driver
                       REQUIRES freertos
                       REQUIRES nvs_flash
                       )