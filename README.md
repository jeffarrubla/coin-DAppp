# Coin DApp

Built a money transaction application with a minter who can create money to other accounts, and which they can transfer money to other accounts in the network.

<small> The smart contract used is based on the example in solidity docs </small>

## Prerequisite
1. NodeJs
2. Metamask (3.14.1)
3. Truffle (v4.0.4)

## Instruction for truffle testing
1. Clone the repository to a local folder
2. Go to the cloned folder using command line
3. Execute truffle compile
4. Open a new command line and execute truffle develop to start the blockchain network
5. In the old terminal execute truffle migrate --reset
6. Execute truffle test

## Instruction for DApp

1. Now to start the nodeJs server execute npm run dev
2. This should start the front end of the application at localhost:3000
3. Open Metamask in your chrome browser and enter the key phrase you got after executing truffle develop
4. Now connect to private network using http://127.0.0.1:9545
5. Check the owner contract balance must be 0.
6. Mint some coins for the owner contract account.
7. Check the owner contract balance it must be the value you entered.
8. Send money to the accounts you want from the owner account you should see a message (event) telling you from which account to which accout the money was sent and the balance.
