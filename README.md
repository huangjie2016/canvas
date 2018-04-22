# canvas
canvas study

## 一些小知识
0. canvas是基于状态的绘制。<br/>
1. 状态设置： moveTo\lineTo\lineWidth\strokeStyle\fillStyle\...<br/>
2. 绘制： fill\stroke<br/>
3. moveTo落笔的坐标，lineTo绘制的坐标<br/>
4. 如果要给下一段设置不同的样式，可以用beginPath()表示开始一段全新的状态。<br/>
5. beginPath()配合closePath() 可以无缺口完美封闭绘制的多边形。<br/>
6. 填充色：fillStyle，之后要执行fill()才能生效，如果要给边框加颜色也要在fill()方法之后添加，否则边框的宽度会变小。<br/>

### 日常填坑记录
1. 创建canvas元素要使用canvas标签，用div浏览器会报错，没有getContent方法。<br/>
