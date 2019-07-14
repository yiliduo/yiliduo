<template>
	<div class="about">
		<div class="about-conter">
			<div class="about-her">
				<div class="about-her-top">
					<a href="#">
						<img src="../image/zhuzhu.jpg" alt="">
					</a>
					<div class="title">
						<p class="h2">一字肩拖尾主纱</p>
						<p class="title-p1">HER STYLE</p>
						<P class="title-p2">$5389.00</P>
						<P class="title-p3">白色/M/VK2531</P>
						<span class="title-spa">浅色象牙白缎面婚纱，手工镶嵌金色和银色Chantilly蕾丝, 背面饰有缕空的华丽</span>
						<a href="#">立即预约</a>
					</div>
				</div>
				<div class="about-her-bottom">
					<a href="#">
						<img src="../image/zhuzhuxia.jpg" alt="">
					</a>
					<div class="title">
						<span class="title-spa">这薄纱在皇家婚纱由著名思想Martina Liana的首席创意官,Martina Harris, 有一个身影
							奉承捻胸衣和传统教堂的火车。大胆的钻石水晶点缀的领口，上背部和腰部。背部拉链。选择从石头和象牙薄纱在香槟皇家纱
							,象牙薄纱在皇家是白色婚纱,或皇家白色的薄纱
						</span>
						<p class="p1">尺码: s/m</p>
						<p class="p2">颜色: 白色</p>
					</div>
				</div>
			</div>
		</div>
		<div class="about-banner">
			<ul class="acc">
				<li>新品/NEW</li>
				<li class="c">往季</li>
			</ul>
			<div class="about-img">
				<ul class="nav">
					<li class="a"><img src="../image/zhua.jpg" alt=""></li>
					<li class="rong"><img src="../image/zhub.jpg" alt=""></li>
					<li class="rong"><img src="../image/zhuc.jpg" alt=""></li>
					<li class="rong b"><img src="../image/zhud.jpg" alt=""></li>
					<li class="b"><img src="../image/zhue.jpg" alt=""></li>
					<li class="b"><img src="../image/zhub.jpg" alt=""></li>
				
				</ul>
				
			</div>
			<a href="javascript:;" data-left="true" class="arr le">&lt;</a>
			<a href="javascript:;" data-left="false" class="arr rig">&gt;</a>
			<div class="more"><a href="#">MORE</a></div>
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
<style lang="scss" scoped>
	@media screen and (min-width: 1178px) {
		.about {
			width: 100%;
	
			.about-conter {
				width: 80%;
				margin: 0 auto;
	
				.about-her {
					width: 100%;
					height: 1405px;
					margin-top: 100px;
	
					.about-her-top {
						width: 100%;
						height: 44%;
						position: relative;
	
						a {
							display: block;
							width: 709px;
							height: 437px;
	
							img {
								width: 100%;
								height: 100%;
							}
						}
	
						.title {
							width: 415px;
							height: 300px;
							position: absolute;
							right: 6%;
							top: 3%;
	
							.h2 {
								width: 80%;
								font-size: 25px;
							}
	
							.title-p1 {
								width: 100%;
								text-align: center;
								margin-top: 8px;
							}
	
							.title-p2 {
	
								font-size: 15px;
								margin-top: 20px;
								color: #cacaca;
							}
	
							.title-p3 {
								color: #cacaca;
								width: 90%;
								margin-top: 15px;
								text-align: center;
							}
	
							.title-spa {
								display: block;
								margin-top: 10px;
								color: #cacaca;
								width: 85%;
								padding-left: 16%;
	
							}
	
							a {
								display: block;
								width: 145px;
								height: 46px;
								border: 2px solid #f5f5f5;
								text-align: center;
								position: absolute;
								left: 35%;
								top: 85%;
								line-height: 46px;
								color: black;
	
								:hover {
									color: red;
								}
							}
						}
	
						.title::after {
							width: 2px;
							height: 50px;
							background-color: black;
							content: "";
							position: absolute;
							left: 16%;
							top: -1%;
						}
					}
	
					.about-her-bottom {
						width: 100%;
						height: 56%;
						position: relative;
	
						a {
							display: block;
							width: 709px;
							height: 474px;
	
							img {
								width: 100%;
								height: 100%;
							}
						}
	
						.title {
							width: 710px;
							height: 300px;
							margin-top: 5%;
							color: #747474;
	
							span {
								width: 100%;
								height: 80px;
							}
	
							.p1 {
								width: 15%;
								margin-top: 8%;
							}
	
							.p2 {
								width: 15%;
								margin-top: 1%;
							}
						}
					}
	
				}
			}
	
			.about-banner {
				width: 100%;
				height: 475px;
				background-color: #ddd;
				position: relative;
				.acc{
					width: 80%;
					height: 50px;
					position: absolute;
					top: 20%;
					left: 12%;
					li{
						width: 85px;
						margin-right: 5%;
						height: 35px;
						line-height: 35px;
						float: left;
						background-color: #f7f5f5;
						font-size: 15px;
						color: #929292;
					}
					li.a{
						width: 70px;
					}
				}
				.about-img {
					overflow: hidden;
					width: 80%;
					height: 140px;
					margin: 0 auto;
					position:relative;
					top: 35%;
					ul {
						width: 130%;
						height: 100%;
						position: absolute;
						li {
							width: 210px;
							height: 100%;
							float: left;
							margin-left: 30px;
							img {
								width: 100%;
								height: 100%;
							}
						}
					}	
				}
				.arr{
					width: 5%;
					height: 55px;
					display: block;
					background-color: orange;
					line-height: 55px;
					font-size: 20px;
					position: absolute;
					left: 5%;
					top: 40%;
					z-index: 99;
					}
					.arr.rig {
						left: auto;
						right: 3%;
					}
					.more{
						width: 150px;
						height: 45px;
						position: absolute;
						left: 45%;
						top: 83%;
						border: 2px solid #bbbaba;
						line-height: 45px;
						a{
							color: #bbbaba;
							display: block;
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

	@media screen and (max-width:768px) {
		
		.about {
			width: 100%;
			
			.about-conter {
				width: 80%;
				margin: 0 auto;
		
				.about-her {
					width: 100%;
					height: 1300px;
					margin-top: 30px;
		
					.about-her-top {
						width: 100%;
						height: 43%;
						position: relative;
		
						a {
							display: block;
							width: 100%;
							height: 500px;
		
							img {
								width: 100%;
								height: 100%;
							}
						}
		
						.title {
							width: 100%;
							height: 300px;
							position: absolute;
							
							top: 20%;
							color: white;
							.h2 {
								width: 80%;
								font-size: 22px;
							}
		
							.title-p1 {
								width: 100%;
								text-align: center;
								margin-top: 8px;
							}
		
							.title-p2 {
		
								font-size: 15px;
								margin-top: 20px;
							
							}
		
							.title-p3 {
								
								width: 90%;
								margin-top: 15px;
								text-align: center;
							}
		
							.title-spa {
								display: block;
								margin-top: 10px;
								
								width: 85%;
								padding-left: 10%;
		
							}
		
							a {
								display: block;
								width: 145px;
								height: 46px;
								border: 2px solid #333;
								text-align: center;
								position: absolute;
								left: 35%;
								top: 85%;
								line-height: 46px;
								color: black;
		
								:hover {
									color: red;
								}
							}
						}
		
						.title::after {
							width: 2px;
							height: 50px;
							background-color: black;
							content: "";
							position: absolute;
							left: 10%;
							top: -1%;
						}
					}
		
					.about-her-bottom {
						width: 100%;
						height: 55%;
						position: relative;
		
						a {
							display: block;
							width: 100%;
							height: 500px;
		
							img {
								width: 100%;
								height: 100%;
							}
						}
		
						.title {
							width: 100%;
							height: 300px;
							margin-top: 5%;
							color: #747474;
		
							span {
								width: 85%;
								height: 80px;
							}
		
							.p1 {
								width: 50%;
								margin-top: 8%;
							}
		
							.p2 {
								width: 50%;
								margin-top: 1%;
							}
						}
					}
		
				}
			}
		
			.about-banner {
				width: 100%;
				height: 455px;
				background-color: #ddd;
				position: relative;
				.acc{
					width: 80%;
					height: 50px;
					position: absolute;
					top: 10%;
					left: 18%;
					li{
						width: 85px;
						margin-right: 5%;
						height: 35px;
						line-height: 35px;
						float: left;
						background-color: #f7f5f5;
						font-size: 15px;
						color: #929292;
					}
					li.a{
						width: 70px;
					}
				}
				.about-img {	
					width: 80%;
					height: 200px;
					margin: 0 auto;
					position:relative;
					
					top: 20%;
					ul {
						width: 100%;
						height: 100%;
						position: absolute;
						li {
							width: 130px;
							height: 100%;
							float: left;
							margin-top: 5%;
							margin-left: 2%;
							img {
								width: 100%;
								height: 100%;
							}
						}
						li.b{
							display: none;
						}
					}	
				}
				.arr{
					width: 5%;
					height: 55px;
					display: block;
					background-color: orange;
					line-height: 55px;
					font-size: 20px;
					position: absolute;
					left: 5%;
					top: 45%;
					z-index: 99;
					display: none;
					}
					.arr.rig {
						left: auto;
						right: 5%;
					}
					.more{
						width: 30%;
						height: 45px;
						position: absolute;
						left: 30%;
						top: 83%;
						border: 2px solid #bbbaba;
						line-height: 45px;
						a{
							color: #bbbaba;
							display: block;
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
	}
</style>
<script>
	export default{
		name: 'jewellery',
		mounted(){
			var ul = document.querySelector(".nav");
			var lis = ul.children;
			var w = lis[0].offsetWidth;
					console.log(w);
			var n = 0;
			var left = document.querySelectorAll(".arr")[0];
			var right = document.querySelectorAll(".arr")[1];
			console.log(right);
			left.onclick = function(){
				gonext(left,true);
			}
			right.onclick = function(){
				gonext(right,false);
			}
			
			function gonext(el,isg){
				if(el.dataset.left =="true"){
					n = 0;
					if(n == '0'){
						ul.style.left = 0 +'px';
						
						n = 1;
					}
					
				}else{
					n = 1;
					if(n == '1'){	
						var target = -n * w ;
						ul.style.left = target + (-30) + 'px';
						
						n = 0;
					}
					
				}
				
			}
			var rong = document.querySelectorAll(".rong");
			var about = document.querySelector(".about");
			
			if(about.offsetWidth < 376){
				
				rong[1].style.display = 'none';
				rong[2].style.display = 'none';
			}
		}
	}
</script>