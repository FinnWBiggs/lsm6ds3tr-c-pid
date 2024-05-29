zephyr_library(
  NAME lsm6ds3
  SOURCES
    lsm6ds3.c
  PUBLIC_HEADER
    lsm6ds3.h
)

target_include_directories(lsm6ds3 PUBLIC
  ${CMAKE_CURRENT_LIST_DIR}/
)