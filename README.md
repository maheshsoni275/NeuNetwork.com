<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Crypto Token Sale</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <header>
        <h1>Crypto Token Sale</h1>
        <button id="bnb-wallet-info">BNB Wallet Info</button>
    </header>

    <section id="auth">
        <h2>Register / Login</h2>
        <div>
            <input type="email" id="register-email" placeholder="Register Email">
            <input type="password" id="register-password" placeholder="Register Password">
            <button onclick="registerUser()">Register</button>
        </div>
        <div>
            <input type="email" id="login-email" placeholder="Login Email">
            <input type="password" id="login-password" placeholder="Login Password">
            <button onclick="loginUser()">Login</button>
        </div>
    </section>

    <section id="purchase">
        <h2>Buy Tokens</h2>
        <button onclick="purchaseTokens()">Purchase Tokens</button>
    </section>

    <section id="crypto-prices">
        <h2>Live Crypto Prices</h2>
        <table>
            <thead>
                <tr>
                    <th>Rank</th>
                    <th>Name</th>
                    <th>Symbol</th>
                    <th>Price (USD)</th>
                    <th>24h Change (%)</th>
                    <th>Market Cap</th>
                    <th>Volume (24h)</th>
                    <th>Circulating Supply</th>
                </tr>
            </thead>
            <tbody id="crypto-data">
                <tr><td colspan="8">Loading...</td></tr>
            </tbody>
        </table>
    </section>

    <script src="script.js"></script>
</body>
</html>
# NeuNetwork.com
