# 第一步，引入JS，CSS文件 #
```
<link rel="stylesheet" type="text/css" href="css/pic360.css"/>
<script type="text/javascript" language="JavaScript" src="js/jquery-1.4.4.js"></script>
<script type="text/javascript" language="JavaScript" src="js/pic360-1.0.0.js"></script>
```
# 第二步，必须的HTML代码结构 #
class="PIC360"必须写上，JS插件根据这个来初始化
```
<div class="PIC360">
	<ul>
		<li><img width=400 height=255 src="images/image1_1.jpg" /></li>
		<li><img width=400 height=255 src="images/image1_2.jpg" /></li>
		<li><img width=400 height=255 src="images/image1_3.jpg" /></li>
		<li><img width=400 height=255 src="images/image1_4.jpg" /></li>
		<li><img width=400 height=255 src="images/image1_5.jpg" /></li>
		<li><img width=400 height=255 src="images/image1_6.jpg" /></li>
		<li><img width=400 height=255 src="images/image1_7.jpg" /></li>
		<li><img width=400 height=255 src="images/image1_8.jpg" /></li>
		<li><img width=400 height=255 src="images/image1_9.jpg" /></li>
		<li><img width=400 height=255 src="images/image1_10.jpg" /></li>
		<li><img width=400 height=255 src="images/image1_11.jpg" /></li>
		<li><img width=400 height=255 src="images/image1_12.jpg" /></li>
		<li><img width=400 height=255 src="images/image1_13.jpg" /></li>
		<li><img width=400 height=255 src="images/image1_14.jpg" /></li>
		<li><img width=400 height=255 src="images/image1_15.jpg" /></li>
		<li><img width=400 height=255 src="images/image1_16.jpg" /></li>
		<li><img width=400 height=255 src="images/image1_17.jpg" /></li>
		<li><img width=400 height=255 src="images/image1_18.jpg" /></li>
	</ul>
</div>
```
其中的图片是按角度排列好的，建议不少于8张，图片越多，转动越平滑。<br />
<a href='http://picture-360-rotation.googlecode.com/hg/1.0.0/index.html'>点击看示例</a><br />
相当简单吧