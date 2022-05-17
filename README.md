# REAL / FAKE PRODUCT IDENTIFIER DAPP!

DESCRIPTION-
The Real/Fake Product Identifier is a Decentralized Application which will help to distinguish between the original product and the fake product using Ethereum based Blockchain Technology.The use of Blockchain Technology make the project more robust and secure as compared to the previous anti-counterfeiting software. The manufacturer will add a QR Code while manufacturing the product. The product details and all the information are stored in blocks in Blockchain Network. The consumer who buys the product will scan the QR Code using application which will provide product's information as it will search the scanned QR Code in the Blockchain Database entries. If the product is original, it will provide all the details, otherwise, it will indicate that the product is fake as there is no entry in the database regarding the product.

INSTRUCTIONS-
1) Download and install Ganache.
2) 2) Download and install Xamppserver on windows or MAMP on MacOS X.
3) Download and install Google Chrome (in case you don't have it already). Go to the Chrome store and download Metamask 
4) Create a Metamask account. 
5) Run Ganache. 
6) In Metamask, select Networks > Custom RPC.
7) Give any name to the network. 
8) Copy RPC Server URL from Ganache (It should probably be HTTP://127.0.0.1:7545 but please check) 
9) Go to Metamask > Accounts > Import Account. 
10) Open Ganache, go to the Accounts tab, click on the key icon on the right side for an account and copy the private key. 
11) Paste this key in the Metamask import account section. 
12) Copy the smartcontract.sol from this repo and paste it into RemixIDE code section.
13) Save it, go to compile tab and compile the code. 
14) Go to the deploy tab, select Environment as 'Injected Web3' then Click deploy.
15) Copy the contract address and paste it into the app.js file. 
16) Copy the contract ABI from compile tab and paste it into the app.js file. 
