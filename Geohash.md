# Geohash 的用法
> 参考教程：
> 1. https://www.jianshu.com/p/1ecf03293b9a
> 2. https://halfrost.com/go_spatial_search/

上面是比较详细的两个教程

GeoHash本质上是空间索引的一种方式，其基本原理是将地球理解为一个二维平面，将平面递归分解成更小的子块，每个子块在一定经纬度范围内拥有相同的编码。以GeoHash方式建立空间索引，可以提高对空间poi数据进行经纬度检索的效率。

总而言之，该模块可以帮忙划分城市区块。
