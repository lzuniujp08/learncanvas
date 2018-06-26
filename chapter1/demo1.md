#### 1.canvas元素的大小(css设置)与绘图表面的大小(通过canvas的width和height属性设置)。

#### 2.canvas的属性：width和height；

#### 3.canvas的方法：getContext('2d')、toDataURL('image/png', .5)、toBlob();

#### 4.2d对象所含属性
![2d对象所含属性](img/draw2denv.png)

#### 5.2d对象的状态操作函数：save()、restore();
![2d对象的状态操作函数](img/状态操作函数.png)

##### 6.获取和保存函数：getImageData()和putImageData();

#### 7.数学基础
##### 1、求解代数方程；
##### 2、三角函数
> 180度=π弧度

>1弧度=(π/180)*度

>1度=(180/π)*弧度

```js
Math.PI;
Math.sin((π/180)*30);
```