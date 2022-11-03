# Jupyter JuliaFormatter [JuliaFormatter for Jupyter Notebook]

在 Jupyter Notebook 中使用 JuliaFormatter 格式化 Julia
代码很大程度上来自 https://github.com/drillan/jupyter-black 
仅做了部分修改

Inspired by https://github.com/drillan/jupyter-black, Only partially modified

**pre-requisites:** of course, you must have some of the corresponding packages installed:

```julia
]add JuliaFormatter
add JSON
```

Then the extension provides

- a toolbar button
- a keyboard shortcut for reformatting the current code-cell (default: Alt-F)
- a keyboard shortcut for reformatting whole code-cells (default: Alt-Shift-F, Same as vscode format shortcut)

## Installation

```bash
jupyter nbextension install https://github.com/jiangzhuochi/jupyter-JuliaFormatter/archive/master.zip --user
jupyter nbextension enable jupyter-JuliaFormatter-master/jupyter-JuliaFormatter
```
