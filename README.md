<html>
<head>
	<title>Research Scientist</title>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<link rel="stylesheet" href="style.css">
</head>
<body>
	<header>
		<h1>Welcome to My Website</h1>
		<nav>
			<ul>
				<li><a href="#">Home</a></li>
				<li><a href="#">About</a></li>
				<li><a href="#">Contact</a></li>
			</ul>
		</nav>
	</header>
	<main>
		<section>
			<h2>About Me</h2>
			<p>I am a research scientist in the field of solid state physics and especially interested to develop and bring innovative technology to application. </p>
		</section>
		<section>
			<h2>Contact Us</h2>
			<form action="submit-form.php" method="post">
				<label for="name">Name:</label>
				<input type="text" id="name" name="name" required><br>
				<label for="email">Email:</label>
				<input type="email" id="email" name="email" required><br>
				<label for="message">Message:</label>
				<textarea id="message" name="message" required></textarea><br>
				<input type="submit" value="Send">
			</form>
		</section>
	</main>
	<footer>
		<p>&copy; 2023 </p>
	</footer>
</body>
</html>
