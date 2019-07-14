<template>
	<div class="home">
		<div class="banner">
			<ul class="ul">
				<li class="li"><img src="../../public/image/banner1.jpg" alt=""></li>
				<li class="li"><img src="../../public/image/banner2.jpg" alt=""></li>
				<li class="li"><img src="../../public/image/banner1.jpg" alt=""></li>

			</ul>
			<a href="javascript:;" data-left="true" class="arr arr-l">&lt;</a>
			<a href="javascript:;" data-left="false" class="arr arr-r">&gt;</a>
			<ol class="ol">
				<li class="act"><a href="#"></a></li>
				<li><a href="#"></a></li>
			</ol>
		</div>
		<div class="main">
			<div class="main-conter">
				<div class="dress">
					<h2 class="title">婚纱礼服</h2>
					<p class="titld">Wedding Dress</p>
					<div class="dress-new">
						<ul>
							<li class="orp" @click="dress1(1)" >新品/NEW
								<span class="spat dac"></span>
							</li>
							<li class="orp" @click="dress2(2)" >2018春夏
								<span class="spat"></span>
							</li>
							<li class="orp" @click="dress3(3)" >2018秋冬
								<span class="spat"></span>
							</li>
							<li class="orp" @click="dress4(4)" >专属定制
								<span class="spat"></span>
							</li>
						
						</ul>
						
						<div class="dress-img">
							<ul v-show="images">
								<li v-for="img in imges" :key="img.id">	
									<div class="img-active">	
										<p class="one ">HER STYLE/一字肩拖尾主纱</p>
										<p class="two ">$5389.00</p>
										<p class="three ">白色/M/VK2531</p>
									</div>
									<a href="#">
										<img class="imgs" :src="img.imgs" alt="">
									</a>
									
								</li>
							</ul>
							<ul v-show="!images">
								<li v-for="user in users">
									<img :src="user.imgs" alt="" class="imgs">
								</li>
								</li>
							</ul>
						</div>
						<div class="more"><a href="">MORE</a></div>
					</div>
				</div>
			</div>
		</div>
		<div class="jewellery">
			<div class="jewellery-conter">
				<div class="jewellery-news">
					<h2 class="title">珠宝配饰</h2>
					<p class="titld">Jewellery Show</p>
					<ul class="show">
						<li class="show-li"><img src="../../public/image/zhubao1.jpg">
							<p>
								<span class="show-sp"></span>
								<span class="show-spe">创世之作,经典重现</span>
								<span class="show-spf">维罗妮卡倾情呈现"斑斓之境"</span>
							</p>
						</li>
						<li><img src="../../public/image/zhubao2.jpg">
							<p>
								<span class="show-sp"></span>
								<span class="show-spe">创世之作,经典重现</span>
								<span class="show-spf">维罗妮卡倾情呈现"斑斓之境"</span>
							</p>
						</li>
						<li><img src="../../public/image/zhubao3.jpg">
							<p>
								<span class="show-sp"></span>
								<span class="show-spe">创世之作,经典重现</span>
								<span class="show-spf">维罗妮卡倾情呈现"斑斓之境"</span>
							</p>
						</li>
						<li><img src="../../public/image/zhubao4.jpg">
							<p>
								<span class="show-sp"></span>
								<span class="show-spe">创世之作,经典重现</span>
								<span class="show-spf">维罗妮卡倾情呈现"斑斓之境"</span>
							</p>
						</li>
					</ul>
					<div class="more"><a href="#">MORE</a></div>
				</div>
			</div>
		</div>
		<div class="latest">
			<div class="bg"><img src="../image/huodongda.jpg" alt=""></div>
			<div class="latest-conter">
				<div class="latest-more">
					<h2 class="title">最新活动</h2>
					<p class="titld">Latest Activities</p>
					<ul>
						<li><img src="../image/huodong.jpg" alt="">
								<div class="release">
									<span class="release-data">06-18</span>
									<span class="release-date">2018</span>
									<h4 class="release-new">新品发布会</h4>
									<span class="release-title">伴随着T台两边色彩趋势报告的发布,VERONICA2017婚纱新品发布会</span>
									<span class="release-more">more&ensp;></span>
								</div>
						</li>
						<li><img src="../image/huodong.jpg" alt="">
								<div class="release">
									<span class="release-data">06-18</span>
									<span class="release-date">2018</span>
									<h4 class="release-new">新品发布会</h4>
									<span class="release-title">伴随着T台两边色彩趋势报告的发布,VERONICA2017婚纱新品发布会</span>
									<span class="release-more">more&ensp;></span>
								</div>
						</li>
						<li><img src="../image/huodong.jpg" alt="">
								<div class="release">
									<span class="release-data">06-18</span>
									<span class="release-date">2018</span>
									<h4 class="release-new">新品发布会</h4>
									<span class="release-title">伴随着T台两边色彩趋势报告的发布,VERONICA2017婚纱新品发布会</span>
									<span class="release-more">more&ensp;></span>
								</div>
						</li>
						<li><img src="../image/huodong.jpg" alt="">
								<div class="release">
									<span class="release-data">06-18</span>
									<span class="release-date">2018</span>
									<h4 class="release-new">新品发布会</h4>
									<span class="release-title">伴随着T台两边色彩趋势报告的发布,VERONICA2017婚纱新品发布会</span>
									<span class="release-more">more&ensp;></span>
								</div>
						</li>
					</ul>
					<div class="more a"><a href="#">MORE</a></div>
				</div>
				
			</div>
		</div>
		<div class="designers">
			<div class="designers-conter">
				<div class="designers-pro">
					<h2 class="title a">设计师</h2>
					<p class="titld">Designers</p>
					<ul>
						<li><span><img src="../image/sheji1.jpg" alt=""></span>
								<p class="name">Jason.W</p>
								<p class="position">首席设计师</p>
								<span class="title">法国时装设计师,VERONICA创始人之一,设计总监,2016福布斯最具影响力的设计师...</span>
								<div class="moq">MORE</div>
						</li>
						<li><span><img src="../image/sheji2.jpg" alt=""></span>
								<p class="name">&ensp;颜澈</p>
								<p class="position">资深设计师</p>
								<span class="title">设计界的"设计鬼才"从题材到表现方式都引起了极大的福布斯中国最具潜力...</span>
								<div class="moq">MORE</div>
						</li>
						<li class="a"><span><img src="../image/sheji3.jpg" alt=""></span>
										<p class="name">Katherine.J</p>
										<p class="position">运营总监</p>
										<span class="title">设计界的"设计鬼才"从题材到表现方式都引起了极大的福布斯中国最具潜力...</span>
										<div class="moq">MORE</div>
						</li>
					</ul>
				</div>
			</div>
		</div>
		<div class="footer">
			<div class="footer-conter">
				<div class="footer-title">
					<p>网站备案号 : 豫ICP备110121210号</p>
					<p>增值电信业务经营许可证号 : 豫B2-20100033</p>
					<ul>
						<li><a href="#">@2018VERONICA</a></li>
						<li><a href="#">联系我们</a></li>
						<li><a href="#">加入我们</a></li>
					</ul>
				</div>
			</div>	
		</div>
	</div>

