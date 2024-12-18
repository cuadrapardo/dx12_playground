# CMakeList.txt : CMake project for dx12_playground, include source and define
# project specific logic here.
#

# Add source to this project's executable.
add_executable (dx12_playground "dx12_playground.cpp" "dx12_playground.h")

if (CMAKE_VERSION VERSION_GREATER 3.12)
  set_property(TARGET dx12_playground PROPERTY CXX_STANDARD 20)
endif()

# TODO: Add tests and install targets if needed.
