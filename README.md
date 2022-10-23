# Smart-Contract-with-Truffle

Requirements:
VS code editor 
https://code.visualstudio.com/download

Node.js
https://nodejs.org/en/

Truffle is little bit more advanced toolset building a complete suite or collection of contracts working together or interacting with external contract.
we can install it by visiting their official website:
https://trufflesuite.com/

Command for installing it in vs code is : 
npm install truffle -g

Truffle is used to compile our contracts locally, to deploy them to either local network or testnet or mainnet, run unit testing before deploying.

After installing truffle in vs code we will run - truffle init
which initializes with basic depositories such as contracts,migrations,test and a truffle
configuration file.we can start creating smart contracts in contract directory.

In order to compile it we have to run - truffle compile compiling all contracts.

-truffle develop bring up the developer chain giving local ethereum nodes.

Next step is executing migration files by - truffle migrate command connecting to local instance and deploying contacts to it.
The whole process can be divided or separated and thus summarized into following 4 steps only.

step 1. Installation and Contract Creation using Truffle

step 2. Migrations and Deployment using truffle

step 3. Testing using Truffle

step 4. Deploying to Testnet and Mainnet using Truffle
