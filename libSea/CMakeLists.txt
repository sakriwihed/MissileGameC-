# TODO Aufgabe 1:
#  Fügt dem Projekt die Bibliothek `Sea` hinzu, mit den Dateien im Verzeichnis src/libSea/.
add_library(Sea Coordinates.cpp Object.cpp)

target_include_directories(Sea PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})