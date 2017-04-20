set(SRC_LIST gherkin.cxx)

add_library (Gherkin ${SRC_LIST})

target_include_directories (Gherkin PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})