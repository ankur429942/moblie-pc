<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FFMAX Injector</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #111;
            color: white;
        }
        .btn {
            background: #ff4500;
            color: white;
            border: none;
            padding: 10px 20px;
            font-size: 18px;
            cursor: pointer;
            margin-top: 20px;
            border-radius: 5px;
        }
        .btn:hover {
            background: #ff5733;
        }
    </style>
</head>
<body>

    <h1>🔥 FFMAX Headshot Injector 🔥</h1>
    <p>Enable 100% Headshots with One Click!</p>
    
    <button class="btn" onclick="injectConfig()">Inject Headshot Config</button>

    <script>
        function injectConfig() {
            var link = document.createElement('a');
            link.href = "https://yourserver.com/config.xml"; // Replace with actual file link
            link.download = "config.xml";
            document.body.appendChild(link);
            link.click();
            document.body.removeChild(link);
            alert("✅ Headshot Config Downloaded! Now Move to FFMAX Folder");
        }
    </script>

</body>
</html>