</template>

<script>
	// @ is an alias to /src
	export default {
		name: 'home',
		data() {
			return {
				imges: [{
						id: 1,
						imgs: require('@/image/hun1.jpg')
					},
					{
						id: 2,
						imgs: require('@/image/hun2.jpg')
					},
					{
						id: 3,
						imgs: require('@/image/hun3.jpg')
					},
					{
						id: 4,
						imgs: require('@/image/hun4.jpg')
					}
				],
				users:[
					{
						id: 1,
						imgs: require('@/image/sha1.jpg')
					},
					{
						id: 2,
						imgs: require('@/image/sha2.jpg')
					},
					{
						id: 3,
						imgs: require('@/image/sha3.jpg')
					},
					{
						id: 4,
						imgs: require('@/image/sha4.jpg')
					}
				],
				images : true,
				acti: false,
				imageq: false
			}

		},
		methods: {
				dress1(){
					this.images = true;
					this.acti = true;
				},
				dress2(){
					this.images = false;
					this.acti = true;
				},
				dress3(){
					
				},
				dress4(){
					
				}
				
		},
		mounted() {
			var banner = document.querySelector(".banner");
			var ul = document.querySelector(".ul");
			var lis = document.querySelectorAll(".li");
			var w = lis[0].offsetWidth;
			var n = 0;
			var ol = document.querySelector(".ol");
			var ollis = ol.children;
			var arr = document.querySelectorAll(".arr");
			var left = document.querySelectorAll(".arr")[0];
			var right = document.querySelectorAll(".arr")[1];
			var n = 0;
			var timer;
			left.onclick = function() {
				goNext(left, true);
				dott(n);
			}
			right.onclick = function() {
				goNext(right, false);
				dott(n);
			}
			banner.onmouseenter = function() {
				clearInterval(timer);
			}
			banner.onmouseleave = function() {
				autoPlay();
				dott(n);
			}
			autoPlay();

			function autoPlay() {
				timer = setInterval(function() {
					goNext(right, false);

				}, 4000)

			}

			function dott(data) {
				var act = document.querySelector('.act');
				act.className = "";
				if (n === 2) {
					data = 0;
				}
				ollis[data].className = "act";
			}

			for (var i = 0; i < ollis.length; i++) {
				ollis[i].onclick = function(s) {
					return function() {
						n = s;
						var target = -n * w;
						dott(n);
						move(ul, target);
					}
				}(i)
			}

			function goNext(el, reg) {
				if (el.dataset.left == 'true') {
					n--;
					if (n === -1) {
						ul.style.left = -1 * w * (lis.length - 1);
						n = lis.length - 2;
					}
				} else {
					n++;
					if (n === 2) {
						ul.style.left = -1 * w * lis.length;
						n = 0;
					}
				}
				var target = -n * w;
				move(ul, target);
			}

			function move(el, target) {
				clearInterval(el.timer);
				el.timer = setInterval(function() {
					var start = el.offsetLeft;
					var step = (target - start) / 10;
					if (Math.abs(step) < 1) {
						step = step > 0 ? 1 : -1;
					}
					if (start == target) {
						clearInterval(el.timer);
						return;
					}
					start += step;
					el.style.left = start + 'px';

				}, 17)
			}
			var orp = document.querySelectorAll(".orp");
			var spat = document.querySelectorAll(".spat");
// 			for(var  i= 0; i< orp.length ; i++){
// 				orp[i].onclick = function(){
// 					var dac = document.querySelector(".dac");
// 					console.log(dac);
// 					dac.classList = "spat"
// 					for(var j = 0; j<spat.length; j++){
// 						
// 						if(orp[i] == spat[j]){
// 							 this.spat[j].className = "spat dac";
// 						}
// 					}
// 				}
// 				
// 			}
			
		},
		components: {}
		

	}
