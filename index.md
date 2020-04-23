<!DOCTYPE html>
<html>
<head>
	<title>Red Chilli Restaurant</title>
	<meta name= viewport content= "width=device-width, initial-scale=1.0">
	<link rel="stylesheet" type="text/css" href="css/style.css">
	<link href="https://fonts.googleapis.com/css?family=Flamenco" rel="stylesheet">
	<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/3.5.2/animate.min.css">
	<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
</head>
<body>

	<header>
		<nav>
			<div class="row clearfix">
				<img src="images/logo.png" class="logo">

				<ul class="main-nav animated slideInDown" id="check-class">
					<li><a href="#"><b>FOOD DELIVERY</b></a></li>
					<li><a href="#"><b>HOW TO ORDER</b></a></li>
					<li><a href="#"><b>CHECK MORE</b></a></li>
					<li><a href="#"><b>Sign up</b></a></li>
				</ul>
				<a href="#" class="mobile-icon"  onclick="slideshow()"> <i class="fa fa-bars"></i> </a>
			</div>
		</nav>

		<div class="main-content-header">
			<h1><b>WELCOME TO</b> <span class="colorchange"><b>RED CHILLI RESTAURANT</b></span>.<br>
				<b>HOUSE OF FOOD LOVER OO YES.</b> </h1>
			<a href="#" class="btn btn-full"> click to order</a>
			<a href="#" class="btn btn-nav"> show me more</a>
		</div>
	</header>

	<script type="text/javascript">
		
		function slideshow(){
			 var x = document.getElementById('check-class');
			 if(x.style.display === "none"){
			 	x.style.display="block";
			 }else{
			 	x.style.display="none";
			 }
		}	

	</script>

</body>
</html>
