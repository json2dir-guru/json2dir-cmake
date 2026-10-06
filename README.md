# json2dir-cmake

json2dir in pure CMake script mode: reads a JSON document from stdin and creates the directory tree it describes in the current directory.

    cmake -P json2dir.cmake < document.json
