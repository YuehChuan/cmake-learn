PROJECT(qthelloworld)
cmake_minimum_required(VERSION 2.4.0)

find_package(Qt4 REQUIRED)
#add _definitions(${QT_DEFINITIONS})
#add_directories(${QT_LIBRARY_DIR})
#include_directories(${QT_INCLUDES})
include(${QT_USE_FILE})

add_executable(qthelloworld hello.cpp)
target_link_libraries(qthelloworld ${QT_LIBRARIES} ${QT_QTGUI_LIBRARIES})
