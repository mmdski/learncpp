add_executable(hello hello_world.cpp)
add_executable(plus plus.cpp)
target_compile_features(plus PRIVATE cxx_std_14)
