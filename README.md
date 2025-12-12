<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Sharveshwaran G - Personal Details</title>

    <!-- Google Icons -->
    <link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">

    <style>
        body {
            background: linear-gradient(135deg, #ff6b6b, #f7d794, #1dd1a1, #54a0ff);
            background-size: 400% 400%;
            animation: gradientBG 10s ease infinite;
            font-family: Arial, sans-serif;
            color: white;
            text-align: center;
            padding-top: 50px;
        }

        @keyframes gradientBG {
            0% {background-position: 0% 50%;}
            50% {background-position: 100% 50%;}
            100% {background-position: 0% 50%;}
        }

        .container {
            background: rgba(0,0,0,0.4);
            padding: 30px;
            width: 60%;
            margin: auto;
            border-radius: 20px;
            box-shadow: 0 0 20px rgba(255,255,255,0.4);
        }

        h1 {
            font-size: 40px;
            text-shadow: 2px 2px 5px black;
        }

        .detail {
            font-size: 24px;
            margin: 20px 0;
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 15px;
        }

        .icon {
            font-size: 32px;
        }

        a {
            color: #ffeaa7;
            text-decoration: none;
            font-weight: bold;
        }

        a:hover {
            color: #fffa65;
        }
    </style>
</head>
<body>

    <div class="container">
        <h1>Sharveshwaran G</h1>

        <div class="detail">
            <span class="material-icons icon">email</span>
            Gmail: <a href="mailto:gsharveshwaran@gmail.com">gsharveshwaran@gmail.com</a>
        </div>

        <div class="detail">
            <span class="material-icons icon">phone</span>
            Mobile: <a href="tel:6379125090">6379125090</a>
        </div>

        <div class="detail">
            <span class="material-icons icon">chat</span>
            WhatsApp: <a href="https://wa.me/6379125090">Chat on WhatsApp</a>
        </div>

        <div class="detail">
            <span class="material-icons icon">camera_alt</span>
            Instagram: <a href="https://instagram.com/ig_.sharvesh" target="_blank">@ig_.sharvesh</a>
        </div>
    </div>

</body>
</html>
