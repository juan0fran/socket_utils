file (GLOB_RECURSE utils *)

add_library(utils  SHARED  ${utils})

set_target_properties(utils PROPERTIES
            VERSION 0.1
            SUBVERSION 1)

target_link_libraries(utils)
