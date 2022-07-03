project(bitmap)

add_library(${PROJECT_NAME} "bitmap_image.cpp")
target_include_directories(${PROJECT_NAME} PUBLIC ${PROJECT_SOURCE_DIR})