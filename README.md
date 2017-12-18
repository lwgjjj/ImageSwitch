# 图片碰撞
- 基本功能
1. 九宫格内的图片，拖拽某一张和其它的图片位置发生交叉的时候会互换位置
2. 如果拖拽图片和多张图片相互碰撞，计算最大接触面积
3. 放手后，图片交换位置，有简单的动画效果
4. 图片不能被拉出范围之外，当鼠标位于矩形范围外的时候，会释放掉对图片的拉取
5. 图片碰撞的时候会为碰撞的图片加边框，以及更改拖拽物体的层级，使其位于最上层
- 拓展功能
1. 拖拽外部图片到某位置放下，会实现图片上传的功能
2. 读取上传的图片展示到当前位置
3. 图片自动放置到最后面
4. 盒子宽度和高度自适应
5. 点击按钮上传图片，同样将图片放置到当前容器的最后面
6. 同样实现点击排序随机排序，偶数好排，两两排序，奇数一个不动，其余的两两互换位置

7. 测试提交
