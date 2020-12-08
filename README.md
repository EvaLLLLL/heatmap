# 热力图

点击预览：https://evalllll.github.io/heatmap/index.html

实现思路如下：

    1. 加地图：使用百度地图 API 初始化地图
    2. 转数据：将原始中文地址转换成地图可识别 point
    3. 加绘制层：给地图添加自定义绘制层
    4. 画绘制层：用canvas的api绘制每个点的样式
    5. 将绘制层添加在地图上
