# PUBG-UC-GENERATION
BEDAVA UC KODLARI TÜKENMEDEN YÜKLEMENİZİ YAPIN3
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PUBG UC Fun Generator</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>PUBG UC Fun Generator</h1>
        <p>Generate infinite UC... or at least have a good laugh!</p>
    </header>

    <section class="generator">
        <h2>Fake UC Generator</h2>
        <p>Enter your PUBG username and watch the magic happen!</p>
        <form id="uc-form">
            <label for="username">Username:</label>
            <input type="text" id="username" name="username" placeholder="Enter your PUBG username" required>
            <label for="uc-amount">UC Amount:</label>
            <input type="number" id="uc-amount" name="uc-amount" placeholder="Enter amount" required>
            <button type="button" onclick="generateUC()">Generate UC</button>
        </form>
        <p id="result" style="margin-top: 20px; font-weight: bold;"></p>
    </section>

    <section class="trivia">
        <h2>PUBG Trivia</h2>
        <p>Did you know?</p>
        <ul>
            <li>The "chicken dinner" phrase originated from a saying in Las Vegas: "Winner winner, chicken dinner!"</li>
            <li>PUBG was inspired by the Japanese movie "Battle Royale".</li>
            <li>Over 70 million copies of PUBG have been sold worldwide!</li>
        </ul>
    </section>

    <footer>
        <p>&copy; 2025 FunCorp. This site is just for fun and does not actually generate UC.</p>
    </footer>

    <script>
        function generateUC() {
            const username = document.getElementById('username').value;
            const ucAmount = document.getElementById('uc-amount').value;
            const result = document.getElementById('result');

            if (username && ucAmount) {
                result.textContent = `Congratulations, ${username}! You just received ${ucAmount} UC... just kidding! 😄 This is all for fun!`;
            } else {
                result.textContent = 'Please enter both username and UC amount.';
            }
        }
    </script>
</body>
</html>

