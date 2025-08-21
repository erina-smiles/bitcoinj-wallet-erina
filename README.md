Bitcoin Wallet Application

This is my customized implementation of a Bitcoin Wallet Application built using bitcoinj
, a Java library for working with the Bitcoin protocol.

The wallet can:

Maintain addresses and keys

Send/receive transactions

Provide balance information through APIs

Run without needing a local copy of Bitcoin Core (uses SPV mode)

Bitcoinj works in SPV (Simplified Payment Verification) mode, meaning only a lightweight part of the blockchain is downloaded, making it suitable for constrained devices like smartphones or lightweight servers.

🚀 Features

Generate a wallet address

Check wallet balance using an API

Send BTC to any valid address with an API

Lightweight blockchain sync (SPV mode)

⚙️ Setup Instructions

Clone the repository

git clone https://github.com/your-username/bitcoin-wallet-app.git
cd bitcoin-wallet-app


Configure application properties
Create or edit application.properties with your specific values (network, node details, etc.).

Build and run

./mvnw spring-boot:run


(or mvn spring-boot:run if Maven is installed)

📸 Screenshots
After blockchain downloaded completely:

Wallet Address Generated:

Get Balance API:

Send BTC with API:






📌 Notes

Make sure you’re connected to the internet for blockchain sync.

The first sync may take time (SPV mode).

Always keep your private keys secure.

👤 Author

Developed by Erina Smilin S ✨
(Customized from [Bitcoin-Wallet-App-Implementation-With-BitcoinJ](https://github.com/mohsenamjadi/Bitcoin-Wallet-App-Implementation-With-BitcoinJ))
