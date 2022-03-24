# 一个普通的项目

## css
### 盒模型
css将页面中的所有元素设置为一个矩形的盒子，将盒子摆放  
#### 内容区 content 
`width`  
`height`
#### 边框 border
大小会影响盒子大小  
`border-width`  
`border-color`  
`border-style`  
#### 内边距 padding  
#### 外边距 margin

### 动画
#### transition 过渡
1. `transition-property` 执行过渡的属性 `all`
2. `transition-duration` 过渡效果时长
3. `transition-timing-function` 过渡时序函数，过渡执行方式：  
`ease` 默认值  
`linear` 匀速  
`ease-in` 加速  
`ease-out` 减速  
`ease-in-out` 先加速后减速  
`cubic-bezier()` 贝塞尔曲线 [指定时序函数](https://cubic-bezier.com)  
`steps()` 分步执行过渡效果 (n, start/end)
4. `transition-delay` 延迟等待时间

transition可以同时设置过渡相关的所有属性 `transition: margin-left 2s 1s;`

#### transform 变形
`translateX()`  
`translateY()`  
`translateZ()`  

`rotateX()`  
`rotateY()`  
`rotateZ()`  

`perspective`视距，近大远小

先后顺序有关 `transform: translateX(xxx) rotateZ(xxx)`
#### :hover
鼠标移到

### flex
`display: flex`
`flex-direction: row/row-reverse/column/column-reverse;`
`flex-grow: 1;` 伸展系数
`flex-shrink: 1;` 收缩系数

### position
`static` 默认值  
`relative` 相对定位  
`absolute` 绝对定位  
`fixed` 固定定位  
`sticky` 粘滞定位  

offset: `top/bottom/left/right: ;`