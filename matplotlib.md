# matplotlib
## matplotlib.pyplot
### plt.scatter( "x" , "y" , 各種參數)
畫出散佈圖
```Python
plt.scatter(x , y , marker="x" , color = "red")
```
### plt.title("文字")
設定圖表標題
### plt.xlabel("文字")、plt.ylabel("文字")
設定軸的標題
### plt.plot(x , y , label="文字")
畫出直線
```Python
#基於 y_pred(要預測的值) = w*x + b
plt.plot(x , y_pred , label="預測線")
```
### plt.xlim([min,max])、、plt.ylim([min,max])
設定軸的最大最小值
```Python
plt.xlim([0,12]) #設定X範圍
plt.ylim([-60,120]) #設定Y範圍
```
### plt.legend()
顯示圖例
### plt.show()
顯示圖表