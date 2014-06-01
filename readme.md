# Some Engine
This engine is intended to be built in C++ with potential LuaJIT interfaces.

To build it, use `tup udp`, then run it with `bin/main`.

Presently, the tup build system may only work on Linux, as it uses `pkg-config`.

Some Engine has the following dependencies:
- luajit 2.0+
- GLFW 3
- GLEW 1.1

It targets OpenGL 3.2 and up, meaning Direct3D 10-level hardware.