<script>
</script>

<main>
	<div class="login-box">
		<div>
			<p>Welcome back</p>
			<p>Login to your account</p>
		</div>
		<form action="post">
			<input type="text" label="email">
			<input type="password" label="password">
			<input type="checkbox" name="Remember me" id="remeber-me">
			<p>Remember me</p>
			<input type="button" value="Sign in">
		</form>
	</div>
</main>

<style>
	main {
		overflow: hidden;
		background-size: cover;
		background-repeat: no-repeat;
		background-color: #FFF4F4;
		background-image: url('/background.svg');
		min-height: 100vh;
		min-width: 100vw;
		display: flex;
		justify-content: center;
		font-family: 'Poppins';
	}

	.login-box {
		height: 45vh;
		width: 25vw;
		background-color: white;
		margin: auto;

	}
</style>