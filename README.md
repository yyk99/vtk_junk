Let's see the VTK guts color...

REQUIRED:

    apt install libvtk9-dev
    apt install libvtk9-qt-dev

BUILD:

    cmake -B build-SimpleView -S Qt/SimpleView
    cmake --build build-SimpleView
