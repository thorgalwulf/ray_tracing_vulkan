# Ray Tracing with Vulkan

Repository to study graphics using Vulkan. 

From the project: [NVIDIA Vulkan Ray Tracing Tutorials](github.com/nvpro-samples/vk_raytracing_tutorial_KHR)

---

# Environment Setup

### 1. Dependencies (Vulkan Drivers, Visual Studio and CMAKE)
- [Vulkan Windows SDK](https://vulkan.lunarg.com/sdk/home)
- [Nvidia Vulkan Drivers](https://developer.nvidia.com/vulkan-driver)
- [Visual Studio](https://visualstudio.microsoft.com/downloads/)
- [CMAKE](https://cmake.org/download/)

### 2. Clone (Download)
```bash
git clone https://github.com/nvpro-samples/build_all.git
cd build_all
clone_all.bat
```

### 3. Build
- Generate the build directory, solution file and release directory with the .exe files
```bash
cd samples\vk_raytracing_tutorial_KHR
mkdir build
cd build
cmake .. -G "Visual Studio 17 2022" -A x64
cmake --build . --config Release  
```

### 4. Run
```bash
cd build_all\bin_x64\Release
build_all\bin_x64\Release>vk_ray_tracing__before_KHR.exe
```

---

# Repository

```
build_all                                      Main directory
build_all\samples\vk_raytracing_tutorial_KHR   Project directory
build_all\bin_x64\Release                      Executable (.exe) files
```

---
