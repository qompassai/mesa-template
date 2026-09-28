# Mesa quickstart

Mesa is the open-source OpenGL / Vulkan / OpenCL implementation for Linux: https://www.mesa3d.org/

Useful starting points:
- Check your drivers: `glxinfo -B` (OpenGL), `vulkaninfo --summary` (Vulkan via Lavapipe/RADV).
- Force software rendering: `LIBGL_ALWAYS_SOFTWARE=1`.
- Debug: `MESA_DEBUG=1`, `VK_LOADER_DEBUG=all`.
- Source: https://gitlab.freedesktop.org/mesa/mesa
