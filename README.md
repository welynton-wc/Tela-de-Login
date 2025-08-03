<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Login</title>

  <!-- Ícones -->
  <link href="https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css" rel="stylesheet">

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, sans-serif;
    }

    body {
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
      background: url('https://4kwallpapers.com/images/walls/thumbs_3t/21293.jpg') no-repeat center center fixed;
      background-size: cover;
    }

    .wrapper {
      width: 400px;
      background: rgba(0, 0, 0, 0.75);
      padding: 40px;
      border-radius: 10px;
      color: #fff;
      box-shadow: 0 0 15px rgba(0,0,0,0.6);
    }

    .wrapper h1 {
      text-align: center;
      margin-bottom: 30px;
      font-size: 32px;
    }

    .input-box {
      position: relative;
      margin-bottom: 25px;
    }

    .input-box input {
      width: 100%;
      padding: 15px 45px 15px 15px;
      border: none;
      outline: none;
      border-radius: 30px;
      background: rgba(255, 255, 255, 0.1);
      color: white;
      font-size: 16px;
    }

    .input-box input::placeholder {
      color: rgba(255, 255, 255, 0.7);
    }

    .input-box i {
      position: absolute;
      right: 15px;
      top: 50%;
      transform: translateY(-50%);
      color: white;
      font-size: 20px;
    }

    .remember-forgot {
      display: flex;
      justify-content: space-between;
      align-items: center;
      font-size: 14px;
      margin-bottom: 20px;
    }

    .remember-forgot label {
      display: flex;
      align-items: center;
      gap: 5px;
    }

    .remember-forgot a {
      color: #ddd;
      text-decoration: none;
    }

    .remember-forgot a:hover {
      text-decoration: underline;
    }

    .btn {
      width: 100%;
      padding: 12px;
      background: #fff;
      color: #000;
      font-size: 16px;
      border: none;
      border-radius: 30px;
      cursor: pointer;
      font-weight: bold;
    }

    .btn:hover {
      background: #f1f1f1;
    }

    .register-link {
      text-align: center;
      margin-top: 20px;
      font-size: 14px;
    }

    .register-link a {
      color: #fff;
      font-weight: bold;
      text-decoration: none;
    }

    .register-link a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>
  <div class="wrapper">
    <form action="#">
      <h1>Login</h1>

      <div class="input-box">
        <input type="text" placeholder="E-mail" required>
        <i class="bx bxs-user"></i>
      </div>

      <div class="input-box">
        <input type="password" placeholder="Senha" required>
        <i class="bx bxs-lock-alt"></i>
      </div>

      <div class="remember-forgot">
        <label><input type="checkbox">Lembre de mim</label>
        <a href="#">Esqueceu sua senha?</a>
      </div>

      <button type="submit" class="btn">Login</button>

      <div class="register-link">
        <p>Não tem uma conta? <a href="#"> Cadastre-se</a></p>
      </div>
    </form>
  </div>
</body>
</html>
