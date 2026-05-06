add_executable(solver equation.cpp)
target_link_libraries(solver formatter_ex solver_lib)
target_include_directories(solver PUBLIC
${CMAKE_SOURCE_DIR}/solver_lib
${CMAKE_SOURCE_DIR}/formatter_ex_lib
${CMAKE_SOURCE_DIR}/formatter_lib
)
