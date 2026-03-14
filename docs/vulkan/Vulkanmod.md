<div align="center">

# VulkanMOD

</div>

## 前言

VulkanMod 是一个强大的优化模组，让 Minecraft 使用 Vulkan 渲染，而不是使用 OpenGL 渲染。使在手机上运行 Minecraft: Java Edition 时，有高效的 GPU 资源利用，同时避免消耗在使用渲染器时转译浪费的 CPU 资源。

## 相关链接

- **[MC百科](https://www.mcmod.cn/class/6626.html)**
- **[Modrinth 下载](https://modrinth.com/mod/vulkanmod)**
- **[CurseForge 下载](https://www.curseforge.com/minecraft/mc-mods/vulkanmod)**

## 注意事项

### 1. VulkanMod Android Lib 缺失

- **原因**: 官方不对 Android 进行兼容，但提供了所需 [Lib](https://www.curseforge.com/minecraft/mc-mods/vulkanmod-android-libs)
- **修复建议**：
  - 使用他人已经修改好的版本（见[成品 VulkanMod](/docs/vulkan/VulkanMod-Done)）
  - 自己修改（提供教程，详见 [Android Lib](/docs/vulkan/AndroidLib)）

::: tip 提示
MC 百科说是放在 mods 即可，但实际看来似乎不可行。
:::

### 2. Vulkan API 版本过低

- **原因**: 个人设备问题
- **修复建议**：
  - 换手机
  - Adreno 6xx/7xx 可尝试 Root 后刷入 Turnip Vulkan 驱动

::: tip 提示
骁龙 GPU (Adreno) 6xx/7xx 一般支持 Turnip 驱动，支持 Vulkan 1.3（1.4 目前仅限 7xx，启动器暂未更新到该版本 Turnip）。

骁龙启动时一般使用启动器中的 Turnip 驱动，如果要使用系统/刷入的驱动，请打开"允许 Zink 使用系统 Vulkan 鵑动"。

注意：是 GPU 型号，不是 SOC（芯片）型号。
:::

### 3. Vulkan 版本要求

- **最低要求**: Vulkan 1.2+
- **推荐**: Vulkan 1.3+

查看 Vulkan 版本请参阅 [Vulkan 版本查看](/docs/vulkan/VulkanAPI-Check)。

---

## 署名

**编辑作者**: [空心](https://github.com/KongXing0819)  
**创建时间**: 2024.12.22  
**修改时间**: 2024.12.23
