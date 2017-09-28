file (GLOB example main.cpp)

set(EXAMPLE_BIN ${PROJECT_SOURCE_DIR}/bin/${CMAKE_BUILD_TYPE}/sensor_core CACHE STRING "example dir")

add_executable(example ${example})

target_link_libraries(example utils)
