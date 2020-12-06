cmake_minimum_required(VERSION 3.17)
project(mixture_Gaussian_matrix)

set(CMAKE_CXX_STANDARD 14)
set(OpenCV_DIR E:\\opencv4.x\\opencv\\mingw_build\\install)
find_package(OpenCV REQUIRED)
add_executable(mixture_Gaussian_matrix main.cpp)
target_link_libraries(mixture_Gaussian_matrix ${OpenCV_LIBS})