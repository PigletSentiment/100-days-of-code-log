<!-- markdownlint-disable MD022 MD032 -->

# Andrew Park

## 100 Days Of Code

| Log 1 | Log 2 | Log 3 | Log 4 | Log 5 |
| --- | --- | --- | --- | --- |
| this log | 

## Challenge & Commitment
This is part of Alexander Kallaway's [100DaysOfCode](https://github.com/Kallaway/100-days-of-code "the official repo") challenge. More details about the challenge can be found here: [100daysofcode.com](http://100daysofcode.com/ "100daysofcode.com").

**Commitment:** *I will code daily OR learn crypto daily for the next 100 days.*

|  Start Date   | End Date     |
| ------------- | ------------ |
| June 1, 2021 | September 9, 2021 |

## Goals

- [x] Code daily OR learn crypto daily
- [x] Expand blockchain and/or crypto knowledge
- [x] Complete as many courses, classes, challenges, & certifications as possible
- [x] Get established in Twitter dev community
  - Use [#100DaysOfCode](https://twitter.com/search?q=%23100DaysOfCode&src=tyah) hashtag.

### Secondary Goals & Resources

# Code Log
<!--
## 1.
### Day 1: date - day

**Project:**

**Progress:**

**Thoughts:**

**Link to Work:**
-->

---
### Day 35:  July 8, 2021
Ethereum Developer certificate exam prep continues.  Completed chapters 6 and 7. Getting pretty high scores but need to improve on Solidity knowledge.


### Day 34:  July 7, 2021
Ethereum Developer certificate exam prep continues.  Completed chapters 3, 4 and 5.  I got 100% for chapters 3 and 5 but only 77% for chapter 4.
Only 3 more chapters to go before the exam but the last 3 are the hardest.

### Day 33:  July 6, 2021
I have decided that I am going to be writing the "Ethereum Developer certificate" exam.  It'll require for me to complete the quizzes and write practice exams.
For today I have completed "Chapter 2: Ethereum Nodes and Networks" and got 12/15 in the practice exam.  This will continue until I write and complete the certification exam.


### Day 32:  July 5, 2021
I had a few days off for being sick after the vaccination and then went on a mini vacation over the long weekend.
I am back and continuing right where I left off.
Today I decided to study XLM (Stellar lumen).  Basically Stellar is a permissionless blockchain network with its own consensus mechanism (Stellar Consensus Protocol), which performs faster than Bitcoin and Ethereum.
Essentially with Stellar, one is meant to digitally represent fiat money (be it, USD, CDN, Pesos etc). The digital currency can be withdrawn into actual cash by the end users any time.
Lumen (XLM) is a digital currency native to Stellar blockchain.  It is compatible to Ethereum's gas where it is in place to prove stake in the Stellar network.

One question I have is if Stellar is meant to represent fiat money, how come there is fluctuation in (let's say) USD in Stellar?

At this point, there are more questions than answers.  I may have to dive deep to understand better.


### Day 27: June 27, 2021
**Today's Learning:**
- Returned to the Truffle tutorial (Pet shop) and continued the troubleshoot session to determine why the code was not working
- on line 28, within the initWeb3 function, I had specified `App.web3Provide` instead of `App.web3Provider` (missed "r" at the end).
- With the typo above, the web injection provider would not have been configured properly and thus the transactions were not being handled.
- Started studying for the Ethereum developer certificate - the study process will further reveal what I do not understand about Ethereum and crypto in geenral

### Day 26: June 26, 2021
**Today's Learning:**
- Researched into Corda and XDC
  - I always thought Corda was a token but it refers to a Decentralized Finance product
  - Corda is a permissioned shared ledger protocol which started looking like a permissioned blockchain but due to various limitations of the blockchains (i.e. lack of privacy of transactions) decided to become more of inter organization messaging protocol.
  - In fact, Corda does not want to be another blockchain DApp
  - One of the key differentiators is that the transactions do not need to be approved by the majority in the chain but smart contract agreement between the involved parties is achieved, the transactioin is approved
  - Corda is for the financial industry and various financial organizations participate in it.
  - XDC is the Cordite community's token
  - Corda is at version 4 now and comes with fully open sourced SDK, libraries and other codes necessary to develop applications or run nodes

### Day 24 and 25: June 24-25, 2021
**Today's Learning:**
- added frontend code for the pet shop tutorial I have been takin
  - latest code [here](https://bit.ly/2SqBzku)
  - it seems like there is a bug since when I click "Adopt" nothing happens.
  - I need to add debug code to dive deep but thus far, I got to use truffle suite extensively as well as connecting Ganache, Metamask and frontend code altogether.  This has been extremely beneficial.

### Day 23: June 23, 2021
**Today's Learning:**
- Started the pet shop tutorial project available from Truffle (https://www.trufflesuite.com/tutorial)
  - Installed Truffle suite on my local machine
  - Started using my own IDE (PyCharm) and command line commands to start compiling and deploying the smart contracts
  - Learned how to write test cases using truffles Assert.sol functions
  - Wrote 3 test cases but I saw that the number of cases go from 4 to 26 just based on those test cases.  I need to understand why so many transactions were needed to give results.
  - my pet shop project code is [here](https://github.com/PigletSentiment/100-days-of-code-code/tree/main/pet-shop-tutorial)

### Day 22: June 22, 2021
**Today's Learning:**
- Researched into a couple of Crypto Coins: XRP and Tether (i.e. stablecoin)
  - Tether boasts that its coin is 100% backed by fiat currency which turned out to be a lie. A recent audit revealed that only 2.5% of the coin were covered with cash and roughly 65% was covered by commercial paper.  Tether is owned by Bitfinex who was alledgedly participated in price manipulation.
  - XRP advertises that it can settle global transfer of funds within seconds.  It also boasts that it operates permissionless and distributed blockchain but that claim is misleading.  In order to participate in the chain, one must "apply" and receive approval but apparently the participants are big financial corporations. Since it operates more like permissioned blockchain, it does not need miners and may not necessarily have enough visibility into the transactions.
- Going forward, once a week, I will be dedicating my session for researching into the crypto coins. I need to know the differentiating features.

### Day 21: June 21, 2021
**Today's Learning:**
- Moved on with the rest of the lab and it seems like my previous coin deployment succeeded. I see them in my wallet
- learned to create ERC 721 (Non Fungible Token - NFT) contracts
  - deployed a sample contract in Ropsten network [contract URL here](https://ropsten.etherscan.io/address/0x326cb560bf059ab88fb5b6e9ac6657c15d83b602)
  - added a sample image URL onto the contract [transaction here](https://ropsten.etherscan.io/tx/0x601ba337bfeebfb8c33e2350f7d509ccf789afd2dfc5199470f708f200703e7c)
- Did an additional which goes through contract development using truffle suite.  Currently, learning how to write unit testing.

### Day 20: June 20, 2021
**Today's Learning:**
- trying to troubleshoot the default balance that ends up in my wallet when I create a new coin
- re-traced the steps to try re-create the coin under a different name.  Now I am getting this error:
```text
Compiler debug log:
Error! Unable to generate Contract ByteCode and ABI
Found the following ContractName(s) in source code : ERC20Interface, MyToken, SafeMath
But we were unable to locate a matching bytecode (err_code_2)
For troubleshooting, you can try compiling your source code with the Remix - Solidity IDE and check for exceptions
```
- planning on spending day time brain tomorrow.  if I cannot figure it out then, I will move on but will create a support ticket.

### Day 19: June 19, 2021
**Today's Learning:**
- Completed lab 10 and created my Ethereum derivative (ERC20 compatible) coin called LKM (lowKickCoin)
  - coin contract address is https://ropsten.etherscan.io/address/0x7a9b48dae529a530a1997d39f58e6a8eb1f23551#code
  - source code is also found in above URL as well
- The only issue is that I am supposed to get 100000000 LKC upon adding to my wallet but I currently get 0.
- I might have to repeat the lab until I really understand it.  For now, it should be noted that below functions MUST be in place for the coin to be ERC-20mcompatible
  - **totalSupply** Returns the total supply of the token created.
  - **balanceOf** Returns the token balance for the supplied address 
  - **transfer** Allows the contract owner to give tokens to other users.
  - **transferFrom** This function is used to support automated transfers to a specific account.
  - **approve** This function checks the transaction against the total supply of tokens to make sure that there are none missing or extra.
  - **allowance** This function will cancel a transction if the user does not have sufficient balance

### Day 18: June 18, 2021
**Today's Learning:**
- my remix and metamask problem is finally figured out  
  - when working with metamask plugin, remember to allow popup windows
  - also exit from full browser window - this hid the popup window that supposedly appeared
  - the popup window from metamask is a confirmation window.  The confirm button must be pressed otherwise, the transaction will not proceed.
- completed lab 9 and there was not much to it.  Ensure that I am logged into metamask then in the remix choose "inject web3" option.  A popup window will ask for confirmation.
  - if I have any Ethereum then I am able to create transactions  It may take a while but eventually it comes back and from the metamask window I can even open the etherscan page showing the transaction.

### Day 17: June 17, 2021
**Today's Learning:**
- Lab 9 was ruined.  I was asked to work with metamask to deploy into the Ropsten network but for whatever reason my remix will not connect to the metamask. Need to troubleshoot further.

### Day 16: June 16, 2021
**Today's Learning:**
- completed lab 8
  - learned inheritance where one contract inherits features from another
  - Album contract now inherits from Utility contract
- during the testing, I ran into "out of gas" error.  Nothing is more confusing than that error message. I had plenty of gas but it is just that user's favourite album information had not been initialized
  - the workaround is to initialize the information right after the deployment via remix
  - after that the web interface works like a charm
- Today's code:
  - https://github.com/PigletSentiment/100-days-of-code-code/tree/main/MyAlbumApplication-nodejs
  - https://github.com/PigletSentiment/100-days-of-code-code/commit/e8ce7e77797a6df0d74b60dea4caa07bb6e16a3c

### Day 15: June 15, 2021
**Today's Learning:**
- I had to troubleshoot and fix yesterday's error message. `Error: Returned error: VM Exception while processing transaction: revert`
  - There was a discrepancy between the mapping hash I created in the remix (smart contract) and the UI code.
  - While I defined userAlbums in the smart contract, I used the variable userAlbum (without the trailing "s") in the UI code
- The code still generated errors and eventually I had to change the compiler to 0.8.4 from 0.7.6 which compiled successfully and also got rid of the other errors.
- Just read up on gas price and gas limit.  Found this definition to be helpful:
  `The Gas Limit is the maximum amount of Gas that a user is willing to pay for performing this action or confirming a transaction (a minimum of 21,000). The price of Gas (Gas Price) is the amount of Gwei that the user is willing to spend on each unit of Gas.`
- For the record, one gwei is equal to one billion wei

### Day 14: June 14, 2021
**Today's Learning:**
- completed lab 7
  - learned about `struct` and `mapping` in Solidity
  - I introduced a bug .. I am getting `Error: Returned error: VM Exception while processing transaction: revert`
  - I checked the code several times but no luck. Hoping to resolve this before tomorrow.

### Day 13: June 13, 2021
**Today's Learning:**
Too tired to be coding thus resorted to reading more about the details of Ethereum.
In addition to developing decentralized applications, I am trying to learn technical details of crypto coin implementations so this type of detailed reading helps.
Today's reading:
EVM: https://ethereum.org/en/developers/docs/evm/
Blocks: https://ethereum.org/en/developers/docs/blocks/

### Day 12: June 12, 2021

**Today's Learning:**
Finished Lab 6 - function modifiers and error catching
- Learned about function modifiers whose job is to some sanity checking and allow the function to go on if everything passes
- Fairly limited function in that the only action it can take is execute the attached function or interrupt
- The keyword in Solidity is `modifier`
- There can be multiple modifiers in multiple functions. If multiple, the modifiers get executed in sequence
- Error handling is just like event handling (i.e. catching error event)
  - `event errorEvent(string errorEvent_Description);`
  - `emit` is used to "send" th error
- then in the UI, simply write the handler
  - `albumContract.events.errorEvent(function(error,result){});`

### Day 11: June 11, 2021

**Today's Learning:**
Finished lab 5 - Events
- In the smart contracts, events can be defined and raised. Raising of the events can be anywhere in the smart contracts but just have to serve purpose.  In today's lab, we were raising events for setting new album information and we used the raised events to display information in the user facing interface.
  These are done in remix IDE:
  - When defining an event, we use following syntax:
    <pre>
    event eventName(<em>parameters passed to the event listener</em>);
    </pre>
  - where _event_ is the keyword; _eventName_ is any meaningful name given to the event;
  - whenever the code wishes to _*raise*_ an event, keyword _emit_ is used
    <pre>
    emit eventName(_value1, _value2, _value3);
    </pre>
- These are done in UI code (i.e. index.html)
  - new ABI (application binary interface) must be defined after an event has been defined
  - a listener must be created and function to handle the emitted event.  It'll look something like this:
    <pre>
    albumContract.events.eventName(function(error, result) {
      if (!error) {
        $("#loader").hide();
          $("#album").html('The current album is ' + result.returnValues.albumEvent_Title + ' by ' + result.returnValues.albumEvent_Artist + '.<br/> It contains ' + result.returnValues.albumEvent_Tracks + ' tracks.');
        } else {
          $("#loader").hide();
          console.log(error);
      }
    });
    </pre>
- The usual applies ... after the remix code update, the code must be compiled and deployed
- During the deployment, running environment must be chosen and with the event emitting, only the web socket protocol is supported thus I had to go with the Ganache created local environment
- After the deployment, code update to the UI and a refresh were needed to show the new UI functionality

### Day 10: June 10, 2021

**Today's Learning:**
As logged yesterday, I wanted to take a breather from the course to focus on some of the key concepts and underlying reasoning.
I always wondered why "mining" was required in Crypto (just focusing on BTC and ETH for now).

The mining activity is needed to deter easy manipulation of the whole blockchain.  If it does not involve a form of labour through which the right to write the block, it is too easy for an attacker to "bully" the chain.
Therefore the sensible way to deter such bullying is to ask for "Proof of Work" which is obtained through "mining" process which tries to come up with a "nonce" whose presence results in a number of leading zeroes in the hash.

The following explains things rather well.
https://assets.ctfassets.net/sdlntm3tthp6/5CbV1gD3NuCCkKauWug6aU/b24fcd5fa2a5cd4a0c32e7dd90838c8a/A-Gentle-Introduction-To-Bitcoin-Mining-WEB.pdf

https://bitcoin.stackexchange.com/questions/8031/what-are-bitcoin-miners-really-solving

It appears that block size and the number of transactions in it varies every day.  

Just trying to get my head around these key concepts.


### Day 9: June 9, 2021
**Today's Learning:**

- BTA's [Ethereum Developer Training on demand](https://blockchaintrainingalliance.com/products/ethereum-developer-training-on-demand) course
  - labs

**Progress:**
- Lab 3 and 4 completed
- Created an account on infura.io and started a new project
  - So that I can my project on a Ethereum test net via the node provided by infura
  - With the API reference guide, I was able to write an extremely short python code for getting my balance from MetaMask.
  ```
  from web3 import Web3
  w3 = Web3(Web3.HTTPProvider("https://ropsten.infura.io/v3/0f483572710449d88734c7afd9------"))
  print(w3.eth.get_balance('0x831C8D503De618774695810a829e90f9f0------'))
  ```
  this returned the following result:
```1999979000000000000```
  
- the API reference document for python: https://web3py.readthedocs.io/en/stable/providers.html

- additionally, I got to download and use Ganache. It is a blockchain simulator which runs locally.
  - After the setup, I had to point my smart contract that I created using remix needed to be pointed to the simulated environment
  - After the deployment, the lab provided code for UI which interfaced with the simulated blockchain and I was able to view the information in the UI
    
Tomorrow, I am planning on revisiting the concepts and lectures to ensure that I really understand the technology.

### Day 8: June 8, 2021
**Today's Learning:**

- BTA's [Ethereum Developer Training on demand](https://blockchaintrainingalliance.com/products/ethereum-developer-training-on-demand) course
  - labs 
  
**Progress:**
- Lab 2 completed
  - Experimented with Metamask (online wallet)
  - In one of the Ethereum test net, I received a few eth coins and practiced transferring it to another wallet kept in Metamask
  - Used Etherscan to publicly audit the transactions to and from my wallets

### Day 7: June 7, 2021
**Today's Learning:**

- BTA's [Ethereum Developer Training on demand](https://blockchaintrainingalliance.com/products/ethereum-developer-training-on-demand) course

**Progress:**
- Ethereum is terrible for large storage

 Thus IPFS / Swarm
  - peer to peer
  - file content == hash
  - content based addressing and not location based
  - zero-down time
  - in this context Eth only stores pointer to data
    - IPFS/Swarm hosts large files
  - ipfs.io - A peer-to-peer hypermedia protocol

- Eth 2.0 upgrade
  - ice age is not considered any more
  - three phase approach instead
    - phase 1: A beacon chain network is introduced
    - phase 2: New Shard Chains is added to the beacon chain
      - 64 new shards using PoS consensus
      - basically creating subnets
    - phase 3: the docking
      - PoW network will merge with the 64 PoS shards
      - PoW will remain PoW

- additional lab work: 
  - Solidity reference library: https://docs.soliditylang.org/en/v0.4.21/contracts.html
  - learned about functions and function returns
  ```
    function getAlbum() public view returns (string memory, string memory, uint) {
        return (artist, albumTitle, tracks);
    }
    
    function setAlbum(string memory _artist, string memory _albumTitle, uint _tracks) public {
        artist = _artist;
        albumTitle = _albumTitle;
        tracks = _tracks;
    }
  ```
  `view` keyword is used to promise that the state will not change

### Day 6: June 6, 2021
**Today's Learning:**

- BTA's [Ethereum Developer Training on demand](https://blockchaintrainingalliance.com/products/ethereum-developer-training-on-demand) course

**Progress:**
- After creating a support ticket with the BTA, I discovered that I can just go ahead with the labs on my own.
- Created the first Solidy code using remix.  Following is my first code
```
// SPDX-License-Identifier: CC-By-1.0
// Creative Commons Attribution 1.0 Generic

pragma solidity ^0.7.0;

contract Album {
string public artist;
string public albumTitle;
uint public tracks;
string public constant contractAuthor = 'Andrew Park';

    constructor() {
        artist = 'Nirvana';
        albumTitle = 'Nevermind';
        tracks = 13;
    }
} // Album
```

- In addition to the Solidity code, I have been reading up on the following
  - https://bitsonblocks.net/2016/10/02/gentle-introduction-ethereum/
  - https://bitsonblocks.net/2015/09/01/gentle-introduction-bitcoin/
  - https://bitsonblocks.net/2015/09/09/gentle-introduction-blockchain-technology/
- The last two are recommended pre-readings for the first one.ddi




### Day 5: June 5, 2021
**Today's Learning:**

- BTA's [Ethereum Developer Training on demand](https://blockchaintrainingalliance.com/products/ethereum-developer-training-on-demand) course

**Progress:**
- Learn about the truffle frameworks https://www.trufflesuite.com/
- the framework is really for smart contract development and testing
- it offers unit testing feature where the syntax resembles mochachai
- A couple of resources that can help
  - Truffles petshop (step by step guide to setting up and run project - tutorial)
  - truffle boxes - mostly templates
- Additional reading I must complete
  - https://consensys.github.io/smart-contract-best-practices/known_attacks/
  - https://ethereum.org/en/developers/docs/smart-contracts/
  - https://ethereum.org/en/developers/docs/accounts/
  - https://ethereum.org/en/developers/docs/transactions/
  - https://ethereum.org/en/developers/docs/evm/
- I am getting closer to lab time .. but not yet, it seems ...

### Day 4: June 4, 2021
**Today's Learning:**

- BTA's [Ethereum Developer Training on demand](https://blockchaintrainingalliance.com/products/ethereum-developer-training-on-demand) course

**Progress:**
- Since I am not getting much out of the lectiures of BTA's course (this guy just talks - not much visuals, not much demos, just talks...) I have done some Googling to make more sense of lectures.
- I wanted to see the internals of an Ethereum block, I found some resources from ethereum.org
  
  https://ethereum.org/en/developers/docs/blocks/
  
  https://www.youtube.com/watch?v=_160oMzblY8&t=15s

  These were much more useful than the talkative and not so productive BTA course.
- **Still hoping to get to the coding or building portion of the course**
- **Is this guy for real?? Kris Bennett - Chief Learning Officer has been talking over 50% of the course.  He keeps on saying it'll make more sense when we get into the labs but WHEN???! if we are not getting into it any time soon just don't say it!  I am getting so update listening to this guy talk for hours**

### Day 3: June 3, 2021
**Today's Learning:**

- BTA's [Ethereum Developer Training on demand](https://blockchaintrainingalliance.com/products/ethereum-developer-training-on-demand) course

**Progress:**
- Learned that one of the most considerations for blockchain design is
  - Public or Private
  - Open or Closed
  - permissioned or permissionless?
- uses cases for Hyperledger vs Ethereum
- the instructor touched on the Ethereum tooling infrastructure
  - I need to be connected to a node to access the rest of nodes
  - I can run my own local node https://ethereum.org/en/developers/docs/nodes-and-clients/
  - or I can connect to an externally hosted node such as infura https://nimbus.guide/infura-guide.html
    
 
- **Hoping to get to the coding or building portion of the course**
- **The instructor of the on-demand course keeps talking about the lab and the hands-on portion of the course but after 41% of the court, I still don't even see the sections**

### Day 2: June 2, 2021
**Today's Learning:**

- BTA's [Ethereum Developer Training on demand](https://blockchaintrainingalliance.com/products/ethereum-developer-training-on-demand) course

**Progress:**
- Ether source code repos: https://github.com/ethereum
- Ethereum network
  - Live network (main net) == ID 1
  - Test net = ID 2 (retired) and 3 and 4 (Rinkeby)
  - Beyond 4 is ... private instances of ethereum
    - assigned

- **Hoping to get to the coding or building portion of the course**
- **Also hoping to write and pass the certificate exam at the end of the course**

### Day 1: June 1, 2021

**Today's Learning:**

- BTA's [Ethereum Developer Training on demand](https://blockchaintrainingalliance.com/products/ethereum-developer-training-on-demand) course

**Progress:**
- Complete the intro and chapter 1 (Blockchain basics)
I will upload code as soon as exercises are introduced.  Until then I will create the summary of the lecture.
Today was just an introduction to Blockchain - what is it, when did it start and the origin.
---

## Pre-launch - GitHub, Twitter & BTA
### Day 0: June 1, 2021

**Today's Project(s):**

- GitHub profile
- Twitter account
- BTA (Blockchain Alliance) course sign up (Ethereum developer)

**Progress:**  Prep work...

- Setup
  - Forked the Official [100-days-of-code GitHub Repo](https://github.com/Kallaway/100-days-of-code "Official #100DaysOfCode GitHub Repo")
  - Updated [my GitHub profile](https://github.com/awsandrewpark "Andrew Park on GitHub") (@awsandrewpark)
  - Got [my Twitter account](https://twitter.com/PigletSentiment "Sentiment Piglet on Twitter") going (@pigletsentiment)
- Tweet'd my commitment to the 100-days-of-code challenge

**Link to work:**

- My GitHub [100-days-of-code-log](https://github.com/awsandrewpark/100-days-of-code-log "this repo")

**Thoughts:** Glad to be starting this.
