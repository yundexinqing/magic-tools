# 神奇妙妙工具 (magic-tools)

> 我的插件仓库。Blender 插件练手 + 真实可用插件；后续逐步加入 Unity/C# 工具。

## 定位
- **入行策略**：管线 / 工具 TA 入行 → 渲染 TA 转型（先靠 Python/C# 进游戏行业，再补美术/渲染）。
- 本仓库 = 所有插件的代码归处（练手 demo + 真实可用插件）。

## 目录约定
每个插件一个子文件夹，内部结构：
```
<插件名>/
├─ README.md     # 问题 → 方案 → 结果(带数字) → 复现步骤 → 对应 JD 自查
├─ <源码>
└─ <示例/截图>
```
- 练手期：先读/改高星插件，理解 bpy 结构与模式。
- 实战期：基于社区真实需求，做一个能跑、能用的插件。

## 技术栈路线
1. **Python (bpy)** —— Blender 插件、资产校验、批量处理（练手主战场）
2. **C# (Unity Editor)** —— 引擎内工具（生产级交付）
3. **ShaderLab / HLSL** —— 渲染方向长线（入行后并行）

## 互通说明
- Blender（DCC）与 Unity（引擎）通过 **FBX / glTF** 互通资产；插件脚本不互通（Python ≠ C#），**概念可迁移、代码需重写**。
- 参考实现：EpicGames/BlenderTools、EdyJ/blender-to-unity-fbx-exporter。

## 相关仓库
- TA-Portfolio：作品集总览（5 个项目结构，待填充）。
