# Dream DAO "Learning Together" #5: All About Layer 2s

Date: January 29, 2022
Recording (Video): ../GMT20220129-153641_Recording_1920x1080.mp4
Host: QZ
Event type: Learning Together
POAP admin link: https://app.poap.xyz/admin/events/dream-dao-learning-together-5-all-about-layer-2s-2022

Icebreakers + Intros (5 mins)

![Untitled](Dream%20DAO%20Learning%20Together%20#5%20All%20About%20Layer%202s%202b307e1809a543bbab9e3c3a238e6acb/Untitled.png)

***PARTICIPATE FOR ATTENDANCE:** Type in your first and last name, favorite emoji to send friends, add a colon, and answer the prompt*

*Prompt: What is your favorite way to connect online?*

- QZ: Hop on a call
- Oliver Yehlik **⛅:** Sending giant walls of text between friends
- Charlotte Bruderly 🪴: Conversations on Discord or via text
- Chabu Kapumba 🤺: sharing playlists or FT
- Madison ☺️: Collaborating in any way synchronously (zoom, discord voice chat)- playing games, learning, etc
- Madhav 🤖: Collabing with people and arguing whose code is better(even though everyone knows its mine)
- Thessy Mehrain🥳 , working on content together such as with figma
- Arman 🗺️: Conversations on WhatsApp, Discord, Zoom, virtually everywhere possible, Sharing recipes and hitting people (with bricks, jk) randomly
- Jae-Hee 🦧: giant thought bricks analyzing studio ghibli movies
- Aditya Dahiya 🕸️3️⃣: Discord and Zoom
- Jason UwU: Twitter + Gaming
- Gary 🙏: watching youtube videos together
- Amanda 😎: whatsapp (I like when ppl tell me about their days as if I was a diary)
- Ale : 1:1 zooms
- Mirna🤩: WhatsApp and Instagram dms
- Aishah 🌺: Conversations on Whatsapp and Telegram
- Joshua S. Cruz ✌🏻: zoom + discord/Ig
- Ahyun :) : zoom calls + discord messages!

## L2s

