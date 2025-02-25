cmake_minimum_required(VERSION 3.10)
project(my_cmake_test)

if(NOT CMAKE_CXX_STANDARD)
  set(CMAKE_CXX_STANDARD 14)
endif()

add_executable(${PROJECT_NAME}
  main.cpp 
)

#target_link_libraries(my_ros2_param_node ${YAML_CPP_LIBRARIES})