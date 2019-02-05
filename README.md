# What is ZeroMQ?

The ZeroMQ lightweight messaging kernel is a library which extends the standard socket interfaces with features traditionally provided by specialised messaging middleware products.
Read more: www.zeromq.org

#  Building ZeroMQ using Mingw on Win32

Compiler: [Mingw 6.4.0](https://osdn.net/projects/sfnet_mingw-w64/downloads/Toolchains%20targetting%20Win32/Personal%20Builds/mingw-builds/6.4.0/threads-win32/dwarf/i686-6.4.0-release-win32-dwarf-rt_v5-rev0.7z/) (**exactly:** Mingw g++ (i686-win32-dwarf-rev0, Built by MinGW-W64 project) 6.4.0) 
Cmake: 3.11.1 (cmake.org)

Kind Note: Previous versions(~5.1.0) of Mingw seems to fail the zeromq build, therefore use version 6, but not 8 (cmake does not recognizes it).


> **Tip:** Make sure to provide runtime lib path to your application (-lrt).

