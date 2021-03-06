# 3DRender
**软件光栅渲染器**
## 主要实现了以下功能：
## 使用说明
**Tab：**线框模型，光栅化模型，纹理模型切换 

**L**：光照开关

**相机变换**：↑↓控制相机上下移动，←→控制相机左右移动，+-控制相机前后移动，鼠标控制相机角度
## 2D部分：

 - 光栅化2D点
 - 光栅化2D直线
 - 光栅化2D三角形
##3D部分：

 - 把顶点从三维世界空间变换至二维屏幕空间，把顶点连线（如各种三维正多面体）光栅化成wire frame模型
 - 三角形光栅化
 - 使用深度缓冲
 - 实现简单的纹理映射，先做屏幕空间的插值，然后实现简单的透视纹理校正
 - 实现简单的顶点光照，使用顶点颜色插值实现Gouraud shading
 
 
 ![像素绘制](http://i.imgur.com/QOE5dDf.png)
 
	像素绘制
![三角形光栅化](http://i.imgur.com/UZXC2oK.png)

	三角形光栅化
![相框模型](http://i.imgur.com/qQDIDqA.png)

	线框模型
![](http://i.imgur.com/WJgm3oH.png)

	光栅化cube
![](http://i.imgur.com/CLny0rV.png)

	纹理模型带光照
