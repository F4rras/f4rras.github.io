# f4rras.github.io
<html>
	<head>
		<meta charset="utf-8"c/>
		<link rel="" href=""/>
		<meta name="viewport" content="width=device-width, initial-scale=1" />
		<title>Website</title>
		<link rel="stylesheet" href="style.css" />
		<link
    rel="stylesheet"
    href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css"
  />
	</head>
	<body>
		<header class="animate__animated animate__backInDown animate__slower">
			<div class="logo">
				<img src="assets/icon/logo.jpg" alt="" class="logo-img"/>
				<h1 class="logo-title animate__animated animate__swing animate__infinite">FARRAS<h1>
			</div>
			<nav>
				<ul>
					<li><a href="#jasa">JASA</a></li>
					<li><a href="https://www.instagram.com/fr4g_s/">CONTACT</a></li>
				</ul>
			</nav>
			<button class="btn-cta" onclick="redirInstagram">Follow me</button>
		</header>
		<div class="container">
			<div class="intro">
				<p class="title  animate__animated animate__backInLeft animate__faster">hello i'm Farras</p>
				<p class="description  animate__animated animate__backInRight animate__faster">i study at SMPN 255 Jakarta</p>
				<img src="assets/foto/kambing.jpg" alt="kambing,jpg" class="img-foto  animate__animated animate__tada animate__slower"/>
			</div>
		</div>
		<div class="paralax">
			<div class="tentang">
				<p class="title">Saya suka mempelajari hal baru</p>
				<p class="description">#ngetest</p>
				<div class="mt-10">
					<button class="btn-cta" onclick="redirContact">Mari Berkawan</button>
				</div>
			</div>
			<div class="container">
				<div class="card animate__animated animate__backInRight" id="jasa">
					<div class="card-item">
						<img src="assets/icon/Chat.jpg" alt="Chat.jpg" class="icon"/>
						<p class="card-title">Layanan chat 24/7</p>
						<p class="card-description">Solusi bagi anda yang gabut</p>
					</div>
					<div class="card-item">
						<img src="assets/icon/bantuan.jpg" alt="bantuan.jpg" class="icon"/>
						<p class="card-title">Cepat tanggap</p>
						<p class="card-description">Siap membantu anda kapanpun</p>
					</div>
					<div class="card-item">
						<img src="assets/icon/Telephone.jpeg" alt="Telephone.jpeg" class="icon"/>
						<div class="card-title">Hubungi kami</div>
						<p class="card-description">Hubungi kami jika anda perlu bantuan</p>
					</div>
				</div>
			</div>
		</div>
		<footer>
			<p class="title">&copy; farras website 2024</p>
		</footer>

		<script>
			function redirInstagram () {
				window.location.href= "https://www.instagram.com/fr4g_s/"

			}

			function redirInstagram () {
				window.location.href= "https://www.instagram.com/fr4g_s/"
			}
		</script>
	</body>
</html>
