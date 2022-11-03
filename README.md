# JuliaFormatter for Jupyter Notebook

在 Jupyter Notebook 中使用 JuliaFormatter 格式化 Julia

代码很大程度上来自 https://github.com/drillan/jupyter-black 

仅做了部分修改



Format Julia with JuliaFormatter in Jupyter Notebook

The code comes largely from https://github.com/drillan/jupyter-black

Only partially modified

## 前置条件 pre-requisites

安装如下软件包

of course, you must have some of the corresponding packages installed:

```julia
]add JuliaFormatter
add JSON
```

## 功能 Features

- 工具栏按钮（点按格式化当前代码单元，按住 Shift 点按格式全部代码单元）
- 格式化当前代码单元的快捷键：Alt-F，Mac：Option-F
- 格式化整个代码单元的快捷键：Alt-Shift-F，Mac：Option-Shift-F，与 vscode 格式化快捷键相同

- a toolbar button
- a keyboard shortcut for reformatting the current code-cell (default: Alt-F, Mac: Option-F)
- a keyboard shortcut for reformatting whole code-cells (default: Alt-Shift-F, Mac: Option-Shift-F, Same as vscode format shortcut)

## 安装 Installation

```bash
jupyter nbextension install https://github.com/jiangzhuochi/jupyter-JuliaFormatter/archive/main.zip --user
jupyter nbextension enable jupyter-JuliaFormatter-main/jupyter-JuliaFormatter
```
