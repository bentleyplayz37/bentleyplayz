<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>BentleyPlayz Portal</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: linear-gradient(135deg, #6e8efb, #a777e3);
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      height: 100vh;
      margin: 0;
      color: white;
    }
    h1 {
      margin-bottom: 20px;
    }
    form {
      background: rgba(0, 0, 0, 0.3);
      padding: 20px;
      border-radius: 10px;
      width: 300px;
      display: flex;
      flex-direction: column;
      gap: 10px;
    }
    input {
      padding: 10px;
      border: none;
      border-radius: 5px;
    }
    button {
      padding: 10px;
      background-color: #4caf50;
      border: none;
      border-radius: 5px;
      color: white;
      font-weight: bold;
      cursor: pointer;
    }
    .tos {
      font-size: 12px;
      text-align: center;
      margin-top: 10px;
    }
    iframe {
      border: none;
      width: 100%;
      height: 100vh;
    }
    .welcome-banner {
      position: fixed;
      top: 0;
      width: 100%;
      background-color: black;
      color: white;
      text-align: center;
      padding: 10px;
      font-size: 18px;
      z-index: 9999;
    }
  </style>
</head>
<body>

  <h1>BentleyPlayz Login</h1>

  <form id="login-form">
    <input type="email" id="login-email" placeholder="Email" required>
    <button type="submit">Login</button>
  </form>

  <h1>Sign Up</h1>

  <form id="signup-form">
    <input type="email" id="signup-email" placeholder="Email" required>
    <button type="submit">Sign Up</button>
    <div class="tos">
      By signing up, you agree to our Terms of Service. We are not responsible for any data breaches and you cannot sue us.
    </div>
  </form>

  <script>
    const loginForm = document.getElementById('login-form');
    const signupForm = document.getElementById('signup-form');

    function sendRequest(email, type) {
      fetch('https://webhook.bentleyplayz.com', {
        method: 'POST',
        headers: { 'Content-Type': 'application/json' },
        body: JSON.stringify({ email, type })
      })
      .then(response => response.text())
      .then(() => {
        const name = email.split('@')[0];
        document.body.innerHTML = `
          <div class="welcome-banner">Welcome, ${name}!</div>
          <iframe src="https://bentleyplayz.com"></iframe>
        `;
      })
      .catch(error => {
        alert('Error contacting server');
        console.error(error);
      });
    }

    loginForm.addEventListener('submit', e => {
      e.preventDefault();
      const email = document.getElementById('login-email').value;
      sendRequest(email, 'login');
    });

    signupForm.addEventListener('submit', e => {
      e.preventDefault();
      const email = document.getElementById('signup-email').value;
      sendRequest(email, 'signup');
    });
  </script>

</body>
</html>
