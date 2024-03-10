<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>main site for all my stuff!! :D</title>
    <!-- You can add additional meta tags, stylesheets, or scripts in the head section -->
</head>
<body>

    <header>
        <h1>main site for all my stuff!! :D</h1>
        <!-- Add any header content here -->
    </header>

    <main>
        <p>yahallo! you can find all my websites and ongoing projects! ill try to update everything when i can.</p>
        <!-- Add your main content here -->
    </main>

    <footer>
        <p>&copy; 2024 AlvinarioWorks. All rights reserved.</p>
        <!-- Add your footer content here -->
    </footer>

</body>
</html>

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>clcik here to go to goog!1!!</title>
</head>
<body>
    <button onclick="window.location.href = 'https://www.google.com';">go to goog</button>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Confetti Explosion</title>
    <!-- Include confetti-js library -->
    <script src="https://cdn.jsdelivr.net/npm/canvas-confetti@1.0.1/dist/canvas-confetti.min.js"></script>
</head>
<body>
    <!-- Button to trigger confetti explosion -->
    <button onclick="explodeConfetti()">Explode Confetti!</button>

    <!-- Script to handle confetti explosion -->
    <script>
        function explodeConfetti() {
            // Configure confetti settings
            var config = {
                angle: 90,
                spread: 360,
                startVelocity: 40,
                elementCount: 70,
                decay: 0.9
            };
            // Trigger confetti explosion
            confetti.create(document.body, config).fire();
        }
    </script>
</body>
</html>
