set(SRC_LIST)

include_directories (../include)

set(
    SRC_LIST
    ./main.cpp
    ./add.cpp
)
add_executable (main ${SRC_LIST})

set (EXECUTABLE_OUTPUT_PATH ${PROJECT_SOURCE_DIR}/bin)
