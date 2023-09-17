cmake_minimum_required(VERSION 3.10)

project(HLLib)

add_library(libhl BSPFile.cpp Checksum.cpp DebugMemory.cpp DirectoryFile.cpp
        DirectoryFolder.cpp DirectoryItem.cpp Error.cpp FileMapping.cpp
        FileStream.cpp GCFFile.cpp GCFStream.cpp HLLib.cpp
        Mapping.cpp MappingStream.cpp MemoryMapping.cpp MemoryStream.cpp
        NCFFile.cpp NullStream.cpp PAKFile.cpp Package.cpp ProcStream.cpp
        SGAFile.cpp Stream.cpp StreamMapping.cpp Utility.cpp VBSPFile.cpp
        VPKFile.cpp WADFile.cpp Wrapper.cpp XZPFile.cpp ZIPFile.cpp
)

set(CMAKE_CXX_STANDARD 14)