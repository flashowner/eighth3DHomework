### 告示板
这次的作业是用NGUI实现一个告示板<br>
效果图：<br>
![]()<br>
首先先创建一个UI对象Scroll View，这是一个有滚动条的界面:<br>
![]()<br>
接着给Scroll View下的Viewport下的Content，也就是滚动条的内容区域添加一个<br>
Vertical Layout Group组件用来设置内容的排版，在这里内容区域是从上到下排版的:<br>
![]()<br>
然后在Content下创建你想要数量的Button和Text，每一个Text对应一个Button，<br>
设置Button上text的内容以及Text组件的内容，调整Content的大小确保可以显示所有<br>
的内容，调整好位置后可以通过给画布和Content添加个Image组件来设置背景。<br>
最后是一个挂载到每一个button的C#文件用来控制点击按钮的事件：<br>
![]()<br>
![]()<br>
![]()<br>