</script>
<style lang="scss" scoped>
	@media screen and (min-width: 1178px) {
		.home {
			width: 100%;

			.banner {
				width: 100%;
				height: 720px;
				overflow: hidden;
				position: relative;

				ul {
					width: 300%;
					position: absolute;

					li {
						width: 33.3%;
						height: 100%;
						float: left;

						img {
							width: 100%;
							height: 100%;
						}
					}
				}

				.arr {
					display: block;
					position: absolute;
					left: 1%;
					top: 30%;
					width: 5%;
					height: 15%;
					font-size: 30px;
					line-height: 120px;
					color: #fff;
					text-align: center;
					text-shadow: 0 1px 2px rgba(0, 0, 0, .5);
					background: rgba(0, 0, 0, 0.2);
				}

				.arr-r {
					left: auto;
					right: 1%;
				}

				.arr:hover {
					background-color: rgba(0, 0, 0, 0.6);
				}

				.ol {
					width: 280px;
					height: 30px;
					position: absolute;
					left: 60%;
					top: 65%;

					li {
						display: block;
						width: 19px;
						height: 19px;
						float: left;
						border-radius: 50%;
						margin-left: 10px;

						a {
							display: block;
							width: 15px;
							height: 15px;
							margin-left: 2px;
							margin-top: 2px;
							border-radius: 50%;
							background-color: white;
						}
					}

					li.act {
						background-color: yellow;
					}
				}
			}
		}
		.title {
			width: 100%;
			height: 30px;
			text-align: center
		}
		.titld {
			width: 100%;
			height: 20px;
			text-align: center;
			color: #c1c1c1;
			font-size: 16px;
		}
		.more{
			margin-top: 55px;
			width: 100%;
			height: 45px;
			a{
				display: block;
				width: 14%;
				height: 100%;
				line-height: 45px;
				text-align: center;
				margin: 0 auto;
				color: black;
				font-size: 22px;
				border: 2px solid #f5f5f5;
			}
		}
		.main {
			width: 100%;
			
			.main-conter {
				width: 80%;
				margin: 0 auto;
				.dress {
					width: 100%;
					height: 635px;
					.dress-new {
						width: 100%;
						height: 45px;
						margin-top: 50px;

						ul {
							width: 50%;
							height: 100%;
							margin: 0 auto;
							position: relative;
							li {
								width: 25%;
								height: 100%;
								float: left;
								line-height: 45px;
								color: #4d4d4d;
								font-weight: bold;
								cursor:pointer;
								&:hover{
									color: orange;
								}
								.spat{
									display: none;
									width: 15%;
									height: 2px;
									background-color: orange;
									position: absolute;
									margin-left: 5%;
									top: 80%;
									
								}
								.spat.dac{
									display: block;
								}
							}
							
							
							
						}
						.dress-img{
							width: 100%;
							height: 360px;
							ul{
								margin-top: 30px;
								width: 100%;
								li{
									width: 22.5%;
									height: 100%;
									float: left;
									margin-right: 2.5%;
									
									position: relative;
									.img-active{
										
										width: 100%;
										background-color: #c1c1c1;
										opacity: 0.8;
										float: left;
										height: 360px;
										position: relative;
										display: none;
										z-index: 99;
										margin-right: 2.5%;
										.one{
											position: absolute;
											left: 10%;
											top: 30%;
											color: white;
											opacity: 1;
										}
										.two{
											position: absolute;
											left: 38%;
											top: 43%;
											color: white;
											opacity: 1;
											font-size: 15px;
										}
										.three{
											position: absolute;
											left: 28%;
											top: 53%;
											color: white;
											opacity: 1;
										}
									}
									a{
										display: block;
										position: absolute;
										top: 0;
										.imgs{
											width: 100%;
											height: 100%;
										}
										
									}
									&:hover .img-active{
											display: block;
										}
								}
							}
						}
					}
				}
			}
		}
		.jewellery{
			width: 100%;
			background-color: #f9f9f9;
			margin-top: 60px;
			height: 515px;
			.jewellery-conter{
				width: 80%;
				margin: 0 auto;
				.jewellery-news{
					width: 100%;
					height: 45px;
					padding-top: 50px;
					.show{
						width: 100%;
						height: 180px;
						margin-top: 55px;
						li{
							width: 22.5%;
							height: 100%;
							float: left;
							margin-right: 2.5%;
							position: relative;
							img{
								width: 100%;
								height: 100%;
							}
							p{
								display: none;
								.show-sp{
									position: absolute;
									left: 0;
									top: 120px;
									width: 270px;
									height: 60px;
									background-color: #9b9b9b;
									opacity: 0.6;
								}
								.show-spe{
									opacity: 1;
									position: absolute;
									left: 30px;
									top: 128px;
									color: white;
									z-index: 100;
								}
								.show-spf{
									opacity: 0.8;
									position: absolute;
									left: 20px;
									top: 150px;
									color: white;
									font-size: 15px;
								}
							}
							&:hover p{
								display: block;
							}
						}
					}
				}
			}
		}
		.latest{
			width: 100%;
			margin-top: 70px;
			position: relative;
			height: 780px;
			.bg{
				width: 100%;
				height: 345px;
				position: absolute;
				left: 0;
				top: 150px;
				img{
					width: 100%;
					height: 100%;
				}
			}
			.latest-conter{
				width: 80%;
				margin: 0 auto;
				.latest-more{
					width: 100%;
					padding-top: 35px;
					position: relative;
					ul{
						width: 100%;
						height: 334px;
						position: absolute;
						left: 0;
						top: 300px;
						li{
							width: 24%;
							height: 100%;
							margin-right: 1%;
							float: left;
							position: relative;
							img{
								width: 100%;
								height: 100%;
							}
							.release{
								display: none;
								width: 100%;
								height: 100%;
								background-color: white;
								position: absolute;
								left: 0;
								top: 0;
								.release-data{
									font-size: 25px;
									position: absolute;
									left: 16%;
									top: 16%;
									color: #8b8b8b;
								}
								.release-date{
									position: absolute;
									left: 52%;
									top: 17.5%;
									color: #8b8b8b;
								}
								.release-new{
									position: absolute;
									left: 35%;
									top: 35%;
								}
								.release-title{
									width: 80%;
									height: 40px;
									font-size: 15px;
									position: absolute;
									left: 10%;
									top: 54%;
									overflow: hidden;
									text-overflow:ellipsis;
									-webkit-line-clamp: 2;
									display: -webkit-box;
									-webkit-box-orient: vertical;
								}
								.release-more{
									position: absolute;
									left: 12%;
									top: 79%;
								}
							}
							&:hover .release{
								display: block;
							}
						}
					}
					.more.a{
						position: absolute;
						top: 640px;
					}
				}
			}
		}
		.designers{
			width: 100%;
			background-color: #4d4d4d;
			margin-top: 45px;
			height: 660px;
			.designers-conter{
				width: 80%;
				margin: 0 auto;
				.designers-pro{
					width: 100%;
					padding-top: 90px;
					.title.a{
						color: white;
						font: {
							text-color: white;
						}
					}
					ul{
						width: 100%;
						height: 400px;
						margin-top: 50px;
						li{
							width: 33%;
							height: 100%;
							float: left;
							margin-left: 0.3%;
							span{
								display: block;
								width: 180px;
								height: 180px;
								margin: 0 auto;
								img{
									width: 100%;
									height: 100%;
									border-radius: 50%;
								}
							}
							.name{
								color: white;
								margin-top: 18px;
								font-size: 25px;
							}
							.position{
								color: white;
								margin-top: 10px;
								font-size: 13px;
							}
							.title{
								display: block;
								width: 75%;
								color: white;
								margin-top: 15px;
								font-size: 13px;
								height: 22%;
							}
							.moq{
								width: 74%;
								height: 30px;
								font-size: 18px;
								color: white;
								margin: 0 auto;
								position: relative;
								:hover{
									color: red;
								}
							}
							.moq::after{
								width: 64%;
								height: 2px;
								background-color: white;
								content: "";
								position: absolute;
								left: 18%;
								top: 87%;
							}
						}
					}
				}
			}
		}
		.footer{
			width: 100%;
			height: 100px;
			.footer-conter{
				width: 80%;
				height: 100%;
				margin: 0 auto;
				.footer-title{
					width: 100%;
					height: 100%;
					padding-top: 25px;
					position: relative;
					p{
						width: 45%;
						margin-top: 15px;
					}
					ul{
						width: 50%;
						position: absolute;
						right: 1%;
						top: 48%;
						li{
							width: 28%;
							height: 100%;
							float: left;
							a{
								display: block;
								color: black;
								&:hover{
									color: red;
								}
							}
						
						}
					}
				}
			}
		}
	}
	
