add_executable(shell-app main.cpp Map.cpp NodesManager.cpp Actions.cpp Astar.cpp Iksolver.cpp)
include_directories(
    ${CMAKE_SOURCE_DIR}/include
    /usr/include/eigen3
)
