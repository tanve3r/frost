set(component_srcs "src/rgb_led_strip.c")

idf_component_register(SRCS "${component_srcs}"
                       INCLUDE_DIRS "inc"
                       PRIV_INCLUDE_DIRS ""
                       PRIV_REQUIRES "driver"
                       REQUIRES "")