[Initial research](https://hackmd.io/2OIXruKLSCiOMQzt3qMn1w#Starkware-Amanda-Maritan9027)

**Objectives of session:**

- ELI5 of layer 2s and their different types
- Try out a Layer 2 on testnet.
- Get a sense of what kind of L2 would be best to launch DreamDAO on

# What is a Layer 2? (20 minutes) - Jae-Hee

[https://www.youtube.com/watch?v=d7ulxd3R97E](https://www.youtube.com/watch?v=d7ulxd3R97E)

When it comes to adding blocks quickly to the chain, Ethereum has its boundaries. 

- specifically, the maximum throughput limitation is about 15-20 transactions per second (TPS)
- this is because of the block gas limit of 30 million gas and the competitive nature of block creation

### The Problem: As Ethereum began hosting thousands of DApps...

***TPS speed limit*** 🏃 ***→***  ***slow transaction processing/higher fees*** 🚦 ***→***  ***scalability issue!*** ⛔

## The Solution: This is where Layer 2 (L2) steps in!

**What is Layer 2?** Layer 2 is made up of “protocols” that are built on top of the Ethereum Mainnet (Layer 1). Think of it like a second layer on the blockchain cake! *(Yum, blockchain! Sorry.)*

![*Is it just me or are you getting hungry?*](Dream%20DAO%20Learning%20Together%20#5%20All%20About%20Layer%202s%202b307e1809a543bbab9e3c3a238e6acb/Untitled%201.png)

*Is it just me or are you getting hungry?*

![*L2 solutions go on top of L1 (Bitcoin, Ethereum)*](Dream%20DAO%20Learning%20Together%20#5%20All%20About%20Layer%202s%202b307e1809a543bbab9e3c3a238e6acb/Untitled%202.png)

*L2 solutions go on top of L1 (Bitcoin, Ethereum)*

This makes it possible to ***process data on-chain AND off-chain.*** But L2 protocols do keep key data and user assets on the main chain. So those things are stored safe in the Mainnet. 

- L2 is a tool that allows you to retain cryptographic security + decentralization without high prices and slow traffic.

![*On-chain and off-chain processing pathways join forces!*](Dream%20DAO%20Learning%20Together%20#5%20All%20About%20Layer%202s%202b307e1809a543bbab9e3c3a238e6acb/Untitled%203.png)

*On-chain and off-chain processing pathways join forces!*

In simple terms, this combined processing makes it easier, faster, and cheaper to scale Ethereum in ways that the underlying L1 is incapable of on its own. 

Now where will be going with this?

[Vitalik has a suggestion, an endgame.](https://vitalik.ca/general/2021/12/06/endgame.html)

![Untitled](Dream%20DAO%20Learning%20Together%20#5%20All%20About%20Layer%202s%202b307e1809a543bbab9e3c3a238e6acb/Untitled%204.png)

### 🙋🏽 FAQ: Wait, then what do DApps have to do with any of this?

DApps are digital applications or programs that run on a blockchain network of computers instead of relying on a single computer. 

![Untitled](Dream%20DAO%20Learning%20Together%20#5%20All%20About%20Layer%202s%202b307e1809a543bbab9e3c3a238e6acb/Untitled%205.png)

- Because dApps are decentralized, they are free from the control and interference of a single authority.
- Benefits of dApps include the safeguarding of user privacy, the lack of censorship, and the flexibility of development.

So, collectively, dApps make up L3! Aka:

### L3 = the apps comprising the platform’s rich DApp ecosystem. 🌴

- These apps are built either on L1 directly or utilize L2 solutions.
- Unlike the L2 protocols, L3 apps do not normally process transactions off-chain and rely on smart contracts on the blockchain.
    - Smart contracts: **agreements that have been codified inside a blockchain**.
    - **ex. of smart contract applications:** financial purposes like trading, investing, lending, and borrowing.

[https://twitter.com/hosseeb/status/1484584811180163074](https://twitter.com/hosseeb/status/1484584811180163074)

[https://twitter.com/hosseeb/status/1484583541258084353](https://twitter.com/hosseeb/status/1484583541258084353)

[Today's Arbitrum Sequencer Downtime: What Happened?](https://offchain.medium.com/todays-arbitrum-sequencer-downtime-what-happened-6382a3066fbc)

## Ok, now let’s go back to L2...What Is A Rollup? 🌯

**Rollups** are some of the **most popular** types of **L2 solutions**. 

Rollups are protocols that:

**#1 — Execute transactions off the blockchain**

**#2 —** **Roll hundreds of processed transactions into a batch**

**#3 — Post that finalized batch to the underlying L1 blockchain all at once.**

![If Rollups were a cake...](Dream%20DAO%20Learning%20Together%20#5%20All%20About%20Layer%202s%202b307e1809a543bbab9e3c3a238e6acb/Untitled%206.png)

If Rollups were a cake...

![Untitled](Dream%20DAO%20Learning%20Together%20#5%20All%20About%20Layer%202s%202b307e1809a543bbab9e3c3a238e6acb/Untitled%207.png)

***Off-chain processing and batching = achieve superior speeds and fees compared to purely L1 Ethereum-based processing.***

- **Rollups move computation (and state storage) off-chain, but keep some data per transaction on-chain**. To improve efficiency, they use a whole host of fancy compression tricks to *replace data with computation* wherever possible.

And that's it! Except for one major detail: **How do we verify that roll-ups are correct?** This leads us to the two flavors of rollups...

**Vanilla** and **chocolate**!

![Untitled](Dream%20DAO%20Learning%20Together%20#5%20All%20About%20Layer%202s%202b307e1809a543bbab9e3c3a238e6acb/Untitled%208.png)

![Untitled](Dream%20DAO%20Learning%20Together%20#5%20All%20About%20Layer%202s%202b307e1809a543bbab9e3c3a238e6acb/Untitled%209.png)

*Just kidding~!!* 😋

## **2 Types of Layer 2s, explained -Madison can do this section!**

---

<aside>
💻 You may be wondering, if L2 rollups execute transactions off-chain then transfer the data on-chain... how do we ensure that the posted data is valid? 😬

![Aka, what about these bad guys? ](Dream%20DAO%20Learning%20Together%20#5%20All%20About%20Layer%202s%202b307e1809a543bbab9e3c3a238e6acb/man-stealing-data-laptop-12086194.jpg)

Aka, what about these bad guys? 

</aside>

The answer depends on the rollup implementation use. In general, there are two types:  

**Optimistic Rollups** 😄 **and** **Zero-knowledge Rollups** 🧠

### Similarities 🟢

As previously stated, both types execute transactions off-chain and then transfer the data on-chain. In addition, they both deploy a set of smart contracts in layer one that are responsible for verifying the data. 

### Differences 🟩

The difference lies mostly in the approach for verifying transaction data, also known as **proofs**. 

**Optimistic Rollups** 😄

![Real-life footage of a bad guy getting caught in a transaction dispute and losing his $$$](Dream%20DAO%20Learning%20Together%20#5%20All%20About%20Layer%202s%202b307e1809a543bbab9e3c3a238e6acb/istockphoto-87300708-612x612.jpg)

Real-life footage of a bad guy getting caught in a transaction dispute and losing his $$$

**Zero-knowledge (ZK) Rollups** 🧠

![Literally the only ppl who can run ZK rollups ](Dream%20DAO%20Learning%20Together%20#5%20All%20About%20Layer%202s%202b307e1809a543bbab9e3c3a238e6acb/worldsbigges.jpg)

Literally the only ppl who can run ZK rollups 

## Hands-on: its time to bridge to a Layer 2 (20 minutes)

*Provide a short guide here [based on this document](https://docs.handle.fi/how-to-guides/arbitrum-l2-testnet-rinkeby)*

**DIY**

*Take some screenshots to demonstrate this. Get folks to use Arbitrum-Rinkeby testnet, make a transaction on Arb-Rinkeby and another on Rinkeby. See the difference in gas. See the difference in the block explorer.*

1. Get yourself some testnet Rinkeby ETH. If you don’t have, add your address to the list
    1. [your address here]
    2. 0xc1A6a5B2cb66caaab269Ff3713673a799135f0a0
    3. 0x5a00afB2A3e4A4154a62cf0b902249BC02b05F50
    4. 0x5c0265DCFBeeA7A363098483fE4910052D4DD668 - waiting for eth
    5. 0xCCa22fA403F96D4B161b09293faBfA10AA3385DC
    6. 0x0683Cd96043106c1cF3Fa19Bcb8160f0e7321DbF
    7. 0x83B1255816F72fF12b2005653d0D039554C19D5F
    8. 0x26BB89e1e8b5Ce5e37F57e67401ecfc798287479
    9. 0x2a81C13F9366395c8FD1EA24912294230d062Db3
2. Go to the [Arbitrum bridge](https://bridge.arbitrum.io/) and connect with your wallet

![Untitled](Dream%20DAO%20Learning%20Together%20#5%20All%20About%20Layer%202s%202b307e1809a543bbab9e3c3a238e6acb/Untitled%2010.png)

1. Make sure you’re on the Rinkeby testnet

![Untitled](Dream%20DAO%20Learning%20Together%20#5%20All%20About%20Layer%202s%202b307e1809a543bbab9e3c3a238e6acb/Untitled%2011.png)

1. Bridge over by setting how much you want, then click Deposit

![Untitled](Dream%20DAO%20Learning%20Together%20#5%20All%20About%20Layer%202s%202b307e1809a543bbab9e3c3a238e6acb/Untitled%2012.png)

1. So there’s a caveat you need to take note of!

![Untitled](Dream%20DAO%20Learning%20Together%20#5%20All%20About%20Layer%202s%202b307e1809a543bbab9e3c3a238e6acb/Untitled%2013.png)

1. You deposit into L1
    
    ![Untitled](Dream%20DAO%20Learning%20Together%20#5%20All%20About%20Layer%202s%202b307e1809a543bbab9e3c3a238e6acb/Untitled%2014.png)
    
2. Then it shows up on L2
    
    ![Untitled](Dream%20DAO%20Learning%20Together%20#5%20All%20About%20Layer%202s%202b307e1809a543bbab9e3c3a238e6acb/Untitled%2015.png)
    
3. It’s done!

![Untitled](Dream%20DAO%20Learning%20Together%20#5%20All%20About%20Layer%202s%202b307e1809a543bbab9e3c3a238e6acb/Untitled%2016.png)

1. Now set the right RPCs to be able to use it
2. To do that go to “Add network” when selecting

![Untitled](Dream%20DAO%20Learning%20Together%20#5%20All%20About%20Layer%202s%202b307e1809a543bbab9e3c3a238e6acb/Untitled%2017.png)

- Arbitrum Testnet
- [https://rinkeby.arbitrum.io/rpc](https://rinkeby.arbitrum.io/rpc)
- 421611
- ETH
- [https://rinkeby-explorer.arbitrum.io/#/](https://rinkeby-explorer.arbitrum.io/#/)

**Try some Dapps**

*[Check out which Dapps](https://portal.arbitrum.one/) have a testnet version and put it here so others can try*

You can look at you [transactions in the explorer.](https://rinkeby-explorer.arbitrum.io/)

**What happened?**

*Provide some reflection questions for our participants on using Dapps*

| DApp | Does it exist on L2 testnet? | How was the experience? (gas, UX, complexity, etc) |
| --- | --- | --- |
| https://farmland-game.github.io/collectibles | Yes but barely | I could only mint some collectibles but wasn’t sure where it shows up. |
| https://adamant.finance/stakeaddy | It's complex - no | it work on polygon  |
| Aave | No | It only works for Ethereum Mainnet, Polygon POS, and Avalanche. |
| Amy | Yes | You can “borrow,” “farm,” and do “IQ mining” — not sure what that means |
| CronoSwap | It has its own different net | It's dope but it's on Cronos main net |

## Where should DreamDAO launch on? (10 minutes)

*Suggest some criteria so that we can discuss and debate on. eg. whether there’s an exchange, whether important DAO tools are on the L2 etc.*

1. Functioning Bridge
2. Functioning DEX
    - liquidity pools and activity
3. Communication channels - [collab.land](http://collab.land) types of bots that function on that L2 or have support for your community platform
4. Important DAO tools - coordinape, snapshot, multisigs gnosis, Aragon
5. Wallet support - metamask?
6. Ecosystem and community - unique space and certain types of people will collaborate with us

## Reflections and Takeaways (10 mins)

## Ideas:

- Gary - this page can serve as a knowledge piece love the humour and graphics
- Charlotte - thanks to everyone that took part, and hands on is great
- Jae-hee - made the learning together session come together in a decentralised way
- Jacob - can catch up as we go, loved the analogies. rollups as L2 and alcohol ID as ZK helped me understand the functionality of these technologies
- Madhav - coordinating, hard to get people to work on something
- Ale - structured session, learn > try > dreamDAO > decentralisation, context to what we’re learning
- Oliver - assumed that already understood at a basic level, helpful on the deeper ideas, how its security works, privacy could work on these things
- Ahyun - help with understanding, structure of the session, help get the metaphors, move on to activity, still early much more to learn, potential to grow
- 

## Who’s doing the recap thread?

Amanda + Charlotte + Madhav

---

- Old version
    
    Icebreakers + Intros (5 mins)
    
    ***PARTICIPATE FOR ATTENDANCE:** Type in your first and last name, favorite emoji to send friends, add a colon, and answer the prompt*
    
    *Prompt: What is your favorite way to connect online?*
    
    ## L2s
    
    [Initial research](https://hackmd.io/2OIXruKLSCiOMQzt3qMn1w#Starkware-Amanda-Maritan9027)
    
    **Objectives of session:**
    
    - ELI5 of layer 2s and their different types
    - Try out a Layer 2 on testnet.
    - Get a sense of what kind of L2 would be best to launch DreamDAO on
    
    # What is a Layer 2? (20 minutes) - Jae-Hee
    
    [https://www.youtube.com/watch?v=d7ulxd3R97E](https://www.youtube.com/watch?v=d7ulxd3R97E)
    
    When it comes to adding blocks quickly to the chain, Ethereum has its boundaries. 
    
    - specifically, the maximum throughput limitation is about 15-20 transactions per second (TPS)
    
    ### The Problem: As Ethereum began hosting thousands of DApps...
    
    ***TPS speed limit*** 🏃 ***→***  ***slow transaction processing/higher fees*** 🚦 ***→***  ***scalability issue!*** ⛔
    
    ## The Solution: This is where Layer 2 (L2) steps in!
    
    **What is Layer 2?** Layer 2 is made up of “protocols” that are built on top of the Ethereum Mainnet (Layer 1). Think of it like a second layer on the blockchain cake! *(Yum, blockchain! Sorry.)*
    
    ![*Is it just me or are you getting hungry?*](Dream%20DAO%20Learning%20Together%20#5%20All%20About%20Layer%202s%202b307e1809a543bbab9e3c3a238e6acb/Untitled%201.png)
    
    *Is it just me or are you getting hungry?*
    
    ![*L2 solutions go on top of L1 (Bitcoin, Ethereum)*](Dream%20DAO%20Learning%20Together%20#5%20All%20About%20Layer%202s%202b307e1809a543bbab9e3c3a238e6acb/Untitled%202.png)
    
    *L2 solutions go on top of L1 (Bitcoin, Ethereum)*
    
    This makes it possible to ***process data on-chain AND off-chain.*** But L2 protocols do keep key data and user assets on the main chain. So those things are stored safe in the Mainnet. 
    
    - L2 is a tool that allows you to retain cryptographic security + decentralization without high prices and slow traffic.
    
    ![*On-chain and off-chain processing pathways join forces!*](Dream%20DAO%20Learning%20Together%20#5%20All%20About%20Layer%202s%202b307e1809a543bbab9e3c3a238e6acb/Untitled%203.png)
    
    *On-chain and off-chain processing pathways join forces!*
    
    In simple terms, this combined processing makes it easier, faster, and cheaper to scale Ethereum in ways that the underlying L1 is incapable of on its own. 
    
    ### 🙋🏽 FAQ: Wait, then what do DApps have to do with any of this?
    
    DApps are digital applications or programs that run on a blockchain network of computers instead of relying on a single computer. 
    
    ![Untitled](Dream%20DAO%20Learning%20Together%20#5%20All%20About%20Layer%202s%202b307e1809a543bbab9e3c3a238e6acb/Untitled%205.png)
    
    - Because dApps are decentralized, they are free from the control and interference of a single authority.
    - Benefits of dApps include the safeguarding of user privacy, the lack of censorship, and the flexibility of development.
    
    So, collectively, dApps make up L3! Aka:
    
    ### L3 = the apps comprising the platform’s rich DApp ecosystem. 🌴
    
    - These apps are built either on L1 directly or utilize L2 solutions.
    - Unlike the L2 protocols, L3 apps do not normally process transactions off-chain and rely on smart contracts on the blockchain.
        - Smart contracts: **agreements that have been codified inside a blockchain**.
        - **ex. of smart contract applications:** financial purposes like trading, investing, lending, and borrowing.
    
    [https://twitter.com/hosseeb/status/1484584811180163074](https://twitter.com/hosseeb/status/1484584811180163074)
    
    [https://twitter.com/hosseeb/status/1484583541258084353](https://twitter.com/hosseeb/status/1484583541258084353)
    
    [Today's Arbitrum Sequencer Downtime: What Happened?](https://offchain.medium.com/todays-arbitrum-sequencer-downtime-what-happened-6382a3066fbc)
    
    ## Ok, now let’s go back to L2...What Is A Rollup? 🌯
    
    **Rollups** are some of the **most popular** types of **L2 solutions**. 
    
    Rollups are protocols that:
    
    **#1 — Execute transactions off the blockchain**
    
    **#2 —** **Roll hundreds of processed transactions into a batch**
    
    **#3 — Post that finalized batch to the underlying L1 blockchain all at once.**
    
    ![If Rollups were a cake...](Dream%20DAO%20Learning%20Together%20#5%20All%20About%20Layer%202s%202b307e1809a543bbab9e3c3a238e6acb/Untitled%206.png)
    
    If Rollups were a cake...
    
    ![Untitled](Dream%20DAO%20Learning%20Together%20#5%20All%20About%20Layer%202s%202b307e1809a543bbab9e3c3a238e6acb/Untitled%207.png)
    
    ***Off-chain processing and batching = achieve superior speeds and fees compared to purely L1 Ethereum-based processing.***
    
    - **Rollups move computation (and state storage) off-chain, but keep some data per transaction on-chain**. To improve efficiency, they use a whole host of fancy compression tricks to *replace data with computation* wherever possible.
    
    And that's it! Except for one major detail: **How do we verify that roll-ups are correct?** This leads us to the two flavors of rollups...
    
    **Vanilla** and **chocolate**!
    
    ![Untitled](Dream%20DAO%20Learning%20Together%20#5%20All%20About%20Layer%202s%202b307e1809a543bbab9e3c3a238e6acb/Untitled%208.png)
    
    ![Untitled](Dream%20DAO%20Learning%20Together%20#5%20All%20About%20Layer%202s%202b307e1809a543bbab9e3c3a238e6acb/Untitled%209.png)
    
    *Just kidding~!!* 😋
    
    ## **2 Types of Layer 2s, explained -Madison can do this section!**
    
    ---
    
    <aside>
    💻 You may be wondering, if L2 rollups execute transactions off-chain then transfer the data on-chain... how do we ensure that the posted data is valid? 😬
    
    ![Aka, what about these bad guys? ](Dream%20DAO%20Learning%20Together%20#5%20All%20About%20Layer%202s%202b307e1809a543bbab9e3c3a238e6acb/man-stealing-data-laptop-12086194.jpg)
    
    Aka, what about these bad guys? 
    
    </aside>
    
    The answer depends on the rollup implementation use. In general, there are two types:  
    
    **Optimistic Rollups** 😄 **and** **Zero-knowledge Rollups** 🧠
    
    ### Similarities 🟢
    
    As previously stated, both types execute transactions off-chain and then transfer the data on-chain. In addition, they both deploy a set of smart contracts in layer one that are responsible for verifying the data. 
    
    ### Differences 🟩
    
    The difference lies mostly in the approach for verifying transaction data, also known as **proofs**. 
    
    **Optimistic Rollups** 😄
    
    ![Real-life footage of a bad guy getting caught in a transaction dispute and losing his $$$](Dream%20DAO%20Learning%20Together%20#5%20All%20About%20Layer%202s%202b307e1809a543bbab9e3c3a238e6acb/istockphoto-87300708-612x612.jpg)
    
    Real-life footage of a bad guy getting caught in a transaction dispute and losing his $$$
    
    **Zero-knowledge (ZK) Rollups** 🧠
    
    ![Literally the only ppl who can run ZK rollups ](Dream%20DAO%20Learning%20Together%20#5%20All%20About%20Layer%202s%202b307e1809a543bbab9e3c3a238e6acb/worldsbigges.jpg)
    
    Literally the only ppl who can run ZK rollups 
    
    ## Hands-on: its time to bridge to a Layer 2 (20 minutes)
    
    *Provide a short guide here [based on this document](https://docs.handle.fi/how-to-guides/arbitrum-l2-testnet-rinkeby)*
    
    **DIY**
    
    *Take some screenshots to demonstrate this. Get folks to use Arbitrum-Rinkeby testnet, make a transaction on Arb-Rinkeby and another on Rinkeby. See the difference in gas. See the difference in the block explorer.*
    
    **Try some Dapps**
    
    *[Check out which Dapps](https://portal.arbitrum.one/) have a testnet version and put it here so others can try*
    
    **What happened?**
    
    *Provide some reflection questions for our participants on using Dapps*
    
    ## Where should DreamDAO launch on? (10 minutes)
    
    *Suggest some criteria so that we can discuss and debate on. eg. whether there’s an exchange, whether important DAO tools are on the L2 etc.*
    
    ## Reflections and Takeaways (10 mins)
    
    ## Ideas:
    
    ## Who’s doing the recap thread?
    
    Amanda + Arman
    

##