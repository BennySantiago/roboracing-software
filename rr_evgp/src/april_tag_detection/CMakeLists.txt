add_executable(april_tag_pointcloud tag_detection.cpp tag_detection.h)
target_link_libraries(april_tag_pointcloud ${catkin_LIBRARIES} ${OpenCV_LIBS})