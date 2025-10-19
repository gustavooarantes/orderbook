cmake_minimum_required(VERSION 3.10)
project(Orderbook VERSION 0.1 LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

# Headers path
include_directories(include)

# Add src folder
add_subdirectory(src)
