# css3_animation

css3动画练习，纵向轮播，轮播到每一项加载动画。
# 遇到的问题

css3 aniamtion属性 在chrome上会有BUG 也就是动画完成时会抖动或闪动。
# 解决办法

-webkit-backface-visibility: hidden;（设置进行转换的元素的背面在面对用户时是否可见：隐藏）
-webkit-transform-style: preserve-3d; （设置内嵌的元素在 3D 空间如何呈现：保留 3D ）

加上以上两个属性，将会很大程度的解决抖动闪动效果，但是动画的最后 还是会有轻微抖动，不过不仔细看 很难看出来 :)

# 总结
大致理解了CSS3动画制作流程，与之前的想法出入很大
