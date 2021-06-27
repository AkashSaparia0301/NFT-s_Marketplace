NFT based Ticket MarketPlace
【Introduction of NFT based Ticket MarketPlace】
NFT based Ticket MarketPlace is the peer-to-peer Marketplace for buy and sell of Tickets which was uploaded by users.
It assume that uploaded Tickets in this marketplace are used as Tickets of news article.
Even if user has smartphone which include function of camera, anyone can become sellers by uploading Tickets in this MarketPlace.
It mean that if user who is seller live in poor region and doesn't has bank account and so on, they can earn money by selling Tickets in this marketplace.
All of being uploaded Tickets are tokenized as NFT（Non-Fungible token).
Uploaded Tickets buy/sell by using DAI for preventing risk of high volatility of crypto currency.
 

【Setup】
Setup private network by using Ganache-CLI
Download Ganache-CLI from link below
https://www.trufflesuite.com/ganache

Execute Ganache

$ ganache-cli -d
※ -d option is the option in order to be able to use same address on Ganache-CLI every time.

 

Setup wallet by using Metamask
Add MetaMask to browser (Chrome or FireFox or Opera or Brave)
https://metamask.io/

Adjust appropriate newwork below

http://127.0.0.1:8545
 

Setup backend
Deploy contracts to private network of Ganache
(root directory)

$ npm run migrate:local
 

Setup frontend
NPM modules install
$ cd client
$ npm install
Execute command below in root directory.
$ cd ..
$ npm run client
Access to browser by using link
http://127.0.0.1:3000
