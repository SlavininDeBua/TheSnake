project(lib)

file(GLOB_RECURSE ALL_SOURCE_FILES *.cpp *.h *.hpp)

add_library(lib STATIC ${ALL_SOURCE_FILES})
target_include_directories(lib PUBLIC .)