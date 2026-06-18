# Z.A.T.O. 实时双语切换补丁

## 简介

为视觉小说 **Z.A.T.O. // I Love the World and Everything in It** 添加**按 T 键实时切换语言**功能。主要用于中文玩家快速获得中文翻译。

## 功能

- **按 T 键**：当前对话瞬间切换为中文
- **前进后自动还原**：点击/回车进入下一句时，自动切回英文
- **设置界面集成**：打开游戏设置（Esc → Settings），左下角有选项：
  - **自动前进 / 手动前进**：还原英文后是否自动进入下一句
  - **跳过动画 / 保留动画**：还原英文时是否跳过文字动画

## 安装

将 `toggle_language.rpy` 复制到游戏目录的 `game/` 文件夹下：

```
Z.A.T.O.  I Love the World and Everything In It/
├── game/
│   ├── toggle_language.rpy    ← 放这里
│   ├── scripts.rpa
│   └── ...
├── ZATO.exe
└── ...
```

**注意**：此补丁依赖已有的中文汉化补丁[[人工\双语]《Z.A.T.O.》汉化补丁](https://steamcommunity.com/sharedfiles/filedetails/?id=3651682454)，确保中文翻译文件存在。
[[人工\双语]《Z.A.T.O.》汉化补丁](https://steamcommunity.com/sharedfiles/filedetails/?id=3651682454) 作者:feng。感谢作者的无私奉提供这么高质量的翻译。

## 使用

| 操作 | 效果 |
|---|---|
| **按 T** | 英文 → 中文（瞬间切换） |
| **点击/回车** | 还原英文 → 进入下一句 |
| **打开设置** | 调整自动前进/跳过动画选项 |


## 兼容性

- 需要 Z.A.T.O. 中文汉化补丁（`z_SC_Main.rpa`）

## 文件

| 文件 | 说明 |
|---|---|
| `toggle_language.rpy` | 补丁主文件，所有功能在一个文件中 |
