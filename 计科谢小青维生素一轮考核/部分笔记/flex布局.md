flex布局：子元素的float,clear,vertical-align属性将无关。

弹性容器：

6个属性：flex-direction, flex-wrap, flex-flow, justify-content, align-items, align-content

1. flex-direction   指定容器中x项目的排列方向，决定主轴的方向

   ​	可选值：

   ​		row 默认值   主轴为水平方向，起点在左端

   ​		row-reverse   主轴为水平方向，起点在右端

   ​		column   	主轴为垂直方向，起点在上沿

   ​		column-reverse  主轴为垂直方向，起点在下沿

2. flex-wrap    设置弹性元素是否在弹性容器中自动换行

   ​	可选值：

   ​		nowrap	不自动换行（默认值）

   ​		wrap	换行，第一行在上方

   ​		wrap-reverse   换行，第一行在上方

3. flex-flow    wrap 和 direction 的简写属性

4. justify-content      如何分配主轴上的空白空间

   ​	可选值：

   ​		flex-start 	左对齐（默认值）

   ​		flex-end		右对齐

   ​		center			居中

   ​		space-around	两端对齐，显目之间的间隔都相等

   ​		space-between   每个项目两侧的间隔相等。项目之间的间隔比项目与边框的间隔大一倍。		

4. align-items         元素在辅轴上如何对齐

    	可选值：

        		stretch   默认值，将元素的长度设置为相同的值

   ​		flex-start  元素不会拉伸，沿着辅轴起边对齐

   ​		flex-end	沿着辅轴终边对齐

   ​		center		居中对齐

   ​		baseline    基线对齐

   5.align- content       辅轴空白空间的分布 

   ​	flex-start		与交叉轴的起点对齐。
   ​    flex-end		与交叉轴的终点对齐。
   ​    center			与交叉轴的中点对齐。
   ​    space-between		与交叉轴两端对齐，轴线之间的间隔平均分布。
   ​    space-around			每根轴线两侧的间隔都相等。所以，轴线之间的间隔比轴线与边框的间隔大一倍。
   ​    stretch（默认值）：轴线占满整个交叉轴。

   弹性元素的属性：

flex-grow 	指定弹性元素的伸展的系数

flex-shrink  指定弹性元素的收缩的系数

align-self	允许单个项目有与其他项目不一样的对齐方式，用来覆盖当前弹性元素上的align-items，默认值为auto

flex-basis	元素占据主轴空间

flex	可以设置弹性元素所有的三个样式

​	flex	增长	缩减	基础；

​			initial  默认值	"flex: 0  1  auto"

​			auto	"flex: 1 1 auto"

​			none "flex：0 0 auto"    弹性元素没有弹性

order  决定弹性元素的排列顺序。数值越小，排列越靠前，默认值为0.