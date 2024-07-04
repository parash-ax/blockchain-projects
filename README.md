# blockchain-projects

This repository contains a basic implementation of a blockchain in Python. The blockchain includes features such as block creation, transaction recording, proof-of-work consensus, and block validation.

## Features

- **Block Structure**: Each block contains an index, timestamp, list of transactions, proof (for mining), and the hash of the previous block.
- **Blockchain Initialization**: The blockchain starts with a genesis block.
- **New Block Creation**: Blocks are added to the chain with a proof-of-work algorithm.
- **Transactions**: Transactions are recorded in blocks, acting as a ledger for exchanges.
- **Proof-of-Work**: A basic proof-of-work algorithm secures the blockchain and adds new blocks.
- **Hashing**: SHA-256 hashing ensures the integrity and immutability of each block.
- **Chain Validation**: The blockchain can be validated by checking hashes and proofs of each block.

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/parash-ax/blockchain-project.git
   cd blockchain-project
