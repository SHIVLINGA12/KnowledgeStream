<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FutureTech Hub</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #111;
            color: #fff;
        }
        header {
            text-align: center;
            padding: 20px;
            background-color: #222;
        }
        .container {
            padding: 20px;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
        }
        section {
            padding: 20px;
            background-color: #333;
            border-radius: 8px;
            text-align: center;
        }
        button {
            padding: 10px;
            background-color: #00ffcc;
            border: none;
            cursor: pointer;
            color: #111;
            font-weight: bold;
            border-radius: 5px;
        }
        button:hover {
            background-color: #008f99;
        }
        .chatbot-box {
            border: 2px solid #00ffcc;
            padding: 10px;
            border-radius: 8px;
            background-color: #222;
            text-align: center;
        }
        input {
            padding: 8px;
            width: 80%;
        }
    </style>
</head>
<body>

<header>
    <h1>FutureTech Hub 🌐</h1>
    <p>Explore AI, Quantum, IoT, Blockchain, Metaverse & More</p>
</header>

<section class="chatbot-box">
    <h2>🤖 AI Chatbot</h2>
    <p id="chatbot-response">Ask me anything about future tech!</p>
    <input type="text" id="chatbot-input" placeholder="Type your question...">
    <button onclick="askChatbot()">Ask</button>
</section>

<div class="container">
    <section>
        <h2>⚛️ Quantum Computing</h2>
        <p>Simulating quantum algorithms... (Coming Soon)</p>
    </section>

    <section>
        <h2>🌍 IoT Dashboard</h2>
        <p>Live IoT data: Temperature: 25°C, Air Quality: Good</p>
    </section>

    <section>
        <h2>🔗 Blockchain Transactions</h2>
        <p>Demo: Transaction recorded on a decentralized ledger.</p>
        <button onclick="simulateTransaction()">Send Transaction</button>
    </section>

    <section>
        <h2>🛡️ Cybersecurity AI Scanner</h2>
        <p>Check for security threats... (Coming Soon)</p>
    </section>

    <section>
        <h2>🌐 Metaverse VR Room</h2>
        <p>Explore the future in VR... (Coming Soon)</p>
    </section>

    <section>
        <h2>🎭 Augmented Reality (AR)</h2>
        <p>View futuristic models in AR... (Coming Soon)</p>
    </section>

    <section>
        <h2>🧬 Biotech Innovations</h2>
        <p>Gene editing and CRISPR simulations... (Coming Soon)</p>
    </section>

    <section>
        <h2>⚡ AI Green Energy Predictor</h2>
        <p>AI estimates solar & wind energy usage... (Coming Soon)</p>
    </section>

    <section>
        <h2>📶 6G Network Visualizer</h2>
        <p>See how 6G connects the world... (Coming Soon)</p>
    </section>
</div>

<script>
    function askChatbot() {
        let input = document.getElementById("chatbot-input").value.toLowerCase();
        let response = "I'm still learning. Try again!";
        
        if (input.includes("ai")) response = "AI is transforming automation and human interaction!";
        if (input.includes("quantum")) response = "Quantum computing uses qubits for ultra-fast calculations!";
        if (input.includes("blockchain")) response = "Blockchain is a decentralized ledger used in crypto and more!";
        
        document.getElementById("chatbot-response").innerText = response;
    }

    function simulateTransaction() {
        alert("Transaction successfully recorded on blockchain!");
    }
</script>

</body>
</html>
