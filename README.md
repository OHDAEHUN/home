<!DOCTYPE html>
<html lang="ko">

<head>
	<meta charset="UTF-8">
	<title>js 문72</title>
	<link rel="stylesheet" href="index.css">
</head>
<!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-RQ2YLVWXG8"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-RQ2YLVWXG8');
</script>

<body>
	<div class="container">
		<h1>로그인</h1>
		<form>
			<div class="form-control">
				<input type="text" id="id" required />
				<label>Id</label>
			</div>
			<div class="form-control">
				<input type="password" id="pw" required />
				<label>Password</label>
			</div>
			<button class="btn" onclick="login();">로그인</button>
			<p class="text">계정이 없나요? <a href="member.html">회원가입</a></p>
		</form>
		<div style="text-align: center;">
			<span id="clock" style="color:rgb(255, 255, 255); font-size: 60px;">clock</span>
			<span id="apm" style="color:rgb(255, 255, 255); font-size: 30px;">ampm</span>
		</div>
	</div>
	<script src="index.js"></script>
	<script src="time.js"></script>
</body>

</html>
