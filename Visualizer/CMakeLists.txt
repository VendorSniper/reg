ADD_LIBRARY(Visualizer Visualizer.cpp)
TARGET_INCLUDE_DIRECTORIES(Visualizer PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})
TARGET_LINK_LIBRARIES(Visualizer ITKtoVTK)