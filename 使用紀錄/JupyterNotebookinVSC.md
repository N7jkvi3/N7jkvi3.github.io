# 如何在VS Code使用Jupyter Notebook

## 準備項目
1. [Visual Studio Code](https://code.visualstudio.com)
2. [Python](https://www.python.org)
    - [pip](https://pypi.org/project/pip)：可幫助 Python 安裝 Package 。
        > pip is the package installer for Python. You can use pip to install packages from the Python Package Index and other indexes. by [介紹](https://pypi.org/project/pip)
    - [ipykernel](https://pypi.org/project/ipykernel)：Jupyter 提供 IPython 內核。
        > This package provides the IPython kernel for Jupyter. by [介紹](https://pypi.org/project/ipykernel)

## 簡易安裝步驟
第一步：先在官網下載最新版本的[Visual Studio Code](https://code.visualstudio.com)和[Python](https://www.python.org)。

第二步：打開終端機[^1]，輸入以下內容：
```
python -m ipykernel install
```

第三步：打開[Visual Studio Code](https://code.visualstudio.com)，從以下步驟中選擇一項來建立[Jupyter Notebook](https://jupyter.org)
- 在快速入門(歡迎頁面)選擇新增檔案；
- 在上方工具列的【檔案(F)】中選擇新增檔案；
- 使用快捷鍵 `Ctrl + Shift + p`[^2]，叫出指令欄，輸入 `Create: New Jupyter Notebook`[^3]。


[^1]: 這邊提供三種開啟終端機的方法：<br>- 在工作列的Windows按鈕上右鍵，選擇【Windows 終端機】；<br>- 使用快捷鍵 `win + x`，選擇【Windows 終端機】；<br>- 在檔案總管的標題列(地址列)中，輸入 `cmd` 或 `powershell`。

[^2]: 用快捷鍵 `Ctrl + p` 叫出搜尋檔案欄，然後輸入 `>`，再輸入指令也是一種方法。
[^3]: [Visual Studio Code](https://code.visualstudio.com)的指令/檔案搜尋欄都採用**模糊搜尋**，因此輸入 `new jupy` 或 `n j` 都能找到 `Create: New Jupyter Notebook`指令。