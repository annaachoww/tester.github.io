<!DOCTYPE html>
<html lang="en">
<head>

<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
	<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.2.0/jquery.min.js"></script>
	<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
<title>! Magazine</title>
</head>
<body>
{% block style %}
{%  endblock %}

<div id="page-wrapper">
	<div class="row border-bottom">
		<nav class="navbar navbar-default" data-spy="affix" data-offset-top="52">
			<div>
				<!-- Not sure wtf this is, you can play with this to get it to do what you want, it didnt cooperate with me -->
				<!-- <div class="navbar-header">
					<button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#bs-example-navbar-collapse-1" aria-expanded="false">
						<span class="sr-only">Toggle navigation</span>
						<span class="icon-bar"></span>
						<span class="icon-bar"></span>
						<span class="icon-bar"></span>
					</button>
					<a class="navbar-brand" href="#">!!</a>
				</div> -->

				<div class="collapse navbar-collapse" id="bs-example-navbar-collapse-1" style="margin-left: 25%">
					<ul class="nav navbar-nav navbar">
						<li class="active"><a href="#">Arts<span class="sr-only">(current)</span></a></li>

						<li class="dropdown"><a href="#" class="dropdown-toggle" data-toggle="dropdown" role="button" aria-haspopup="true" aria-expanded="false">Identity<span class="caret"></span></a>
						<ul class="dropdown-menu">
							<li><a href="#">Culture</a></li>
							<li><a href="#">Sextuality</a></li>
							<li><a href="#">Gender</a></li>
							<li><a href="#">Race</a></li>
						</ul>
						</li>
						<li class="dropdown"><a href="#" class="dropdown-toggle" data-toggle="dropdown" role="button" aria-haspopup="true" aria-expanded="false">Feelings<span class="caret"></span></a>
						<ul class="dropdown-menu">
							<li><a href="#">Love</a></li>
							<li><a href="#">Melancholy</a></li>
							<li><a href="#">Wanderlust</a></li>
						</ul>
						</li>
					</ul>

					<div class="navbar-form" style="float: right;">
						<div class="form-group">
							<input type="text" class="form-control" placeholder="Search">
						</div>
					<div>
				</div>
			</div>
		</nav>
	</div>
	<div class="wrapper wrapper-content">
		{% block body %}
		{% endblock %}
	</div>
</div>
