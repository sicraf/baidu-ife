# baidu-ife

|      任务名称        |    开始时间     |    结束时间   |
|---------------------|:---------------|:--------------|
|  css3-loading       |     08-27      |     08-27     |
|  css3-slider        |     08-28      |     08-29     |
|  css3-hover-effect  |     08-29      |     08-30     |
|  ...    |    ...    |    ...    |


## css3-loading

 主要是对于`rotate`的运用，进行2d转换，多余的部分使用`over-flow: hidden` 隐藏即可。

## css3-slider

 `transform-style: preserve-3d;` 的运用，配合`rotateY` 进行旋转。
 > 参考：[好吧，CSS3 3D transform变换，不过如此！](http://www.zhangxinxu.com/wordpress/2012/09/css3-3d-transform-perspective-animate-transition/)

## css3-hover-effect

 1、文字的流光渐变动画
 `-webkit-background-clip`、`-webkit-text-fill-color`这两个属性，然后`background-image`使用css3渐变，再加上`animation`的动画效果实现。
 >参考[小tip:CSS3下的渐变文字效果实现](http://www.zhangxinxu.com/wordpress/2011/04/%E5%B0%8Ftipcss3%E4%B8%8B%E7%9A%84%E6%B8%90%E5%8F%98%E6%96%87%E5%AD%97%E6%95%88%E6%9E%9C%E5%AE%9E%E7%8E%B0/)

 2、按钮边框的从中间到两边扩展开
 `animation`对线条的宽高进行设置即可。