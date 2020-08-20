bootstrapde的项目结构比较简单，如果只是使用，就是用dist版本就可以，他是bootstrap编译好的文件，直接引用使用。其中bootstrap.css和bootstrap.js是未经压缩的源码，带有min字段的是压缩后的代码，体积小很多，引用更为方便。

bootstrap依赖jquery，所以再使用bootstrap.js前，必须先要引入jquery.js，以确保bootstrap.js能正常运行。

在bootstrap中，最重要的就是meta标签中的viewport属性，这个属性可以控制网页在不同终端有不同效果。

viewport有一些重要的属性：
width:设置viewport的宽度，为一个正整数或“width-device”（表示整个屏幕的宽度）。
initial-scale:设置页面的初始值，为一个浮点数。
minimum-scale:允许用户设置的最小缩放值，为一个浮点数。
maximum-scale:允许用户设置的最大缩放值，为一个浮点数。
height:设置viewport的高度。
user-scalable:是否允许用户进行缩放值为no或yes

响应式布局需要用到css的媒体查询，媒体查询可以让我们根据设备的特性，为其设定css样式，媒体查询可以检测的特性有width，height，color等，媒体查询可以在不改变页面内容的前提下，为一些特定的输出设备定制显示效果。


