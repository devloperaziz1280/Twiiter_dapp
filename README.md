# Twiiter_dapp

🐦 Twitter DApp (Decentralized Application)
A Twitter-like decentralized application (DApp) built on Ethereum that allows users to:

Connect their MetaMask wallet

Post tweets stored on the blockchain

Like tweets

View tweets associated with their address


This project demonstrates how blockchain and Web3 can be used to create social media experiences where data is decentralized and transparent.

🚀 Features
✅ Connect MetaMask wallet

📝 Create and publish tweets

❤️ Like other tweets

🔄 Real-time tweet updates from smart contract

🔒 Data is stored on the Ethereum blockchain via a smart contract


🧠 Tech Stack
Solidity – Smart contract development

Remix IDE – Contract deployment and testing

Web3.js – JavaScript library for Ethereum interactions

MetaMask – Ethereum wallet integration

HTML/CSS/JS – Frontend user interface

Cloud IDE – Hosted with CodeSandbox for frontend



📦 Smart Contract Overview
Smart contract includes:

createTweet(string _tweet) – Post a new tweet

getAllTweets(address _owner) – Fetch all tweets of a user

likeTweet(address author, uint256 id) – Like a tweet by ID

unlikeTweet(address author, uint256 id) – Remove a like from a tweet

getTweet(uint256 _i) – Fetch a single tweet

changeTweetLength(uint16 newTweetLength) – Admin control (optional)

Each tweet contains:

id

author

content

timestamp

likes

🛠 Setup Instructions

1. Clone the repository

Copy
Edit
git clone https://github.com/devloperaziz1280/twitter-dapp.git
cd twitter-dapp

2. Install dependencies

Copy
Edit
npm install

3. Install dependencies

Copy
Edit
npm install


4. Connect MetaMask
Install MetaMask browser extension if not already installed.

Connect your MetaMask wallet to the app.

Make sure to use the same Ethereum network where your contract is deployed (e.g., Goerli/Testnet or Localhost).

4. Deploy Smart Contract (Optional if already deployed)
Use Remix IDE to:

Paste your contract code

Compile and deploy it

Copy the contract address and ABI

5. Update Frontend Config
Edit the following in the JS file:

js
Copy
Edit
const contractAddress = "YOUR_CONTRACT_ADDRESS";
import contractABI from "./abi.json";


📸 Screenshots
    Wallet Connection               	Post Tweet	          Like             Tweet

<img width="1097" height="506" alt="image-1" src="https://github.com/user-attachments/assets/560a3293-bff2-41fb-9650-a01b515edaf1" />

<img width="1324" height="602" alt="image-2" src="https://github.com/user-attachments/assets/849f0ed9-4b23-4b4b-af16-c5b7a6f07ced" />

<img width="1368" height="702" alt="image-3" src="https://github.com/user-attachments/assets/4293f420-1d0d-4140-99b1-ad9801fba72b" />

<img width="1306" height="711" alt="image-4" src="https://github.com/user-attachments/assets/51a66846-b013-46a5-85d9-aad9a254258e" />

📄 License
This project is open-sourced under the MIT License.

🙌 Acknowledgements
Web3.js Documentation – https://web3js.readthedocs.io/

Solidity Language Docs – https://docs.soliditylang.org/

MetaMask Docs – https://docs.metamask.io/

📬 Contact
If you want to learn more or collaborate, feel free to reach out!

Developer: Aziz Ur Rehman
Email: devloperaziz1280@example.com

