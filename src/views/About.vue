<template>
	<div class="jewellery">
		<div class="jewellery-banner">
			<a href="#"><img src="../image/jewbanner.jpg" alt=""></a>
		</div>
		<div class="jewellery-conter">
			<h2 class="title">设计师</h2>
			<p class="titld">Designers</p>
			<ul>
				<li class="a"><a><img src="../image/she1.jpg" alt=""></a>
				<p class="p1">吉承/Jenny</p>
				<p class="p2">VERONICA的视觉艺术总监</p>
				<span>吉承，中国时装设计师代表，JICHENG/织货byJicheng品牌创始人、设计总监。2015年福布斯...</span>
				</li>
				<li><a><img src="../image/she2.jpg" alt=""></a>
				<p class="p1">比尔盖</p>
				<p class="p2">服装设计师</p>
				<span>吉承，中国时装设计师代表，JICHENG/织货byJicheng品牌创始人、设计总监。2015年福布斯...</span>
				</li>
				<li><a><img src="../image/she3.jpg" alt=""></a>
				<p class="p1">吉承/Rankin</p>
				<p class="p2">珠宝设计师</p>
				<span>吉承，中国时装设计师代表，JICHENG/织货byJicheng品牌创始人、设计总监。2015年福布斯...</span>
				</li>
			</ul>
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
</script>

<style lang="scss" scoped>
@media screen and (min-width: 1178px) {
	.jewellery{
		width: 100%;
		.jewellery-banner{
			width: 100%;
			height: 270px;
			background-color: black;
			
			a{
				display: block;
				width: 100%;
				height: 100%;
				background-color: black;
				img{
					width: 100%;
					height: 100%;
					background-color: black;
				}
			}
		}
	
		.jewellery-conter{
			width: 80%;
			height: 800px;
			margin: 50px auto;
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
			ul{
				width: 100%;
				height: 700px;
				margin-top: 50px;
				li{
					width: 300px;
					float: left;
					margin-left: 7%;
					a{
						display: block;
						width: 100%;
						height: 450px;
						img{
							width: 100%;
							height: 100%;
						}
					}
					.p1{
						font-size: 23px;
						margin-top: 35px;
					}
					.p2{
						margin-top: 14px;
					}
					span{
						margin-top: 25px;
						display: block;
					}
				}
				li.a{
					margin-left: 6%;
				}
				
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
	.jewellery{
		width: 100%;
		.jewellery-banner{
			width: 100%;
			height:110px;
			
			a{
				display: block;
				width: 100%;
				height: 100px;
			
				img{
					width: 100%;
					height: 100%;
					background-color: black;
				}
			}
		}
	
		.jewellery-conter{
			width: 80%;
			height: 2050px;
			margin: 50px auto;
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
			ul{
				width: 100%;
				height: 100%;
				margin-top: 50px;
				li{
					width: 300px;
					height: 670px;
					margin: 0 auto;
					// margin-left: 7%;
					a{
						display: block;
						width: 100%;
						height: 450px;
						img{
							width: 100%;
							height: 100%;
						}
					}
					.p1{
						font-size: 20px;
						margin-top: 25px;
					}
					.p2{
						margin-top: 14px;
					}
					span{
						margin-top: 25px;
						display: block;
					}
				}
				
				
			}
		}
		.footer{
			width: 100%;
			height: 250px;
			background-color: black;
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
						color: white;
					}
					ul{
						
						width: 70%;
						height: 50px;
						margin: 20px auto;
						li{
							width: 80%;
							height: 100%;
							float: left;
							
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
</style>
