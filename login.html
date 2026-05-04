<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Login – Tasty Chicken</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            background-image: url('loginpic.jpg');
            background-size: cover;
            background-repeat: no-repeat;
            background-attachment: fixed;
            min-height: 100vh;
            display: flex;
            flex-direction: column;
        }

        header {
            background-color: maroon;
            padding: 18px;
            text-align: center;
            color: white;
        }

        header h1 {
            font-size: 1.6rem;
        }

        .page-center {
            flex: 1;
            display: flex;
            align-items: center;
            justify-content: center;
            padding: 40px 20px;
        }

        .card {
            background-color: rgba(255, 255, 255, 0.92);
            backdrop-filter: blur(8px);
            border-radius: 14px;
            padding: 40px 36px;
            width: 100%;
            max-width: 400px;
            box-shadow: 0 8px 32px rgba(0, 0, 0, 0.25);
        }

        .card h2 {
            text-align: center;
            color: maroon;
            margin-bottom: 6px;
            font-size: 1.6rem;
        }

        .card .subtitle {
            text-align: center;
            color: #666;
            font-size: 0.9rem;
            margin-bottom: 28px;
        }

        .form-group {
            margin-bottom: 18px;
        }

        label {
            display: block;
            font-weight: bold;
            color: #444;
            margin-bottom: 6px;
            font-size: 0.9rem;
        }

        input[type="text"],
        input[type="password"] {
            width: 100%;
            padding: 10px 14px;
            border: 1.5px solid #ddd;
            border-radius: 8px;
            font-size: 1rem;
            transition: border-color 0.2s;
            background: #fff;
        }

        input:focus {
            outline: none;
            border-color: maroon;
        }

        .error-msg {
            color: #c0392b;
            font-size: 0.85rem;
            margin-top: 4px;
            display: none;
        }

        button[type="submit"] {
            width: 100%;
            padding: 12px;
            background-color: maroon;
            color: white;
            border: none;
            border-radius: 8px;
            font-size: 1rem;
            cursor: pointer;
            margin-top: 8px;
            transition: background-color 0.2s;
        }

        button[type="submit"]:hover {
            background-color: darkred;
        }

        .links {
            text-align: center;
            margin-top: 20px;
            font-size: 0.9rem;
            color: #555;
        }

        .links a {
            color: maroon;
            font-weight: bold;
            text-decoration: none;
        }

        .links a:hover {
            text-decoration: underline;
        }

        footer {
            background-color: #f2f2f2;
            text-align: center;
            padding: 12px;
            font-size: 0.85rem;
            color: #666;
        }

        .alert-box {
            display: none;
            padding: 10px 14px;
            border-radius: 8px;
            margin-bottom: 16px;
            font-size: 0.9rem;
            text-align: center;
        }

        .alert-error {
            background: #fde8e8;
            color: #c0392b;
            border: 1px solid #f5c6c6;
        }

        .alert-success {
            background: #e8f8e8;
            color: #27ae60;
            border: 1px solid #b2e0b2;
        }
    </style>
</head>

<body>

    <header>
        <h1>🍗 Tasty Chicken</h1>
    </header>

    <div class="page-center">
        <div class="card">
            <h2>Welcome Back!</h2>
            <p class="subtitle">Login to access your favourite recipes</p>

            <div class="alert-box" id="alertBox"></div>

            <form id="loginForm" onsubmit="handleLogin(event)">
                <div class="form-group">
                    <label for="username">Username</label>
                    <input type="text" id="username" name="username" placeholder="Enter your username" required>
                </div>
                <div class="form-group">
                    <label for="password">Password</label>
                    <input type="password" id="password" name="password" placeholder="Enter your password" required>
                </div>
                <button type="submit">Login</button>
            </form>

            <div class="links">
                <p>Don't have an account? <a href="signup.html">Sign up here</a></p>
                <p style="margin-top:10px;"><a href="index.html">← Back to Home</a></p>
            </div>
        </div>
    </div>

    <footer>
        <p>© 2025 Tasty Chicken. All rights reserved. | Visakhapatnam</p>
    </footer>

    <script>
        function showAlert(message, type) {
            const box = document.getElementById('alertBox');
            box.textContent = message;
            box.className = 'alert-box alert-' + type;
            box.style.display = 'block';
        }

        function handleLogin(e) {
            e.preventDefault();
            const username = document.getElementById('username').value.trim();
            const password = document.getElementById('password').value;

            // Get users from localStorage
            const users = JSON.parse(localStorage.getItem('tastyChickenUsers') || '[]');
            const user = users.find(u => u.username === username && u.password === password);

            if (user) {
                // Save logged-in session
                localStorage.setItem('tastyChickenSession', JSON.stringify({ username: user.username }));
                showAlert('Login successful! Redirecting...', 'success');
                setTimeout(() => { window.location.href = 'index.html'; }, 1200);
            } else {
                showAlert('Invalid username or password. Please try again.', 'error');
            }
        }
    </script>
</body>

</html>
