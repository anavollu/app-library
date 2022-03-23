<script>
</script>

<main>
  <div class="login-box">
    <div>
      <p class="login-title">Welcome back</p>
      <p class="login-subtitle">Login to your account</p>
    </div>
    <form class="form" action="post">
      <input type="text" id="email" placeholder="E-mail" />
      <input type="password" id="password" placeholder="Password" />
      <div class="remember-wrapper">
        <input type="checkbox" id="remember-me" />
        <label for="remember-me">Remember me</label>
      </div>
      <input type="button" class="button" value="Sign in" />
    </form>
  </div>
</main>

<style>
  main {
    overflow: hidden;
    background-size: cover;
    background-repeat: no-repeat;
    background-color: #fff4f4;
    background-image: url('/background.svg');
    min-height: 100vh;
    min-width: 100vw;
    display: flex;
    justify-content: center;
    font-family: 'Poppins', sans-serif;
  }

  .login-box {
    height: 45vh;
    width: 25vw;
    background-color: white;
    margin: auto;
    padding: 30px;
    border-radius: 10px;
    box-shadow: 0px 4px 40px rgba(0, 0, 0, 0.2);
  }

  .login-title {
    font-weight: 700;
    font-size: 24px;
    line-height: 36px;
  }

  .login-subtitle {
    font-weight: 300;
    font-size: 12px;
    line-height: 18px;
    color: #b9b9b9;
    margin-top: 2px;
  }

  .form {
    margin-top: 30px;
  }

  input {
    font-size: 12px;
    line-height: 18px;
    color: #b9b9b9;
    padding-left: 15px;
    display: flex;
    border-radius: 5px;
    height: 40px;
    width: 290px;
  }

  .remember-wrapper {
    display: flex;
    font-size: 12px;
    line-height: 18px;
    color: #b9b9b9;
    gap: 10px;
    align-items: center;
    margin-top: 23px;
  }

  .button {
    display: flex;
    position: absolute;
    margin-top: 23px;
    background-color: #ea5f76;
    color: white;
    font-weight: 700;
    font-size: 12px;
    line-height: 18px;
    border-radius: 5px;
  }
</style>
