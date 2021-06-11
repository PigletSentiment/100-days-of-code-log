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

## 1. Ethereum Developer Course


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
