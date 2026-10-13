# Revit Extend Walls and Beams

一个基于 pyRevit 的 Revit 工具：批量延伸墙和梁到目标构件。

A pyRevit tool for Autodesk Revit: batch-extend walls and beams to a target element.

---

## 功能 / Features

- 框选一批墙或梁 / Box-select multiple walls or beams
- 点选一个目标构件 / Pick one target element
- 自动延伸，无需逐个操作 / Batch extend, no one-by-one picking
- 自动保护墙上的门窗 / Automatically protects doors and windows on walls
- 自动跳过机电类构件 / Skips MEP elements (pipes, ducts, etc.)

---

## 环境要求 / Requirements

- Autodesk Revit 2020
- pyRevit 6.5.3+
- Windows

---

## 安装方法 / Installation

1. 下载本仓库的 `延伸墙梁.pushbutton` 文件夹
   Download the `延伸墙梁.pushbutton` folder from this repo.

2. 复制到 pyRevit 扩展目录：
   Copy it to your pyRevit extensions folder:
   %APPDATA%\pyRevit\Extensions\MyTools.extension\MyTab.tab\Favorites.panel\

4. 打开 Revit，点击 pyRevit 选项卡里的 **Reload**
Open Revit, click **Reload** in the pyRevit tab.

5. 按钮会出现在你的自定义面板里
The button will appear in your custom panel.

---

## 使用方法 / Usage

1. 点击按钮 / Click the button
2. 框选要延伸的墙或梁，按 **完成** 确认 / Box-select walls or beams, press **Enter**
3. 点选一个目标构件 / Pick a target element
4. 脚本自动处理，弹窗显示结果 / The script runs and shows a result dialog

---

## 已知限制 / Known Limitations

- 机电类构件不支持 / MEP elements are not supported
- 梁的 LocationCurve setter 在部分环境下可能不可用
The LocationCurve setter for beams may be read-only in some environments
- 缩短构件的操作默认被拒绝（保护门窗）
Shortening operations are refused by default (to protect openings)

---

## 开源协议 / License

MIT
