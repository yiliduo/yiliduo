<template>
	<div id="app">
		<div class="header">
			<div class="header-conter">
				<div class="logo">
					<img src="../public/image/logo.png" alt="">
				</div>
				<div id="nav">
					<router-link to="/">首页</router-link>
					<router-link to="/dress">婚纱礼服</router-link>
					<router-link to="/jewellery">珠宝配饰</router-link>
					<router-link to="/news">最新活动</router-link>
					<router-link to="/about">关于我们</router-link>
				</div>
			</div>
			<router-view />
		</div>
		<div class="caidan">
			<img src="image/caidan.png" alt="">
		</div>
	</div>
</template>

<style lang="scss">
	* {
		margin: 0;
		padding: 0;
	}

	a {
		text-decoration: none;
	}

	ul {
		list-style: none;
	}

	@media screen and (min-width: 1178px) {
		#app {
			font-family: 'Avenir', Helvetica, Arial, sans-serif;
			-webkit-font-smoothing: antialiased;
			-moz-osx-font-smoothing: grayscale;
			text-align: center;
			color: #2c3e50;
			position: relative;
		}

		#nav {
			width: 50%;
			height: 80px;
			text-align: center;
			position: absolute;
			left: 40%;

			a {
				display: block;
				width: 80px;
				height: 80px;
				float: left;
				text-align: center;
				margin-left: 5%;
				line-height: 80px;
				color: #333;

				&.router-link-exact-active {
					color: orange;
				}
			}
		}

		.header {
			width: 100%;
			height: 80px;

			.header-conter {
				width: 90%;
				height: 80px;
				margin: 0 auto;

				.logo {
					width: 177px;
					height: 42px;
					margin-left: 180px;
					padding-top: 22px;
					float: left;

					img {
						width: 100%;
						height: 100%;
					}
				}
			}

		}
	}

	@media screen and (max-width: 768px) {
		#app {
			font-family: 'Avenir', Helvetica, Arial, sans-serif;
			-webkit-font-smoothing: antialiased;
			-moz-osx-font-smoothing: grayscale;
			text-align: center;
			color: #2c3e50;
			position: relative;

			.caidan {
				width: 33px;
				height: 33px;
				position: absolute;
				left: 5%;
				top: 35%;
				background-image: url('image/cai.png');
				background-repeat: no-repeat;
			}
		}

		#nav {
			width: 80%;

			text-align: center;
			position: absolute;
			background-color: white;
			left: 10%;
			top: 100%;
			opacity: 0.8;
			z-index: 999;
			display: none;

			a {
				z-index: 1000;
				display: block;
				width: 100%;
				float: left;
				text-align: center;

				line-height: 80px;
				color: #333;

				&.router-link-exact-active {}
			}
		}

		.header {
			width: 100%;
			height: 80px;

			.header-conter {
				width: 90%;
				height: 80px;
				margin: 0 auto;
				position: relative;

				.logo {
					width: 33%;
					height: 42px;
					margin-left: 33%;
					padding-top: 22px;
					float: left;

					img {
						width: 100%;
						height: 100%;
					}
				}
			}

		}
	}
</style>
<script>
	export default {
		name: 'app',
		mounted() {
			var caidan = document.querySelector('.caidan');
			var nav = document.querySelector('#nav');
			var navs = nav.children;
			console.log(navs);
			var body = document.querySelector('body');
			var n = 0;
			if (body.offsetWidth < 800) {
				caidan.ontouchstart = function() {
					gonext();
				}
				nav.ontouchstart = function(e) {
					
						gonext();
					
					
				}
			}
			function gonext(){
				if (n == "0") {
					setTimeout(function() {
						nav.style.display = "block";
						n = 1;
					}, 500)
				} else if (n == "1") {
					setTimeout(function() {
						nav.style.display = "none";
						n = 0;
					}, 500)
				}
			}
				
		}
		
	}
</script>
