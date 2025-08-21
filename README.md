Bitcoin Wallet Application
This is my customized implementation of a Bitcoin Wallet Application built using bitcoinj, a Java library for working with the Bitcoin protocol.
The wallet can:
•	Maintain addresses and keys
•	Send/receive transactions
•	Provide balance information through APIs
•	Run without needing a local copy of Bitcoin Core (uses SPV mode)
Bitcoinj works in SPV (Simplified Payment Verification) mode, meaning only a lightweight part of the blockchain is downloaded, making it suitable for constrained devices like smartphones or lightweight servers.
________________________________________
🚀 Features
•	Generate a wallet address
•	Check wallet balance using an API
•	Send BTC to any valid address with an API
•	Lightweight blockchain sync (SPV mode)
________________________________________
⚙️ Setup Instructions
1.	Clone the repository
2.	git clone https://github.com/your-username/bitcoin-wallet-app.git
3.	cd bitcoin-wallet-app
4.	Configure application properties
Create or edit application.properties with your specific values (network, node details, etc.).
5.	Build and run
6.	./mvnw spring-boot:run
(or mvn spring-boot:run if Maven is installed)
________________________________________
📸 Screenshots
After blockchain downloaded completely:
 
Wallet Address Generated:
 
Get Balance API:
 
Send BTC with API:
 
 
 
________________________________________
📌 Notes
•	Make sure you’re connected to the internet for blockchain sync.
•	The first sync may take time (SPV mode).
•	Always keep your private keys secure.
________________________________________
👤 Author
Developed by Erina Smilin S ✨
(Customized from original Bitcoin-Wallet-App-Implementation-With-BitcoinJ))
