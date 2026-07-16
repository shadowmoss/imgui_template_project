#### 创建
在自己的main.cpp文件中引入
```cpp
#include "imgui.h"
#include "imgui_impl_win32.h"
#include "imgui_impl_dx11.h"
```
#### 头文件解释
imgui.h是imgui的头文件，前端头文件。
imgui_impl_xxx.h是你目标平台的实现后端的头文件
#### 编译指令解释
需要将imgui项目根目录下的所有头文件和.cpp文件添加到编译路径中。
需要将imgui/backends目录下的所有头文件和.cpp文件添加到编译路径当中。
使用到的后端库图形库，需要添加到链接路径当中，如，在windows下使用DX11/DX10/DX12等图形库，需要将对于的/d3d12.lib/d3d10.lib/d3d11.lib添加到链接路径当中。