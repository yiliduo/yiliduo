<template>
	<div class="news">
		<div class="news-banner">
			<a href="#"><img src="../image/huodongbanner.jpg" alt=""></a>
		</div>
		<div class="news-conter">
			<h2 class="title">最新活动</h2>
			<p class="titld">Designers</p>
			<ul class="news-c3">
				<li class="news-li">
					<ul class="nav">
						<li class="lis">
							<div class="desi-li">
								<span class="spa1">6-18</span>
								<span class="spa2">2018</span>
								<h4 class="p1">Her Style 2017/18春夏米兰婚纱礼服流行发布</h4>
								<span class="spa3">Rick Owens 2011/12秋冬巴黎男装流行发布 纵观这场秀的主题，你可以想尽各种
									荒谬的元素，都不足以来描述这场“怪诞”的晚餐。Thom大叔将他一向怪诞风趣的服装风格
								</span>
							</div>
						</li>
						<li class="lis">
							<div class="desi-li">
								<span class="spa1">6-18</span>
								<span class="spa2">2018</span>
								<h4 class="p1">Her Style 2017/18春夏米兰婚纱礼服流行发布</h4>
								<span class="spa3">Rick Owens 2011/12秋冬巴黎男装流行发布 纵观这场秀的主题，你可以想尽各种
									荒谬的元素，都不足以来描述这场“怪诞”的晚餐。Thom大叔将他一向怪诞风趣的服装风格
								</span>
							</div>
						</li>
						<li class="lis">
							<div class="desi-li">
								<span class="spa1">6-18</span>
								<span class="spa2">2018</span>
								<h4 class="p1">Her Style 2017/18春夏米兰婚纱礼服流行发布</h4>
								<span class="spa3">Rick Owens 2011/12秋冬巴黎男装流行发布 纵观这场秀的主题，你可以想尽各种
									荒谬的元素，都不足以来描述这场“怪诞”的晚餐。Thom大叔将他一向怪诞风趣的服装风格
								</span>
							</div>
						</li>
					</ul>
				</li>
				<li class="news-li">
					<ul class="nav">
						<li class="lis">
							<div class="desi-li">
								<span class="spa1">7-16</span>
								<span class="spa2">2018</span>
								<h4 class="p1">Her Style 2017/18春夏米兰婚纱礼服流行发布</h4>
								<span class="spa3">Rick Owens 2011/12秋冬巴黎男装流行发布 纵观这场秀的主题，你可以想尽各种
									荒谬的元素，都不足以来描述这场“怪诞”的晚餐。Thom大叔将他一向怪诞风趣的服装风格
								</span>
							</div>
						</li>
						<li class="lis">
							<div class="desi-li">
								<span class="spa1">7-16</span>
								<span class="spa2">2018</span>
								<h4 class="p1">Her Style 2017/18春夏米兰婚纱礼服流行发布</h4>
								<span class="spa3">Rick Owens 2011/12秋冬巴黎男装流行发布 纵观这场秀的主题，你可以想尽各种
									荒谬的元素，都不足以来描述这场“怪诞”的晚餐。Thom大叔将他一向怪诞风趣的服装风格
								</span>
							</div>
						</li>
						<li class="lis">
							<div class="desi-li">
								<span class="spa1">7-16</span>
								<span class="spa2">2018</span>
								<h4 class="p1">Her Style 2017/18春夏米兰婚纱礼服流行发布</h4>
								<span class="spa3">Rick Owens 2011/12秋冬巴黎男装流行发布 纵观这场秀的主题，你可以想尽各种
									荒谬的元素，都不足以来描述这场“怪诞”的晚餐。Thom大叔将他一向怪诞风趣的服装风格
								</span>
							</div>
						</li>
						
					</ul>
				</li>
				
			</ul>
			<span class="btn1">1</span>
			<span class="btn2">2</span>
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
	export default{
		name: 'news',
		mounted(){
			var btn1 = document.querySelector(".btn1");
			var btn2 = document.querySelector(".btn2");
			var news = document.querySelector(".news-conter");
			var ul =  document.querySelector(".news-c3")
			var w = news.offsetWidth;
		
			btn1.onclick = function(){
				ul.style.transform = "translateX(0)";
			}
			btn2.onclick = function(){
			
				ul.style.transform = "translateX(-50%)";
			}
		}
	}
</script>

