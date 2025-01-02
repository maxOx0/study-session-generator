

<!DOCTYPE html>
<html>
<head>
    <title>How to make this study session nice?</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            margin-top: 50px;
        }
        button {
            padding: 10px 20px;
            font-size: 16px;
            cursor: pointer;
        }
        #result {
            margin-top: 20px;
            font-size: 20px;
            color: #333;
        }
    </style>
</head>
<body>
    <h1>How to make this study session nice?</h1>
    <button onclick="pickRandom()">SELECT</button>
    <div id="result"></div>

    <script>
        // Array of options
        const options = ["light a candle", "make tea", "light incense", "salt lamp", "white noise", "take gemstones for focus", "meditate before session"];

        // Function to pick a random option
        function pickRandom() {
            const randomIndex = Math.floor(Math.random() * options.length); // Get a random index
            const selectedOption = options[randomIndex]; // Pick the option
            document.getElementById("result").textContent = `${selectedOption}`; // Display the result
        }
    </script>
</body>
</html>
