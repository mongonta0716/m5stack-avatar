FILE(GLOB COMPONENT_SRCS
     src/*.cpp)

# Make Avatar component available to ESP-IDF builds.
idf_component_register(SRCS ${COMPONENT_SRCS}
                       INCLUDE_DIRS src
                       REQUIRES m5unified)
