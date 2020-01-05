project(aula)

cmake_minimum_required(VERSION 2.8)

# Find the QtWidgets library
find_package(Qt5 REQUIRED
    Core
    Qml
    Quick
    Widgets
)
add_subdirectory(src)