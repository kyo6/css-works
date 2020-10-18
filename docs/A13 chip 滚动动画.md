# A13 chip 滚动动画

## 方案
利用 SVG，Video 和 JavaScript 动画实现.

## 实现思路
监听滚动函数，在滚动的过程中通过调整opacity控制元素的显示或隐藏并根据scroll滚动比率控制元素大小。

### 样式
chip-section：`position:sticky;top:0;`

video: `height:100vh`,宽度auto 自适应, video标签设置muted、autoplay、`playsinline`:移动端、loop属性。

h1 标题绝对定位居中显示

svg#A13 芯片绝对定位居中，并设置它的 `box-shadow: 0 0 0 100vw #000, 0 0 0 30px #000 inset;`这样可以遮罩住底部的视频。