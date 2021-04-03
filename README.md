<!DOCTYPE html>
<html>
<head>
	<title>SignUp and Login</title>
	<meta charset="UTF8">
    <meta name="viewport" content="width=devices-width,initial-scale=1.0">
    <meta http-equip="X-UA-Compaitable" content="ie=edge">
	<link rel="stylesheet" type="text/css" href="style.css">
	<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
	<link rel="stylesheet" type="text/css" href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">
	<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js" integrity="sha384-wfSDF2E50Y2D1uUdj0O3uMBJnjuUD4Ih7YwaYd1iqfktj0Uod8GCExl3Og8ifwB6" crossorigin="anonymous"></script>
</head>
<body>
<div class="container-fluid">
	<div class="container">
		<div class="col-md-12 py-5 col-lg-12 col-sm-6 col-auto">
<div class="container" id="container">
<div class="form-container sign-up-container">
<form action="signup.php" method="post">
	<h1>Create Account</h1>
	<div class="social-container">
		<a href="https://www.facebook.com/people/Anmol-Sharma/100004621953711" class="social"><i class="fa fa-facebook-f fa-lg white-text mr-md-5 mr-3 fa-2x"></i></a>
		<a href="https://twitter.com/AnmolSh31767158" class="social"><i class="fa fa-twitter fa-lg white-text mr-md-5 mr-3 fa-2x"></i></a>
		<a href="https://www.instagram.com/anmol_1998cool/" class="social"><i class="fa fa-instagram fa-lg white-text mr-md-5 mr-3 fa-2x"></i></a>
	</div>
	<span>or use your email for registration</span>
	<input type="text" name="name" placeholder="Name">
	<input type="email" name="email" placeholder="Email">
	<input type="password" name="password" placeholder="Password">
	<button>SignUp</button>
</form>
</div>
<div class="form-container sign-in-container">
	<form action="signin.php" method="post">
		<h1>Sign In</h1>
		<div class="social-container">
		<a href="https://www.facebook.com/people/Anmol-Sharma/100004621953711" class="social"><i class="fa fa-facebook-f fa-lg white-text mr-md-5 mr-3 fa-2x"></i></a>
		<a href="https://twitter.com/AnmolSh31767158" class="social"><i class="fa fa-twitter fa-lg white-text mr-md-5 mr-3 fa-2x"></i></a>
		<a href="https://www.instagram.com/anmol_1998cool/" class="social"><i class="fa fa-instagram fa-lg white-text mr-md-5 mr-3 fa-2x"></i></a>
	</div>
	<span>or use your account</span>
	<input type="email" name="email" placeholder="Email">
	<input type="password" name="password" placeholder="Password">
	<a href="#">Forgot Your Password</a>

	<button style="background-color: #a421a4;">Sign In</button>
	</form>
</div>
<div class="overlay-container">
	<div class="overlay">
		<div class="overlay-panel overlay-left">
			<h1>"MOVE" WORK "FORWARD"</h1>
			<p>To keep connected with us please login with your personal info</p>
			<button class="ghost" id="signIn">Sign In</button>
		</div>
		<div class="overlay-panel overlay-right" style="background-color: #643e64;">
			<h1><img src="lo.png" style="height: 110px;"></h1>
			<h1>Welcome To The SignUp Page</h1>
			<p>Enter your details and start journey with us</p>
			<button class="ghost" id="signUp">Sign Up</button>
		</div>
	</div>
</div>
</div>

<script type="text/javascript">
	const signUpButton = document.getElementById('signUp');
	const signInButton = document.getElementById('signIn');
	const container = document.getElementById('container');

	signUpButton.addEventListener('click', () => {
		container.classList.add("right-panel-active");
	});
	signInButton.addEventListener('click', () => {
		container.classList.remove("right-panel-active");
	});
</script>
<br>
<div class="Skip">
<center>
<a href=""><button style="background-color: dimgray; border-color: whitesmoke;" > SKIP </button></a>
</center>
<br>
</div>
</div>
</div>
</div>
</body>
</html>
