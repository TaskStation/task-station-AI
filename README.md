# task-station-AI
Using taskstation make your tasks as train station
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Sign In - Task Station</title>
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: linear-gradient(135deg, #c2e9fb, #a1c4fd);
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
    }

    .container {
      background: rgba(255, 255, 255, 0.25);
      backdrop-filter: blur(15px);
      -webkit-backdrop-filter: blur(15px);
      padding: 40px;
      border-radius: 20px;
      box-shadow: 0 12px 30px rgba(0, 0, 0, 0.15);
      width: 100%;
      max-width: 400px;
      text-align: center;
      animation: fadeIn 0.6s ease-out;
      border: 1px solid rgba(255, 255, 255, 0.3);
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }

    h2 {
      margin-bottom: 25px;
      color: #2d2d2d;
      font-size: 26px;
    }

    input[type="email"],
    input[type="password"] {
      width: 100%;
      padding: 12px;
      margin: 10px 0;
      border: 1px solid rgba(0,0,0,0.1);
      border-radius: 10px;
      font-size: 16px;
      background: rgba(255, 255, 255, 0.6);
      backdrop-filter: blur(8px);
      transition: border 0.2s;
    }

    input:focus {
      border-color: #7ba7ff;
      outline: none;
    }

    button {
      width: 100%;
      padding: 12px;
      background-color: #6c63ff;
      color: #fff;
      border: none;
      border-radius: 10px;
      font-size: 16px;
      margin-top: 15px;
      cursor: pointer;
      transition: background-color 0.2s, transform 0.1s;
    }

    button:hover {
      background-color: #574de2;
      transform: translateY(-1px);
    }

    .google-btn {
      background-color: #ea4335;
      margin-top: 10px;
    }

    .google-btn:hover {
      background-color: #c63528;
    }

    .links {
      margin-top: 18px;
      font-size: 14px;
      color: #333;
    }

    .links a {
      color: #6c63ff;
      text-decoration: none;
    }

    .links a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>
  <div class="container">
    <h2>Sign In to Task Station</h2>
    <form action="file:///C:/Users/baido/Desktop/task%20station%20AI/main%20page.html">
      <input type="email" placeholder="Email" required />
      <input type="password" placeholder="password" required />
      <button type="submit">Sign In</button>
      <button type="button" class="google-btn">Continue with Google</button>
    </form>
    <div class="links">
      <p><a href="#">Forgot password?</a></p>
      <p>Don't have an account? <a href="#">Sign up</a></p>
    </div>
  </div>
</body>
</html>
