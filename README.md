# Basic Sample Hardhat Project
from https://dev.to/dabit3/the-complete-guide-to-full-stack-ethereum-development-3j13

building, deploying, and connecting to a couple of basic smart contracts:

1. A contract for creating and updating a message on the Ethereum blockchain
2. A contract for minting tokens, then allowing the owner of the contract to send tokens to others and to read the token balances, and for owners of the new tokens to also send them to others.


To run the project:

```shell
npm start
npx hardhat compile
npx hardhat node
npx hardhat run scripts/deploy --network localhost
```