// 	@keyframes all{
// 		
// 		100%{
// 			transform: translateY(0);
// 		}
// 	}
	
	@media screen and (max-width: 768px){
			*{
				font-size: 14px;
			}
			.home {
				width: 100%;
			
				.banner {
					width: 100%;
					height: 240px;
					overflow: hidden;
					position: relative;
					ul {
						width: 300%;
						height: 100%;
						position: absolute;
			
						li {
							width: 33.3%;
							height: 100%;
							float: left;
			
							img {
								width: 100%;
								height: 100%;
							}
						}
					}
			
					.arr {
						display: block;
						position: absolute;
						left: 0;
						top: 0;
						width: 10%;
						height: 100%;
						line-height: 150px;
						color: #fff;
						text-align: center;
						text-shadow: 0 1px 2px rgba(0, 0, 0, .5);
						background: rgba(0, 0, 0, 0.2);
					}
			
					.arr-r {
						left: auto;
						right: 0;
					}
			
					.arr:hover {
						background-color: rgba(0, 0, 0, 0.6);
					}
			
					.ol {
						width: 280px;
						height: 30px;
						position: absolute;
						left: 55%;
						top: 55%;
			
						li {
							display: block;
							width: 19px;
							height: 19px;
							float: left;
							border-radius: 50%;
							margin-left: 10px;
			
							a {
								display: block;
								width: 15px;
								height: 15px;
								margin-left: 2px;
								margin-top: 2px;
								border-radius: 50%;
								background-color: white;
							}
						}
			
						li.act {
							background-color: yellow;
						}
					}
				}
			}
			.title {
				width: 100%;
				height: 30px;
				text-align: center;
				font-size: 16px;
			}
			.titld {
				width: 100%;
				height: 20px;
				text-align: center;
				color: #c1c1c1;
				font-size: 16px;
			}
			.more{
				width: 100%;
				height: 45px;
				margin-top: 400px;
				a{
					display: block;
					width: 80px;
					height: 100%;
					line-height: 45px;
					text-align: center;
					margin:  0 auto;
					color: black;
					font-size: 22px;
					border: 2px solid #f5f5f5;
				}
			}
			.main {
				width: 100%;
				height: 950px;
				margin-top: 25px;
				.main-conter {
					width: 80%;
					margin: 0 auto;
					.dress {
						width: 100%;
						height: 635px;
						.dress-new {
							width: 100%;
							height: 45px;
							margin-top: 50px;
			
							ul {
								width: 50%;
								height: 100%;
								margin: 0 auto;
								position: relative;
								li {
									width: 25%;
									height: 100%;
									float: left;
									line-height: 45px;
									color: #4d4d4d;
									font-weight: bold;
									cursor:pointer;
									.img-active{
										display: none;
										
										.one{
											position: absolute;
											left: 10%;
											top: 30%;
											color: white;
											opacity: 1;
										}
										.two{
											position: absolute;
											left: 38%;
											top: 43%;
											color: white;
											opacity: 1;
											font-size: 15px;
										}
										.three{
											position: absolute;
											left: 28%;
											top: 53%;
											color: white;
											opacity: 1;
										}
									}
									
								}
								
								
								.active{
									color: red;
								}
							}
							.dress-img{
								width: 100%;
								height: 360px;
								ul{
									margin-top: 30px;
									width: 100%;
									li{
										width: 40%;
										height: 100%;
										margin-top: 2.5%;
										margin-left: 8%;
										background-color: orange;
										.imgs{
											width: 100%;
											height: 100%;
										}
									}
								}
							}
						}
					}
				}
			}
			.jewellery{
				width: 100%;
				background-color: #f9f9f9;
				margin-top: 60px;
				height: 515px;
				.jewellery-conter{
					width: 80%;
					margin: 0 auto;
					.jewellery-news{
						width: 100%;
						height: 45px;
						padding-top: 50px;
						.show{
							width: 100%;
							height: 180px;
							margin-top: 55px;
							li{
								width: 45%;
								height: 100%;
								float: left;
								margin-left: 5%;
								margin-top: 5%;
								position: relative;
								img{
									width: 100%;
									height: 100%;
								}
								
								p{
									display: none;	
								}
							}
						}
					}
				}
			}
			.latest{
				width: 100%;
				margin-top: 70px;
				position: relative;
				height: 700px;
				.bg{
					width: 100%;
					height: 345px;
					position: absolute;
					left: 0;
					top: 150px;
					img{
						width: 100%;
						height: 100%;
					}
				}
				.latest-conter{
					width: 80%;
					margin: 0 auto;
					.latest-more{
						width: 100%;
						padding-top: 35px;
						position: relative;
						ul{
							width: 100%;
							height: 334px;
							position: absolute;
							left: 10%;
						
							li{
								width: 40%;
								height: 70%;
								margin-right: 8%;
								margin-top: 8%;
								float: left;
								position: relative;
								img{
									width: 100%;
									height: 100%;
								}
								.release{
									display: none;
									width: 100%;
									height: 100%;
									background-color: white;
									position: absolute;
									left: 0;
									top: 0;
									.release-data{
										font-size: 25px;
										position: absolute;
										left: 16%;
										top: 16%;
										color: #8b8b8b;
									}
									.release-date{
										position: absolute;
										left: 52%;
										top: 17.5%;
										color: #8b8b8b;
									}
									.release-new{
										position: absolute;
										left: 35%;
										top: 35%;
									}
									.release-title{
										width: 80%;
										height: 40px;
										font-size: 15px;
										position: absolute;
										left: 10%;
										top: 54%;
										overflow: hidden;
										text-overflow:ellipsis;
										-webkit-line-clamp: 2;
										display: -webkit-box;
										-webkit-box-orient: vertical;
									}
									.release-more{
										position: absolute;
										left: 12%;
										top: 79%;
									}
								}
								&:hover .release{
									display: block;
								}
							}
						}
						.more.a{
							position: absolute;
							top: 250px;
						}
					}
				}
			}
			.designers{
				width: 100%;
				background-color: #4d4d4d;
				margin-top: 45px;
				height: 1400px;
				.designers-conter{
					width: 80%;
					margin: 0 auto;
					.designers-pro{
						width: 100%;
						padding-top: 50px;
						.title.a{
							color: white;
							font: {
								text-color: white;
							}
						}
						ul{
							width: 100%;
							height: 400px;
							margin-top: 50px;
							li{
								width: 100%;
								height: 100%;
								float: left;
								margin: 0 auto;
								span{
									display: block;
									width: 180px;
									height: 180px;
									margin: 0 auto;
									img{
										width: 100%;
										height: 100%;
										border-radius: 50%;
									}
								}
								.name{
									color: white;
									margin-top: 18px;
									font-size: 25px;
								}
								.position{
									color: white;
									margin-top: 10px;
									font-size: 13px;
								}
								.title{
									display: block;
									width: 75%;
									color: white;
									margin-top: 15px;
									font-size: 13px;
									height: 22%;
								}
								.moq{
									width: 74%;
									height: 30px;
									font-size: 18px;
									color: white;
									margin: 0 auto;
									position: relative;
									:hover{
										color: red;
									}
								}
								.moq::after{
									width: 64%;
									height: 2px;
									background-color: white;
									content: "";
									position: absolute;
									left: 18%;
									top: 87%;
								}
							}
							
						}
					}
				}
			}
			.footer{
				width: 100%;
				height: 100px;
				.footer-conter{
					width: 80%;
					height: 100%;
					margin: 0 auto;
					.footer-title{
						width: 100%;
						height: 100%;
						padding-top: 15px;
						position: relative;
						p{
							width: 100%;
							margin-top: 15px;
						}
						ul{
							
							width: 50%;
							height: 50px;
							margin: 15px auto;
							li{
								width: 80%;
								height: 100%;
								float: left;
								
								a{
									display: block;
									color: black;
									:hover{
										color: red;
									}
								}
							
							}
						}
					}
				}
			}
	}
</style>
