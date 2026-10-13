# Revit pyRevit Tools

一套基于 pyRevit 的 Revit 工具集，用于处理日常建模中的重复性操作。

A collection of pyRevit tools for Autodesk Revit, built to handle repetitive modeling tasks.

---

## 工具列表 / Tools

### 延伸墙梁 / Extend Walls and Beams

框选一批墙或梁，点选目标构件，自动批量延伸。

Box-select multiple walls or beams, pick a target, and batch-extend them.

- 自动保护墙上的门窗 / Automatically protects doors and windows
- 自动跳过机电类构件 / Skips MEP elements
- 文件夹：`延伸墙梁.pushbutton/`

---

## 环境要求 / Requirements

- Autodesk Revit 2020
- pyRevit 6.5.3+
- Windows

---

## 安装方法 / Installation

1. 下载本仓库的 `.pushbutton` 文件夹
   Download the `.pushbutton` folder from this repo.

2. 复制到 pyRevit 扩展目录：
   Copy it to your pyRevit extensions folder:
%APPDATA%\pyRevit\Extensions\MyTools.extension\MyTab.tab\Favorites.panel\

3. 打开 Revit，点击 pyRevit 选项卡里的 **Reload**
Open Revit, click **Reload** in the pyRevit tab.

---

## 开源协议 / License

MIT
