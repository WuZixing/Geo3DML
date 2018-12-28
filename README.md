Geo3DML
===

Geo3DML: Three-Dimensional Geological Model Markup Language，三维地质模型数据交换格式。

Geo3DML(v1.0)是中国地质调查局地质调查技术标准（DD2015-06）。

结合工作需要，基于标准原稿进行扩充和更新是本项目的工作内容，**更新的内容不一定会被标准接受**。

为与标准原稿区分，暂定当前版本号为1.1.x。

主要更新内容
===

1. 新增几何数据结构：`geo3dml:GeoSGrid`；

2. 新增几何数据结构：`geo3dml:GeoUniformGrid`；

3. 元素`GeoFeature`下新增子元素`Geometries`，作为`Geometry`的父标签，并且允许元素`Geometry`出现多次；

4. 元素`Geometry`新增属性`Name`、`LOD`，分别记录几何对象的名字和LOD（Level Of Detail）层级；

5. 元素`Geo3DModel`新增属性`ID`。
