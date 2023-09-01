# Election Systems Research

Created by: Aditya Dahiya
Created time: May 8, 2023 10:37 AM

# 👀 Election System Requirements

> In [#6 - Governance WG Meeting - ](../Governance%20WG%20Meetings%208818ea33b54a432ab37717683ebcb05f/#6%20-%20Governance%20WG%20Meeting%20-%20e2cbec625d8e4115a196e85afbbc04c2.md) the following requirements were reaffirmed for the Season 4 Election System:
> 
> - Security
>     - The election system should be able to guarantee a legitimate outcome even if there are malicious attempts by people to manipulate the election.
> - Anonymity
>     - The votes cast must be anonymous. No one should be able to find out who a member voted for. This should be the case both during and after the election.
> - Transparency
>     - Any member of the DAO should be able to verify the results of the election easily without having to trust any committee or member blindly.
> - Web3
>     - An on-chain solution that utilizes SkywalkerZ NFTs to token-gate the process would be ideal.
> 
> Besides all these requirements, casting a vote should be simple without a high technical barrier. The Election system should also allow the DAO to use ranked-choice voting.
> 

---

# 💭 Proposed Solution

> Aditya has researched the following potential solution:
> 
> - Vocdoni [https://vocdoni.app/](https://vocdoni.app/)

---

# 🛫 Vocdoni

> Vocdoni runs using the Byzantine fault-tolerant blockchain called **Vochain**, which is based on Tendermint. The Vocdoni blockchain requires a native token (VOC) to execute management transactions (i.e. creating elections) but not for casting votes. Therefore, the voters can vote in a free and gasless manner. Vochain is currently Proof-of-Authority but plans to transition to Proof of Stake in 2023.

A typical election conducted using Vocdoni looks like this:
> 
> - A Vocdoni account (which can be used with Metamask) creates an election by specifying the following options:
>     - **Census origin:** description of the eligible voters or rules.
>     - **Lifecycle:** initial state, start, and end of the voting time.
>     - **Election mode:** how the process will behave.
>     - **Vote mode:** the kind of ballots expected from voters.
>     - **Tally mode:** how the results will be computed as defined by the Vocdoni Ballot protocol. Details and examples can be found [here](https://blog.aragon.org/vocdoni-ballot-protocol).
> - As per the election lifecycle option, the election goes through various stages like **paused**, **ready**, **finished**, and eventually, **result** declared.
> - Depending on how the election was set up, these options can be immutable or mutable after creation.
> 
> - Security
>     
>     **Gateways** are entry points for the Vocdoni P2P network. **Gateways** allow users to interact with the blockchain using APIs. They also compute election results.
>     
>     Vocdoni G**ateways** use IPFS for all storage needs, including election data like specific election questions, descriptions, and candidate responses. IPFS also stores the **census** data.
>     
>     In Vocdoni, the **census** defines the set of users that are eligible to vote in a particular election. We can use public eth addresses, token ownership, or email/sms authentication as a basis for the census.
>     
>     The entire process appears to be secure end-to-end.
>     
> - Anonymity
>     
>     The **Vote mode** for an election can be set to **Anonymous,** which uses a zk-SNARK proof to ensure that the identity of the voter can not be recovered. 
>     
>     The **Vote mode** can additionally be set to **Encrypted**, which only reveals the voting tally after the election ends (it is like Snapshot’s **Shutter** voting).
>     
>     When used in combination, these options allow true anonymity, as desired by the system requirements.
>     
> - Transparency
>     
>     Since IPFS stores all election data, the election is completely transparent and easily verifiable by any member of the community.
>     
> - Web3
>     
>     All essential data remains on-chain, either on IPFS or Vochain. 
>     
> 
> Potential issues:
> 
> - The entire process is code-heavy and can't be implemented by a non-technical member
> - The zk-snark proofs required for anonymity might force members to use a laptop/desktop to vote.