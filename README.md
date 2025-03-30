## Java Blockchain Simulator

This is a simple blockchain simulator built in Java. It shows the core mechanics of a blockchain including, block mining, transaction tracking, and rewards to miners. This uses the SHA-256 hashing algorithm (same as Bitcoin). It allows you to adjust the difficulty of mining for each transaction. 

## Features
- Each block contains a single valid transaction
- Blocks are mined using proof-of-work with adjustable difficulty (leading zeros in the hash)
- Miners receive a reward for successfully mining a block
- Uses the SHA-256 hashing algorithm to create a 256 character hash
- Stores all user information (name, address, balance) in a hashmap
- Records the amount of successfully mined blocks by each miner and rewards for each success

## How It Works
- Blocks contain a sender, 

## Includes:
- A manual driver for custom transaction entry
- A demo runnter that processes 100 transactions (difficulty 3) displaying each transacion in the terminal

## Manual Driver:
The manual dirver is an interactive command line interface that allows users to interact with the blockchain.
- Sending money
- Creating wallets
- Viewing user Wallets
- Reconfiguring the blockchain
- Adding funds   
- Viewing the blockchain

On startup users choose a mining difficulty. This is the number of leading zeros required in the hash for a block to be considered valid. A higher difficulty takes more computing power but takes longer. Then the user can select from options depending on the desired operations.

Demo 
This simulates 100 transactions between 10 users at a difficulty of 5. Users are given an amount 10000-20000 and each transacion is 1-100 coins. There are 5 miners created who compete to find the nonce and successfully mine the block. Output in terminal shows the transaction progress. After 100 are complete transactions it displays the blockchain, miners, and users.

## Future Improvements
Add a feature to read and write transaction data from/to a file to load/store blockchain data
Allow multiple transactions to fit inside of one block
Add a non-local network system for multiple users at once

## License
MIT License

## Author
Kevin Ressler
