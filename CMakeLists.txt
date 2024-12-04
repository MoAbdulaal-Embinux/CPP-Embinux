cmake_minimum_required(VERSION 3.5)

# Project name and version
project(CPP_Embinux)

# Add the executable target
add_executable(CPP_Embinux embinux.cpp)

# Install to the target
install(TARGETS CPP_Embinux DESTINATION bin)
