<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Mustarobot Invitation</title>
<style>
    /* Background Gradient Animation */
    body {
        margin: 0;
        height: 100vh;
        display: flex;
        justify-content: center;
        align-items: center;
        background: linear-gradient(270deg, #ff6ec4, #7873f5, #42e695, #fddb92);
        background-size: 800% 800%;
        animation: gradientBG 15s ease infinite;
        font-family: 'Arial', sans-serif;
    }

    @keyframes gradientBG {
        0% { background-position: 0% 50%; }
        50% { background-position: 100% 50%; }
        100% { background-position: 0% 50%; }
    }

    /* Container */
    .container {
        text-align: center;
        background: rgba(255,255,255,0.1);
        padding: 50px 80px;
        border-radius: 20px;
        box-shadow: 0 10px 25px rgba(0,0,0,0.2);
        backdrop-filter: blur(10px);
        animation: fadeIn 2s ease forwards;
        color: white;
    }

    @keyframes fadeIn {
        from {opacity:0; transform: translateY(-50px);}
        to {opacity:1; transform: translateY(0);}
    }

    h1 {
        font-size: 3em;
        margin-bottom: 20px;
        text-shadow: 2px 2px 10px rgba(0,0,0,0.3);
        animation: slideIn 1.5s ease forwards;
    }

    @keyframes slideIn {
        from {opacity:0; transform: translateX(-100px);}
        to {opacity:1; transform: translateX(0);}
    }

    p {
        font-size: 1.2em;
        margin-bottom: 40px;
    }

    /* Button */
    .btn {
        background: linear-gradient(45deg, #ff6ec4, #7873f5, #42e695, #fddb92);
        background-size: 400% 400%;
        padding: 20px 50px;
        font-size: 1.5em;
        color: white;
        border: none;
        border-radius: 50px;
        cursor: pointer;
        text-decoration: none;
        box-shadow: 0 5px 15px rgba(0,0,0,0.3);
        transition: all 0.3s ease;
        animation: pulse 2s infinite;
    }

    .btn:hover {
        transform: scale(1.1) rotate(-2deg);
        box-shadow: 0 10px 25px rgba(0,0,0,0.5);
    }

    @keyframes pulse {
        0% { background-position: 0% 50%; }
        50% { background-position: 100% 50%; }
        100% { background-position: 0% 50%; }
    }
</style>
</head>
<body>
<div class="container">
    <h1>🎉 You're Invited! 🎉</h1>
    <p>Click the button below to access Mustarobot and join the adventure!</p>
    <a href="https://mustarobots-pyfdaqbh.manus.space" target="_blank" class="btn">Open Mustarobot</a>
</div>
</body>
</html>
