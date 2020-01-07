# CS571_HW3
solution video:
https://www.youtube.com/watch?v=uJpMdifQEiQ&feature=youtu.be

image links:
http://csci571.com/hw/hw3/images/face.jpg

http://csci571.com/hw/hw3/images/coffee1.jpg

http://csci571.com/hw/hw3/images/coffee2.jpg

ref:
https://codepen.io/karldanninger/pen/NwzMzN
https://juejin.im/entry/5975ede7f265da6c322e213f
Scott Kellum和Keith Clark在使用CSS 3D实现视差滚动方面卓有成就，他们使用的方法如下：

将要滚动的容器元素属性设置为overflow-y: scroll（和overflow-x:hidden）。
对同一个元素应用perspective值，并将perspective-origin设置为top left或0 0。
对容器元素的子元素应用Z轴变形，通过缩放子元素实现视差效果，注意不要影响到它们在屏幕上的大小。
