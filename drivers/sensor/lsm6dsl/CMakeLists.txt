zephyr_library()

zephyr_library_sources_ifdef(CONFIG_LSM6DSL            lsm6dsl.c)
zephyr_library_sources_ifdef(CONFIG_LSM6DSL_SPI        lsm6dsl_spi.c)
zephyr_library_sources_ifdef(CONFIG_LSM6DSL_I2C        lsm6dsl_i2c.c)
zephyr_library_sources_ifdef(CONFIG_LSM6DSL_TRIGGER    lsm6dsl_trigger.c)
zephyr_library_sources_ifdef(CONFIG_LSM6DSL_SENSORHUB  lsm6dsl_shub.c)
