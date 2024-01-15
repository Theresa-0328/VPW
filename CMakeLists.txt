cmake_minimum_required (VERSION 3.26)

project ("VPW")

add_executable (VPW "VPW.cpp" "VPW.h")

if (CMAKE_VERSION VERSION_GREATER 3.12)
  set_property(TARGET VPW PROPERTY CXX_STANDARD 20)
endif()