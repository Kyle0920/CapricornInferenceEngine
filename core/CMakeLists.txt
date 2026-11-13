add_library(CapricornCore SHARED

    Inference.cpp


)

target_include_directories(CapricornCore PUBLIC
        ${CMAKE_CURRENT_SOURCE_DIR}
)