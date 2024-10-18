<h1 align=center>
<img src="https://github.com/yusufb026/Integration-of-NFT-marketplace/blob/main/src/img/logo.png" />
</h1>

<div align="center">
  
![License](https://img.shields.io/badge/license-MIT-737CA1?style=flat-square) 
![Node_Badge](https://img.shields.io/badge/node-20.15.0-green?style=flat-square)
![React Badge](https://img.shields.io/badge/React-17.0.2-45b8d8?style=flat-square)
![Solidity_Badge](https://img.shields.io/badge/Solidity-%5E8.0.0-yellow?style=flat-square)
![Truffle](https://img.shields.io/badge/Truffle-5.3.14-F0E8E0?style=flat-square)
![Made by Mythik](https://img.shields.io/badge/made%20by-Mythik-pink?style=flat-square)
</div>

# Summary

- [About](#about)
- [Preview](#preview)
- [Architecture of the Project](#architecture)
- [Features](#feature)
- [Based On](#technologies)
- [How to Run](#how-to-run)
- [TODO](#todo)
- [License](#license)

<a id='about'/>

## About

Mythik is a gaming NFT marketplace where you can create, sell, and purchase digital art as NFTs.
This allows users to purchase game items as collectibles to use as weapons to complete tasks, or sell them to other users in-game and on other NFT marketplaces.
Mythik aims to be a one-stop hub for gaming collectibles on the Ethereum Smart Chain.
You can list your ETH-based game NFTs on our marketplace and sell them to other users.


<a id='preview' />

## Preview

<p align="center">
  <img alt="landpage" src="https://github.com/yusufb026/Integration-of-NFT-marketplace/blob/main/src/img/Demo_platform.png">
<p />

<a id='architecture' />

## Architecture of the Project

<p align="center">
  <img alt="Frontend-Flow" src="https://github.com/yusufb026/Integration-of-NFT-marketplace/blob/main/src/img/frontend%20Arch.png">
<p />
<p align="center">
  <img alt="Backend-Flow" src="https://github.com/yusufb026/Integration-of-NFT-marketplace/blob/main/src/img/backend_Arch.png">
<p />

<a id='feature' />

## Feature

- [Opportunity to create the Wish List of NFT and NFT collections] <br>
- [Opportunity to swap NFT collections (Multichain)] <br>
- [Opportunity to create counteroffers for the current propositions] <br>
- [Swapping opportunities for searching and filtering] <br>
- [Opportunity to add tokens to the swapping deals] <br>
- [Opportunity for the automatic matching with other NFTs on NFT marketplaces] <br>
- [Support of other standards (ERC20, ERC1155)] <br>
- [A notification system based on EPNS]

<a id='technologies'/>

## Based On

This platform was developed with the following technologies:

#### **Frontend** <sub><sup>React + JavaScript</sup></sub>
  - [React](https://pt-br.reactjs.org/)
  - [Axios](https://github.com/axios/axios)
  - [Redux](https://redux.js.org/)
  - [Web3.js](https://web3js.readthedocs.io/en/v1.3.4/)

#### **Backend** <sub><sup>Express</sup></sub>
  - [Node](https://nodejs.org/en/download/prebuilt-installer/pt-br/)
 
#### **Blockchain and Smart Contracts** <sub><sup>Solidity</sup></sub>
  - [Solidity](https://docs.soliditylang.org/)
  - [Truffle](https://www.trufflesuite.com/)
  - [Ganache](https://www.trufflesuite.com/ganache)

<a id='how-to-run'/>

##  How to Run

### Requirements

To run the application you'll need:
* [Git](https://git-scm.com)
* [Node](https://nodejs.org/)
* [VScode](https://code.visualstudio.com/download)
* Clone the repository:
  * ```$ git clone https://github.com/AlexiaYuriko24/Coin-Marketplace.git ``` or ```download the zip file```

Now go to project folder and run:
```bash
$ cd NFT_Marketplace

$ npm install
$ npm run
```

<a id='todo'/>

## TODO

There are some things to be done in the project:
 - Add any Phantom wallet excluding MetaMask to your project.
 - Modify frontend calls to the blockchain's buy and sell functions.
 - Error handling.
 - Implement an NFT card function that reflects actual price information coming from the blockchain.


<a id='license'/>

## License

This project is under the **MIT license**. See the [LICENSE](https://github.com/AlexiaYuriko24/Coin-Marketplace/blob/main/LICENCE) for more information.

## Project Structure

```
Integration-of-NFT-marketplace/
├── .git/
│   ├── FETCH_HEAD
│   ├── HEAD
│   ├── config
│   ├── description
│   ├── hooks/
│   │   ├── applypatch-msg.sample
│   │   ├── commit-msg.sample
│   │   ├── fsmonitor-watchman.sample
│   │   ├── post-update.sample
│   │   ├── pre-applypatch.sample
│   │   ├── pre-commit.sample
│   │   ├── pre-merge-commit.sample
│   │   ├── pre-push.sample
│   │   ├── pre-rebase.sample
│   │   ├── pre-receive.sample
│   │   ├── prepare-commit-msg.sample
│   │   ├── push-to-checkout.sample
│   │   ├── sendemail-validate.sample
│   │   └── update.sample
│   ├── index
│   ├── info/
│   │   └── exclude
│   ├── logs/
│   │   ├── HEAD
│   │   └── refs/
│   │   │   ├── heads/
│   │   │   │   └── main
│   │   │   └── remotes/
│   │   │   │   └── origin/
│   │   │   │   │   └── HEAD
│   ├── objects/
│   │   ├── info/
│   │   └── pack/
│   │   │   ├── pack-ecec6871e7698a3adbba6c36ff00f29c24187fdf.idx
│   │   │   ├── pack-ecec6871e7698a3adbba6c36ff00f29c24187fdf.pack
│   │   │   └── pack-ecec6871e7698a3adbba6c36ff00f29c24187fdf.rev
│   ├── packed-refs
│   └── refs/
│          ├── heads/
│          │   └── main
│          ├── remotes/
│          │   └── origin/
│          │   │   └── HEAD
│          └── tags/
├── public/
│   ├── favicon-.ico
│   ├── favicon.ico
│   ├── img/
│   │   ├── 1.jpg
│   │   ├── 2.jpg
│   │   ├── 3.jpg
│   │   └── loading.gif
│   ├── index.html
│   ├── logo192.png
│   ├── logo512.png
│   ├── manifest.json
│   └── robots.txt
├── server/
│   ├── app.js
│   ├── config/
│   │   ├── config.env.example
│   │   └── database.js
│   ├── controllers/
│   │   ├── orderController.js
│   │   ├── paymentController.js
│   │   ├── productController.js
│   │   └── userController.js
│   ├── data/
│   │   ├── cart.json
│   │   ├── invoice/
│   │   │   ├── invoice-5f096ef911137b230cccbcde.pdf
│   │   │   ├── invoice-5f09c880622ce4371411fb65.pdf
│   │   │   ├── invoice-5f0da2c500b7001ab054bcaf.pdf
│   │   │   └── invoice-5f156c42e74db20a30e0b5b0.pdf
│   │   ├── products.json
│   │   └── util/
│   │   │   ├── fileDelete.js
│   │   │   └── path.js
│   ├── middlewares/
│   │   ├── common/
│   │   │   └── index.js
│   │   ├── helpers/
│   │   │   ├── asyncErrorHandler.js
│   │   │   ├── createNotification.js
│   │   │   ├── dbConnection.js
│   │   │   ├── dbErrorHandler.js
│   │   │   ├── error.js
│   │   │   ├── fileRemover.js
│   │   │   ├── geoDistance.js
│   │   │   ├── imageCompressor.js
│   │   │   ├── mailer.js
│   │   │   ├── multer.js
│   │   │   └── waterMarker.js
│   │   ├── user_actions/
│   │   │   ├── auth.js
│   │   │   ├── getRatingInfo.js
│   │   │   └── userHas.js
│   │   └── validator/
│   │   │   └── index.js
│   ├── models/
│   │   ├── Address.js
│   │   ├── Admin.js
│   │   ├── AdminBank.js
│   │   ├── AdminFiles.js
│   │   ├── AdminWarehouse.js
│   │   ├── Banner.js
│   │   ├── BusinessInfo.js
│   │   ├── Cart.js
│   │   ├── Category.js
│   │   ├── Dispatcher.js
│   │   ├── Districts.js
│   │   ├── Lead.js
│   │   ├── ManualOrder.js
│   │   ├── Notification.js
│   │   ├── Order.js
│   │   ├── Payment.js
│   │   ├── Product.js
│   │   ├── ProductBrand.js
│   │   ├── ProductImages.js
│   │   ├── QnA.js
│   │   ├── RefereshToken.js
│   │   ├── Remark.js
│   │   ├── Review.js
│   │   ├── SocketMapping.js
│   │   ├── SuggestKeywords.js
│   │   ├── User.js
│   │   ├── WishList.js
│   │   ├── minedProduct.js
│   │   ├── orderModel.js
│   │   ├── paymentModel.js
│   │   ├── productModel.js
│   │   └── userModel.js
│   ├── public/
│   │   ├── android-chrome-192x192.png
│   │   ├── css/
│   │   │   ├── auth.css
│   │   │   ├── cart.css
│   │   │   ├── forms.css
│   │   │   ├── main.css
│   │   │   ├── orders.css
│   │   │   └── product.css
│   │   └── js/
│   │   │   └── main.js
│   ├── routes/
│   │   ├── orderRoute.js
│   │   ├── paymentRoute.js
│   │   ├── productRoute.js
│   │   └── userRoute.js
│   ├── server.js
│   └── utils/
│   │   ├── apiFeatures.js
│   │   ├── errorHandler.js
│   │   ├── jwtToken.js
│   │   ├── searchFeatures.js
│   │   ├── sendEmail.js
│   │   └── sendToken.js
└── src/
│   ├── App.css
│   ├── App.js
│   ├── App.test.js
│   ├── ChainInfo.js
│   ├── contractabi.json
│   ├── fonts/
│   │   ├── Friz-Quadrata-Std-Regular.otf
│   │   ├── friz-quadrata-std-bold-587034a220f9f.otf
│   │   ├── friz-quadrata-std-bold-italic-587033d6d4298.otf
│   │   ├── friz-quadrata-std-italic-587033b2c95df.otf
│   │   └── friz-quadrata-std-medium-5870338ec7ef8.otf
│   ├── img/
│   │   ├── 1common.png
│   │   ├── 2uncommon.png
│   │   ├── 3rare.png
│   │   ├── 4epic.png
│   │   ├── 5legendary.png
│   │   ├── Adventurer.png
│   │   ├── Aetherborne.png
│   │   ├── Demo_platform.png
│   │   ├── Gemcutter.png
│   │   ├── Geomancer.png
│   │   ├── Grandmaster.png
│   │   ├── Savant.png
│   │   ├── Shaper.png
│   │   ├── Weaver.png
│   │   ├── adventurericon.png
│   │   ├── aetherborneicon.png
│   │   ├── aetherversebackground.png
│   │   ├── backend_Arch.png
│   │   ├── backgroundfullopacity.png
│   │   ├── bg-img.png
│   │   ├── blacklogo.png
│   │   ├── centerscroll.png
│   │   ├── character-back.png
│   │   ├── charactersheet.png
│   │   ├── charactersheet1.png
│   │   ├── charactersheet2.png
│   │   ├── charactersheet3.png
│   │   ├── classiconsquare.png
│   │   ├── connectwalletbutton.png
│   │   ├── craftingbackground.png
│   │   ├── crescent1.png
│   │   ├── crescent2.png
│   │   ├── darksword.png
│   │   ├── discord.png
│   │   ├── discord_mobile.png
│   │   ├── divider.png
│   │   ├── divider2.png
│   │   ├── favicon-16x16.png
│   │   ├── favicon-32x32.png
│   │   ├── firesword.png
│   │   ├── firesword1.png
│   │   ├── fireswordbg.png
│   │   ├── frontend Arch.png
│   │   ├── gemcuttericon.png
│   │   ├── geomancericon.png
│   │   ├── grandmastericon.png
│   │   ├── icesword.png
│   │   ├── instagram.png
│   │   ├── lastbg.png
│   │   ├── lightsword.png
│   │   ├── logo.png
│   │   ├── medium.png
│   │   ├── medium_mobile.png
│   │   ├── member1.png
│   │   ├── member2.png
│   │   ├── member3.png
│   │   ├── mintbackground.png
│   │   ├── mintbackground1.png
│   │   ├── mythiklogosmall.png
│   │   ├── portrait1.png
│   │   ├── reservebutton.png
│   │   ├── roadmapbg.png
│   │   ├── roughborder.png
│   │   ├── roughborder2.png
│   │   ├── savanticon.png
│   │   ├── shapericon.png
│   │   ├── star.png
│   │   ├── stars.png
│   │   ├── steelswordbg.png
│   │   ├── team-back.png
│   │   ├── twitter.png
│   │   ├── twitter_mobile.png
│   │   ├── vectorline-2.png
│   │   └── weavericon.png
│   ├── index.css
│   ├── index.js
│   ├── logo.svg
│   ├── pages/
│   │   ├── Loading.js
│   │   ├── character.js
│   │   ├── home.js
│   │   ├── marketplace.js
│   │   ├── myinventory.js
│   │   ├── navbar.js
│   │   └── whitepaper.js
│   ├── reportWebVitals.js
│   ├── setupTests.js
│   └── web3/
│      ├── ChainInfo.js
│      ├── WalletProvider.js
│      └── contractabi.json
├── .gitignore
├── LICENCE
├── README.md
├── git
├── package-lock.json
├── package.json
└── README.md
```

