CSS

1. 说一下CSS的盒模型。

​			在HTML页面中的所有元素都可以看成一个盒子

​			盒子的组成：内容content、内边距padding、边框border、外边距margin

​			盒模型的类型：

​					标准盒模型

​							margin + border + padding +content

​					IE盒模型：

​							margin + content(border + padding)

​			控制盒模型的模式：box-sizing:content-box(默认值，标准盒模型)、border-box(IE盒模型)；

2.CSS选择器的优先级？

​		CSS的特性：继承性、层叠性、优先级

​		优先级：写CSS样式的时候，会给同一个元素添加多个样式，此时谁的权重高就显示谁的样式

​		标签、类/伪类/属性、全局选择器、行内样式、id、!important

​		!important > 行内样式 > id > 类/伪类/属性 > 标签 > 全局选择器

3.隐藏元素的方法有哪些？

​		display:none;

​			元素在页面上消失，不占据空间

​		opacity:0;

​			设置了元素的透明度为0，元素不可见，占据空间位置

​		visibility:hidden;

​			让元素消失，占据空间位置，一种不可见状态

​		position:absolute;

​		clip-path

4.px和rem的区别是什么？

​		px是像素，显示器上给我们呈现的画面的像素，每个像素的大小是一样，绝对单位长度

​		rem，相对单位，对于html根节点的font-size的值，直接给html节点的font-size:62.5%;

​				1rem = 10px;	(16px*62.5%=10px;)

5.重绘重排有什么区别？

6.让一个元素水平垂直居中的方式有哪些？

7.CSS哪些属性的哪些可以继承？哪些不可以继承？

8.有没有用过预处理器？



​		





​		

​		