cmake_minimum_required(VERSION "3.18.2")

project("Argument")

add_executable("Argument" "main.cpp")

install(TARGETS "Argument" DESTINATION bin) #$(CMAKE_INSTALL_PREFIX)/bin
install(FILES "main.cpp" DESTINATION src)   #$(CMAKE_INSTALL_PREFIX)/src



