set(SOURCES
    core/common.h
    core/difficulty.cpp
    core/difficulty.h
    core/uintBig.cpp
    core/uintBig.h
    utility/common.cpp
    utility/common.h
)

add_library(beam STATIC ${SOURCES})
target_include_directories(beam PRIVATE . ..)

