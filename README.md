<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Will You Be Mine? ❤️</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            text-align: center;
            background-color: pink;
            padding: 50px;
        }
        h1 {
            color: red;
        }
        button {
            padding: 15px;
            font-size: 18px;
            margin: 10px;
            cursor: pointer;
            border-radius: 10px;
        }
        .yes {
            background-color: green;
            color: white;
        }
        .no {
            background-color: red;
            color: white;
            position: absolute;
        }
    </style>
</head>
<body>

    <h1>Hey Crush! ❤️</h1>
    <p>I have something to ask you...</p>
    <h2>Will you be my Valentine? 😊</h2>

    <button class="yes" onclick="alert('Yay! I knew it! ❤️')">Yes</button>
    <button class="no" id="noButton">No</button>

    <script>
        // Move the "No" button to make it hard to click
        document.getElementById("noButton").addEventListener("mouseover", function() {
            var x = Math.random() * window.innerWidth;
            var y = Math.random() * window.innerHeight;
            this.style.left = x + "px";
            this.style.top = y + "px";
        });
    </script>

</body>
</html>
