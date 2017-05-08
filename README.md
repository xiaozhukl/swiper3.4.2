# swiper3.4.2
swiper自己打包的常用的通栏轮播


1、引入css文件和js文件
<link rel="stylesheet" href="css/swiper.css">
<script src="js/swiper.js">

2、构建HTML结构
<div class="swiper-container">
	<div class="swiper-wrapper">
		<div class="swiper-slide"></div>
		<div class="swiper-slide"></div>
		<div class="swiper-slide"></div>
	</div>
	<div class="swiper-pagination"></div>
	<div class="swiper-button-next"></div>
	<div class="swiper-button-prev"></div>
</div>
需要注意的是，图片使用背景图像的方式引用
<div class="swiper-slide" style="background:url(images/1.jpg) no-repeat center center"></div>

3、定义样式表文件，控制最外层的.swiper-container的尺寸
如果是满屏的，只需要给一个高度既可
.swiper-container{
	height:300px;
}
如果不是通栏满屏的，需要给最外层的元素一个宽度
.swiper-container{
	width:1200px;
	height:400px;
}

================================================
swiper-container的初始化我放进了swiper.js文件的最后面，主要是为了简化

