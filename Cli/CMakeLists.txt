set(SRC_LIST cli.cxx)

add_executable (mac_cli ${SRC_LIST})

target_link_libraries (mac_cli LINK_PUBLIC Gherkin)