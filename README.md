<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rose Bouquet</title>
    <style>
        body {
            text-align: center;
            background: linear-gradient(135deg, #ffdde1, #ee9ca7);
            font-family: "Arial", sans-serif;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }
        .container {
            background: white;
            padding: 20px;
            border-radius: 12px;
            box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.2);
            animation: fadeIn 2s ease-in-out;
        }
        h1 {
            color: #b71c1c;
            font-size: 28px;
        }
        p {
            color: #444;
            font-size: 16px;
        }
        .bouquet {
            width: 300px;
            border-radius: 10px;
            box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.2);
            animation: bloom 3s ease-in-out;
        }
        @keyframes fadeIn {
            from { opacity: 0; transform: scale(0.8); }
            to { opacity: 1; transform: scale(1); }
        }
        @keyframes bloom {
            from { transform: scale(0.5); opacity: 0; }
            to { transform: scale(1); opacity: 1; }
        }
        .message {
            margin-top: 20px;
            padding: 10px 20px;
            background-color: #b71c1c;
            color: white;
            border-radius: 8px;
            display: inline-block;
            font-size: 18px;
            font-weight: bold;
            animation: fadeIn 2s ease-in-out;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>🌹A Bouquet for You!🌹</h1>
        <p>Keep on making lovely memes and make me laugh </p>
        <img src="https://drive.google.com/uc?export=view&id=14TAxulhausktlwbms2Cg9qIYtCgjmXU-" 
             alt="Rose Bouquet" class="bouquet">
        <p class="message">With Love & Best Wishes ❤️</p>
    </div>
</body>
</html>
