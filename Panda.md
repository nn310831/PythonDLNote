# Panda 常用函式
```
pip install panda
```
```Pthon
import pandas as pd
```
### pd.read_csv("檔案")
讀取檔案
通常搭配變數
```Python
data = pd.read_csv("檔案")
```
變數後加大括號可提出指定的列
```Python
data["列"]
```