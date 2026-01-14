# Make Avatar component available to ESP-IDF builds.
idf_component_register(SRC_DIRS src
                       INCLUDE_DIRS src
                       REQUIRES m5unified)
