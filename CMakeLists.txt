# CMakeList.txt : CMake project for NonLinear_optimization, include source and define
# project specific logic here.
#
cmake_minimum_required (VERSION 3.8)
project ("TestYOCTO")
set(CXX_STANDARD_REQUIRED 14)
add_executable(${PROJECT_NAME} src/main.cpp)
target_link_libraries(${PROJECT_NAME} -pthread)
install(TARGETS ${PROJECT_NAME})