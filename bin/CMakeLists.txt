project(bin)

add_executable(bin main.cpp)

target_include_directories(bin PUBLIC .)
target_link_libraries(bin sfml-graphics sfml-audio lib)
