set(Boost_USE_STATIC_LIBS OFF)
find_package(Boost REQUIRED COMPONENTS unit_test_framework)
include_directories(${Boost_INCLUDE_DIRS})

add_subdirectory(config_test)
