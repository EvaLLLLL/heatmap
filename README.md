# 热力图

点击预览：https://evalllll.github.io/heatmap/index.html

实现思路如下：

1. 加地图：使用百度地图 API 初始化地图
2. 转数据：将原始中文地址转换成地图可识别 point
3. 加绘制层：给地图添加自定义绘制层
4. 画绘制层：用canvas的api绘制每个点的样式
5. 将绘制层添加在地图上

参考文档：

1. [百度地图JSAPI v3.0](http://lbsyun.baidu.com/jsdemo.htm#canvaslayer)
2. [canvas](https://developer.mozilla.org/zh-CN/docs/Web/API/Canvas_API)
3. [CanvasRenderingContext2D.globalAlpha - MDN](https://developer.mozilla.org/zh-CN/docs/Web/API/CanvasRenderingContext2D/globalAlpha)
4. [CanvasRenderingContext2D.createRadialGradient() - MDN](https://developer.mozilla.org/zh-CN/docs/Web/API/CanvasRenderingContext2D/createRadialGradient)
5. [你不知道的前端算法之热力图的实现 - 知乎](https://zhuanlan.zhihu.com/p/32362059)
