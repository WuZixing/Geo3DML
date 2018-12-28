Geo3DML
===

*2018-12-28*

Geo3DML: Three-Dimensional Geological Model Markup Language，三维地质模型数据交换格式。

Geo3DML(v1.0)是中国地质调查局地质调查技术标准（DD2015-06）。

*Release Geo3DML v1.0.0*与标准原稿内容一致。分支*v1*包含对标准原稿内容的勘误。

分支*master*是结合工作需要，对标准原稿进行扩充和更新，**更新的内容不一定会被标准接受**。为与标准原稿区分，*master*分支的当前版本号约定为1.x。

主要更新内容
===

1. 新增几何数据结构：`geo3dml:GeoSGrid`；

2. 新增几何数据结构：`geo3dml:GeoUniformGrid`；

3. 元素`GeoFeature`下新增子元素`Geometries`，作为`Geometry`的父标签，并且允许元素`Geometry`出现多次；

4. 元素`Geometry`新增属性`Name`、`LOD`，分别记录几何对象的名字和LOD（Level Of Detail）层级；

5. 元素`Geo3DModel`新增属性`ID`。
