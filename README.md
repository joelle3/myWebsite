# myWebsite

<!DOCTYPE html>
<html lang="en">
	<head>
		<meta charset="utf-8">
		<meta http-equiv="X-UA-Compatible" content="IE=edge">
		<meta name="viewport" content="width=device-width, initial-scale=1">
		<meta name="description" content="">
		<meta name="author" content="">
	
		<title>WHIM</title>
		
		<!-- Latest compiled and minified CSS -->
		<link rel="stylesheet" href="http://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/css/bootstrap.min.css">
		
		<link rel="stylesheet" href="whimWithLavish.css"/>

		<!-- jQuery library -->
		<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.1/jquery.min.js"></script>

		<!-- Latest compiled JavaScript -->
		<script src="http://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/js/bootstrap.min.js"></script>

		<!--[if lt IE 9]>
			<script src="https://oss.maxcdn.com/html5shiv/3.7.2/html5shiv.min.js"></script>
			<script src="https://oss.maxcdn.com/respond/1.4.2/respond.min.js"></script>
		<![endif]-->
	</head>
	
	<body>
			<!--tumblr post JavaScript SDK-->
			<script src="http://platform.tumblr.com/v1/share.js"></script>
		
		
		
		<!--sets up fixed/scrolling navigation bar-->
		<nav class="navbar navbar-default navbar-fixed-top navbar-inverse">
			<div class="container-fluid">
				<!-- Toggles navigation bar to a button for small screens -->
				<div class="navbar-header">
					<button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#navbar-collapse">
						<span class="sr-only">Toggle navigation</span>
						<span class="icon-bar"></span>
						<span class="icon-bar"></span>
						<span class="icon-bar"></span>
					</button>
					
				</div>
				<!--collapse-able navigation bar-->
				<div class="collapse navbar-collapse" id="navbar-collapse">
					<h4><ul class="nav navbar-nav">
						<li><a href="index.html">Play the Game<span class="sr-only"></span></a></li>
						<li class="active"><a href="about.html">About the Game</a></li>
						<li><a href="Slideshow.html">Barriers Real Women Face</a></li>
					</ul></h4>
				</div><!-- /collaps-able navbar -->
			</div><!-- /.container-fluid -->
		</nav>
		<div class="container">
		</br></br></br>
		
		<!--About the Game-->
		<div data-role="page">
			<div class="page-header">
				<h1>About WHIM</h1>
			</div>
			<div class="page-content">
				<p>WHIM stands for Women's Health Information Maze. The game aims to raise awareness about the low accessibility 
				of reproductive health care in the United States. WHIM is a maze, representing the maze of barriers women must navigate in order to obtain safe 
				and reliable reproductive health care.</p>
				<p>We believe that everyone, no matter their stance on controversial 
				topics such as abortion and use of contraception, deserves the safe, affordable, and accessible sexual health care that they want.</p>
				</br>
				<p>WHIM was created using Blender. This website was created using HTML, CSS, JavaScript, Bootstrap, and is hosted on Github. CSS was adapted from 
				<a href="http://www.lavishbootstrap.com/">Lavish</a>.</p> 
				<p>This game was created by Raye, Joelle, and Adina.</p>
				</br>
				
				<!-- Here we can have blurbs about ourselves as creators-->
					<div class="row">
						<div class="col-md-4">
							<center>
								<img  class="img-circle" src="raye.jpg" style="width: 200px; height: 200px;">
								<h4>Raye</h4>
								<p>Raye is a high school junior at Pelham Memorial High School who started coding sophomore year, and attended the Girls Who Code Summer Immersion 
								program later that year.</p>
							</center>
						</div><!-- /column -->
						<div class="col-md-4">
							<center>
								<img class="img-circle" src="joelle.jpg" width="200px; height: 200pc;">
								<h4>Joelle</h4>
								<p>Joelle is a college freshman at Brandeis University.
								She attended the Girls Who Code Immersion Program in 2013.
								She is now studying computer science at her university and is currently dreaming of doing research or
								using technology to aid in sustainability.</p>
							</center>
						</div><!-- /column -->
						<div class="col-md-4">
							<center>
								<img class="img-circle" src="adina.jpg" style="width: 200px; height: 200px;">
								<h4>Adina</h4>
								<p>Adina is a high school junior at the Bergen County Academies. 
								She has enjoyed coding since her sophomore year of high school. 
								She is excited to be working on such a fantastic project as WHIM!</p>
							</center>
						</div><!-- /column -->	
						
					</div><!-- /row -->
			</div>
		</div>
</br></br></br>
		
		</div><!--/container-->
		
		<!--footer-->
		<div class="container-fluid">
			<div class="page-footer">
				<p class="text-muted"><b>WHIM 2015</b></br>
				<a class="twitter-share-button"href="https://twitter.com/share" data-count="none">Tweet</a>
					<script>window.twttr=(function(d,s,id){var js,fjs=d.getElementsByTagName(s)[0],t=window.twttr||{};if(d.getElementById(id))return;js=d.createElement(s);js.id=id;js.src="https://platform.twitter.com/widgets.js";fjs.parentNode.insertBefore(js,fjs);t._e=[];t.ready=function(f){t._e.push(f);};return t;}(document,"script","twitter-wjs"));
					</script>
				<a href="http://www.tumblr.com/share/link?url=<?php echo urlencode(INSERT_URL_HERE) ?>&name=<?php echo urlencode(INSERT_NAME_HERE) ?>&description=<?php echo urlencode(INSERT_DESCRIPTION_HERE) ?>" title="Share on Tumblr" style="display:inline-block; text-indent:-9999px; overflow:hidden; width:20px; height:20px; background:url('https://platform.tumblr.com/v1/share_4.png') top left no-repeat transparent;">Share on Tumblr</a>	
				</p>
			</div>
		
		<!-- IE10 viewport hack for Surface/desktop Windows 8 bug -->
		<script src="../../assets/js/ie10-viewport-bug-workaround.js"></script>
	  
  
	</body>
</html>
