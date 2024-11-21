<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple Login Page</title>
    <style>
        /* Minimal CSS styling */
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            font-family: Arial, sans-serif;
            background-color: #f0f0f5;
            margin: 0;
        }
        .login-container {
            width: 280px;
            padding: 20px;
            background-color: #ffffff;
            text-align: center;
            border: 1px solid #ddd;
            border-radius: 5px;
        }
        input, button {
            width: 100%;
            padding: 8px;
            margin: 8px 0;
            border: 1px solid #ddd;
            border-radius: 4px;
        }
        button {
            background-color: #4CAF50;
            color: #fff;
            cursor: pointer;
        }
        #resetButton {
            background-color: #f44336;
        }
        #statusMessage {
            color: green;
            margin-top: 10px;
        }
    </style>
</head>
<body>

<div class="login-container">
    <h2>Login</h2>
    <input type="text" id="username" placeholder="Username">
    <input type="password" id="password" placeholder="Password">
    
    <button onclick="submitLogin()">Submit</button>
    <button id="resetButton" onclick="resetFields()">Reset</button>
    
    <p id="statusMessage"></p>
</div>

<script>
    function submitLogin() {
        const statusMessage = document.getElementById("statusMessage");
        statusMessage.innerText = "Login successful!";
    }

    function resetFields() {
        document.getElementById("username").value = "";
        document.getElementById("password").value = "";
        document.getElementById("statusMessage").innerText = "";
    }
</script>

</body>
</html>