<style lang="scss" scoped>
	@media screen and (min-width: 1178px) {
		.news {
			width: 100%;

			.news-banner {
				width: 100%;
				height: 270px;

				a {
					display: block;
					width: 100%;
					height: 100%;

					img {
						width: 100%;
						height: 100%;
					}
				}
			}

			.news-conter {
				width: 100%;
				height: 870px;
				margin: 50px auto;
				position: relative;
				overflow: hidden;

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

				.news-c3 {
					width: 200%;
					height: 700px;
					position: absolute;
					transition: all .5s ease;
					.news-li {
						width: 50%;
						float: left;
						height: 100%;
						.nav {
							width: 100%;
							height: 100%;
							margin-top: 50px;

							.lis {
								width: 100%;
								height: 30%;
								border-top: 1px solid #dbdbdb;
								float: left;
								border-bottom: 1px solid #dbdbdb;

								.desi-li {
									width: 70%;
									margin: 0 auto;
									height: 100%;

									.spa1 {
										font-size: 60px;
										display: block;
										width: 150px;
										height: 60px;
										padding-top: 4%;
										margin-left: 23%;
										float: left;
										color: #929292;
									}

									.spa2 {
										float: left;
										display: block;
										width: 30px;
										height: 30px;
										padding-top: 12%;
										margin-left: -6%;
										color: #929292;
									}

									.p1 {
										padding-top: 4.8%;
										float: left;
										margin-left: 3%;
									}

									.spa3 {
										float: left;
										display: block;
										width: 500px;
										margin-left: 3%;
										height: 43px;
										color: #929292;
										padding-top: 2.5%;
										font-size: 15px;
										overflow: hidden;
										text-overflow: ellipsis;
										-webkit-line-clamp: 2;
										display: -webkit-box;
										-webkit-box-orient: vertical;
									}
								}

								.desi-li:hover {
									animation: all 1s ease;
									color: white;

									span {
										color: white;
									}
								}

								&:hover {
									background-color: #444444;
								}
							}
						}
					}
					
				}
				.btn1{
					display: block;
					width: 35px;
					height: 30px;
					line-height: 30px;
					border: 1px solid #dbdbdb;
					position: absolute;
					left: 46%;
					top: 90%;
				
				}
				.btn2{
					display: block;
					width: 35px;
					height: 30px;
					line-height: 30px;
					border: 1px solid #dbdbdb;
					position: absolute;
					left: 50%;
					top: 90%;
				}
			}
			.footer{
				width: 100%;
				height: 100px;
				background-color: #4d4d4d;
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
							width: 45%;
							margin-top: 15px;
							color: white;
							font-size: 15px;
						}
						ul{
							width: 50%;
							position: absolute;
							right: 1%;
							top: 40%;
							li{
								width: 28%;
								height: 100%;
								float: left;
								a{
									font-size: 15px;
									display: block;
									color: white;
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
	}
	@media screen and (max-width: 768px) {
		
		.news {
			width: 100%;
		
			.news-banner {
				width: 100%;
				height: 270px;
		
				a {
					display: block;
					width: 100%;
					height: 100%;
		
					img {
						width: 100%;
						height: 100%;
					}
				}
			}
		
			.news-conter {
				width: 100%;
				height: 870px;
				margin: 50px auto;
				position: relative;
				overflow: hidden;
		
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
		
				.news-c3 {
					width: 200%;
					height: 700px;
					position: absolute;
					transition: all .4s ease;
					.news-li {
						width: 50%;
						float: left;
						height: 100%;
						
						
						.nav {
							width: 100%;
							height: 100%;
							margin-top: 50px;
		
							.lis {
								width: 100%;
								height: 30%;
								border-top: 1px solid #dbdbdb;
								float: left;
								border-bottom: 1px solid #dbdbdb;
		
								.desi-li {
									width: 70%;
									margin: 0 auto;
									height: 100%;
		
									.spa1 {
										font-size: 40px;
										display: block;
										width: 150px;
										height: 60px;
										padding-top: 4%;
										margin-left: 25%;
										float: left;
										color: #929292;
									}
		
									.spa2 {
										float: left;
										display: block;
										width: 30px;
										height: 30px;
										padding-top: 13%;
										margin-left: -15%;
										color: #929292;
									}
		
									.p1 {
										padding-top: 1.5%;
										float: left;
										margin-left: 3%;
									}
		
									.spa3 {
										float: left;
										display: block;
										width: 500px;
										margin-left: 3%;
										height: 43px;
										color: #929292;
										padding-top: 2%;
										font-size: 15px;
										overflow: hidden;
										text-overflow: ellipsis;
										-webkit-line-clamp: 2;
										display: -webkit-box;
										-webkit-box-orient: vertical;
									}
								}
		
								.desi-li:hover {
									animation: all 1s ease;
									color: white;
		
									span {
										color: white;
									}
								}
		
								&:hover {
									background-color: #444444;
								}
							}
						}
					}
					
				}
				.btn1{
					display: block;
					width: 35px;
					height: 30px;
					line-height: 30px;
					border: 1px solid #dbdbdb;
					position: absolute;
					left: 46%;
					top: 90%;
					
				}
				.btn2{
					display: block;
					width: 35px;
					height: 30px;
					line-height: 30px;
					border: 1px solid #dbdbdb;
					position: absolute;
					left: 55%;
					top: 90%;
				}
			}
			.footer{
				width: 100%;
				height: 250px;
				background-color: black;
				color: white;
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
								color: white;
								a{
									display: block;
									color: white;
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
	}

	@keyframes all {
		0% {
			transform: translateX(0);
		}

		100% {
			transform: translateX(-45px);
		}
	}
</style>
