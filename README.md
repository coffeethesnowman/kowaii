<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kolwaii Agent</title>
    <style>
        body {
            background-image: url('https://github.com/user-attachments/assets/52903e7e-4afa-492d-836d-4a756833c43a');
            background-size: cover;
            background-repeat: no-repeat;
            background-attachment: fixed;
            backdrop-filter: blur(5px);
            color: #fff;
            text-align: center;
            font-family: Arial, sans-serif;
        }
        a {
            color: #00f;
        }
        img {
            margin-top: 20px;
            cursor: pointer;
        }
        #fact {
            margin-top: 20px;
            font-size: 1.2em;
            color: #ffd700;
        }
    </style>
    <script>
        const cryptoFacts = [
            "Bitcoin was the first cryptocurrency, launched in 2009.",
            "Ethereum introduced the concept of smart contracts.",
            "The total supply of Bitcoin is capped at 21 million coins.",
            "Dogecoin started as a joke but gained massive popularity.",
            "The creator of Bitcoin is known by the pseudonym Satoshi Nakamoto.",
            "Blockchain technology ensures transparency and security in transactions.",
            "Ripple's XRP is designed for real-time international payments.",
            "Litecoin is often referred to as the silver to Bitcoin's gold.",
            "Proof of Work and Proof of Stake are popular consensus mechanisms.",
            "NFTs represent unique digital assets on the blockchain.",
            "El Salvador was the first country to adopt Bitcoin as legal tender.",
            "Mining Bitcoin consumes significant amounts of electricity.",
            "Stablecoins are cryptocurrencies pegged to a stable asset like USD.",
            "Binance Coin (BNB) is the native token of the Binance exchange.",
            "DeFi stands for Decentralized Finance.",
            "The first Bitcoin transaction was used to buy two pizzas for 10,000 BTC.",
            "Ethereum 2.0 introduced Proof of Stake to the Ethereum network.",
            "Polkadot enables interoperability between different blockchains.",
            "Cardano uses a Proof of Stake mechanism called Ouroboros.",
            "Smart contracts are self-executing contracts with predefined conditions.",
            "Cryptography is the backbone of cryptocurrency security.",
            "The halving event reduces Bitcoin miner rewards by half every 4 years.",
            "Solana is known for its high-speed transactions.",
            "The term HODL originated from a typo meaning Hold.",
            "Shiba Inu is a popular meme cryptocurrency.",
            "Cryptocurrency wallets can be hot (online) or cold (offline).",
            "Tether (USDT) is the most widely used stablecoin.",
            "Bitcoin's first block is called the Genesis Block.",
            "Cryptokitties was one of the first popular blockchain games.",
            "Many governments are exploring Central Bank Digital Currencies (CBDCs).",
            "Decentralized Autonomous Organizations (DAOs) operate on blockchain governance.",
            "Chainlink connects smart contracts with real-world data.",
            "Uniswap is a leading decentralized exchange (DEX).",
            "Staking allows users to earn rewards by locking their cryptocurrency.",
            "Metaverse projects like Decentraland use blockchain for virtual assets.",
            "Bitcoin is often referred to as digital gold.",
            "Cryptocurrency transactions are recorded on the blockchain.",
            "Gas fees are paid to process transactions on the Ethereum network.",
            "Proof of Burn is a less common consensus mechanism.",
            "The Bitcoin network adjusts mining difficulty every two weeks.",
            "Meme coins often derive value from community hype.",
            "Governance tokens allow holders to vote on protocol decisions.",
            "The term "whale" refers to large cryptocurrency holders.",
            "Yield farming is a way to earn rewards in DeFi platforms.",
            "Bitcoin ATMs allow users to buy and sell Bitcoin with cash.",
            "Public and private keys are used to secure cryptocurrency transactions.",
            "The Lightning Network enables faster Bitcoin transactions.",
            "Privacy coins like Monero prioritize transaction anonymity.",
            "Cryptocurrency can be highly volatile." 
        ];

        function displayRandomFact() {
            const randomIndex = Math.floor(Math.random() * cryptoFacts.length);
            document.getElementById('fact').innerText = cryptoFacts[randomIndex];
        }
    </script>
</head>
<body>
    <h1>Welcome to Kolwaii Agent</h1>
    <img src="https://github.com/user-attachments/assets/e3a6b277-d5d8-4b4f-b894-4a25d1201c99" alt="Kolwaii Logo" style="width:150px;height:auto;" onclick="displayRandomFact()">
    <p>Follow us on Twitter:</p>
    <a href="https://x.com/kolwaii" target="_blank">https://x.com/kolwaii</a>
    <p id="fact">Click the image for a crypto fact!</p>
</body>
</html>
