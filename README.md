# Will you be my girlfriend?
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Will You Be My Girlfriend?</title>
    <style>
        body {
            text-align: center;
            font-family: Arial, sans-serif;
            margin-top: 100px;
        }
        #yes {
            font-size: 20px;
            padding: 10px 20px;
            background-color: #28a745;
            color: white;
            border: none;
            cursor: pointer;
        }
        #no {
            font-size: 20px;
            padding: 10px 20px;
            background-color: #dc3545;
            color: white;
            border: none;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <h1>Will You Be My Girlfriend? ❤️</h1>
    <button id="yes">Yes</button>
    <button id="no">No</button>

    <script>
        let yesButton = document.getElementById("yes");
        let noButton = document.getElementById("no");

        noButton.addEventListener("click", function() {
            let currentSize = parseInt(window.getComputedStyle(yesButton).fontSize);
            yesButton.style.fontSize = (currentSize + 5) + "px";
        });

        yesbutton.addEventListener("click", function() {
            alert("Yay! I knew you'd say yes! ❤️");
        });
    </script>
</body>
</html>
