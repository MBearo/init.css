# 初始化css和常用工具类
> 解决浏览器间差异引用 [normalize](https://github.com/necolas/normalize.css)，最初始的init.css的想法现在看跟normalize等之类的工具想要解决的问题上有部分交集，所以之前的方案是修改normalize和添加部分工具。现在看来直接写一个init.css来补充业务需求就行了。

__！先引用normalize.css，后引用init.css__
__！该版本以不兼容之前的init.css__

## 设计规范，参数设置参考网易云（app），element-ui（pc），京东（app），Material Design，Ant Design

## 工具命名参考Bootstrap

## 部分初始化和个人的使用习惯有关
```
img{
    width:100%
}
```
为了避免图片出现过大溢出容器，或者过小填充不满容器的现象。
img标签外套一个div，来控制img的位置，大小