# Product Counterfeit Detection using Blockchain

## Packages Required:-
- Truffle v5.11.5 (core: 5.11.5)
- Ganache v7.9.1
- Solidity v0.5.16 (solc-js)
- Node v18.14.2
- Web3.js v1.10.0
- npm 9.6.0


## Other Requirements:-
1. Google Chrome browser 
2. Metamask browser extension
    
## Deploy the Project:- 

1. Clone the project
```
git clone https://github.com/aayushbalaji/Product-Counterfeit-Detection-Using-Blockchain.git
```

2. Go to the project Folder, open a Terminal there and run following command to install the required node_modules:-
```
npm install
```

3. Compile the smart contract source files (Compilation and deployment can be done together using ```truffle migrate``` ):-
```
truffle compile
```

4. Open Ganache to setup local blockchain:-
    - Create a new workspace
    - Add truffle-config.js file as the truffle project 
    - Uncomment the deployment class and change the port to 7545 in the truffle-config.js file

5. In Chrome, open Metamask:-
   - Add a new test network using:
        - NETWORK ID (5777) from Ganache Server settings 
        - RPC SERVER (https://127.0.0.1:7545), from Ganache Server settings
        - CHAIN CODE (1337)
   - Import any account from the local blockchain available in Ganache, using its private key.

6. In terminal, run the following commands:-
- Run migrations to deploy contracts:
```
truffle migrate
```
- Start the server and it will open the homepage (index.html) file in Chrome:
```
npm run dev 
``` 

7. Login to metamask, and connect the imported account to the deployed site (localhost:3000)

8. Interact with the site
