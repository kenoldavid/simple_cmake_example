project(SimpleCmakeExample)

# Builds a STATIC library, by default
add_library(simplecmake
	printhello.cpp
)

target_include_directories(simplecmake
	PUBLIC
	   ${CMAKE_CURRENT_SOURCE_DIR}/../include
)
