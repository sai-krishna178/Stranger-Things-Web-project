<!DOCTYPE html>
<html>
<head>
	<meta charset="UTF-8">
	<title>Strangerthings</title>
	<style>
		nav{
			color:red;
			background-color:black;
			font-size:30px;
			font-family:bold;
		}
			
		.container {
			
			height:100vh;
			width:100%;
			background-color:black;
			position:relative;
			overflow:hidden;
		}
	.mainimage{
			height:100%;
			width:100%;
			object-fit:cover;
			position:absolute;
		}
	.demon{
			
  			clip-path: inset(0 50% 0 0);
  			transition: clip-path 0.1s linear;

  		}	
		</style>
</head>
<body>
	<header>
		<nav>STRANGER THINGS</nav>
	</header>
	<hr>
	
	<div class="container">
			<img src="https://wallpapers.com/images/hd/stranger-things-aesthetic-desktop-v9bs6ggzno7fdcda.jpg" class="img base">
			<img src="https://images.wallpapersden.com/image/wxl-stranger-things-season-5-4k-final-poster_93251.jpg" class="demon" id="mahadev">
	</div>
	<script src="script2.js"></script>
</body>
</html>
