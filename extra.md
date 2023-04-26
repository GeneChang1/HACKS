<!DOCTYPE html>
<html>
<head>
	<title>Cool Layout with Bootstrap</title>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css">
	<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
	<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.9/umd/popper.min.js"></script>
	<script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js"></script>
</head>
<body>
	<nav class="navbar navbar-expand-lg navbar-dark bg-dark">
	  <a class="navbar-brand" href="#">Cool Layout</a>
	  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
	    <span class="navbar-toggler-icon"></span>
	  </button>
	  <div class="collapse navbar-collapse" id="navbarNav">
	    <ul class="navbar-nav">
	      <li class="nav-item active">
	        <a class="nav-link" href="#">Home</a>
	      </li>
	      <li class="nav-item">
	        <a class="nav-link" href="#">About</a>
	      </li>
	      <li class="nav-item">
	        <a class="nav-link" href="#">Services</a>
	      </li>
	      <li class="nav-item">
	        <a class="nav-link" href="#">Contact</a>
	      </li>
	    </ul>
	  </div>
	</nav>

	<div class="jumbotron">
	  <h1 class="display-4">Welcome to Cool Layout!</h1>
	  <p class="lead">This is a simple example of a cool layout using Bootstrap.</p>
	  <hr class="my-4">
	  <p>It uses utility classes for typography and spacing to space content out within the larger container.</p>
	  <a class="btn btn-primary btn-lg" href="#" role="button">Learn more</a>
	</div>

	<div class="container">
	  <div class="row">
	    <div class="col-sm-4">
	      <h3>Column 1</h3>
	      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Fusce malesuada euismod faucibus. Nulla ac erat ut velit iaculis congue.</p>
	    </div>
	    <div class="col-sm-4">
	      <h3>Column 2</h3>
	      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Fusce malesuada euismod faucibus. Nulla ac erat ut velit iaculis congue.</p>
	    </div>
	    <div class="col-sm-4">
	      <h3>Column 3</h3>        
	      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Fusce malesuada euismod faucibus. Nulla ac erat ut velit iaculis congue.</p>
	    </div>
	  </div>
	</div>

	<footer class="container-fluid bg-dark text-center py-3">
	  <p class="text-white">Copyright &copy; 
	  	<script>document.write(new Date().getFullYear())</script> 
	  	Cool Layout. All rights reserved.</p>
	</footer>

</body>
</html>
