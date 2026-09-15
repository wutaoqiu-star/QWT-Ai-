# QuickLook.Plugin.FbxViewer 1.3.0

这是一个面向 Windows QuickLook 的 FBX 静态模型预览插件。

## 本版内容

- 专业深色工具栏、显示模式选择器、灯光菜单和状态栏。
- 材质、白模、漫反射、金属度、粗糙度五种显示模式。
- 可叠加线框；修复 `Alt + W` 在 WPF 中无法触发的问题。
- Substance 3D Painter 风格操作：`Alt + 左键` 旋转、`Alt + 中键` 平移、`Alt + 右键` 缩放、`Shift + 右键` 调整灯光、`F` 聚焦模型。
- 支持标准 PBR 通道和 3ds Max FBX 材质字段。
- 支持中文目录和中文文件名。

## 安装

1. 下载 `QuickLook.Plugin.FbxViewer-v1.3.0.qlplugin`。
2. 在文件资源管理器中选中该文件并按空格。
3. 点击 QuickLook 的安装按钮，然后重启 QuickLook。

基于 QuickLook 4.5.0 编译。安装包已包含 AssimpNet 和 x64/x86 原生 Assimp 依赖，不包含宿主提供的 `QuickLook.Common.dll`。
