add_executable(serverMain source/main.cpp)

target_include_directories(serverMain PUBLIC "usr/local/include")
target_link_directories(serverMain PUBLIC "usr/local/lib")
