# windows 编译指令
### 使用clang-cl编译
```bash
clang-cl main.cpp ./imgui/*.cpp ./imgui/backends/imgui_impl_win32.cpp ./imgui/backends/imgui_impl_dx11.cpp /I./imgui/ /I./imgui/backends/ /Femy_imgui /link d3d11.lib
```