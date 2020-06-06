# supplychain
supplychain project

This Supply chain project follows ERC 721 standards and ethereum best coding Practices.

You can compile this project using online ethereum ide ie. Remix.

OR

You can use Ganache, Ganache is a simple tool that creates a local Ethereum network and you can connect to it just like you would with the main network. It also provides you with 10 accounts with 100 ether every time you run it.

Now that we have our network we need to be able to test and deploy our contracts to it. This is accomplished by another tool called Truffle, part of the same development suite as Ganache.

We will use Truffle to prepare our project structure, so run truffle init and check the folder structure that is created:
ethereum-supply-chain|-contracts| — Migrations.sol|-migrations| — 1_initial_migration.js|-testtruffle-config.js

Finally, we need to provide an interface to our users to let them interact with the Ethereum networks.
One of the options for this is to install Metamask, a browser plugin that manages wallets and also enables web systems to speak with the Ethereum networks.


How To Install Ganache and Truffle, follow these commands:-
1. npm install -g ganache-cli
2. Save the mnemonic to use later. Whenever you need to run Ganache again you can preserve the same accounts providing the mnemonic with the -m parameter:
ganache-cli -m "now frame tenant chronic oven cube minute immune leaf clock demand volume"
3. npm install -g truffle
ethereum-supply-chain|-contracts| — Migrations.sol|-migrations| — 1_initial_migration.js|-testtruffle-config.js
