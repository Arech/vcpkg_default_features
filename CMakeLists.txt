cmake_minimum_required(VERSION 3.16)
# choosing feature list (depending on some CMake vars in a real project)..
set(VCPKG_MANIFEST_FEATURES "myfeature")
# trigger vcpkg
project(MyTestProj)
