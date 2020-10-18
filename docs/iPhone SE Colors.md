# iPhone SE Colors

## 设计思路
利用css3新增的clip-path和三张不同颜色的iPhone SE 来实现滚动式文字不动，但背景回切换的换色效果。

## 实现方案
整个换色区域由黑、白、红三张背景构成，设置它们的定位为`position:absolute`；
当页面滚动到换色区域时，该区域的容器设置`position:sticky;top:0`;

###