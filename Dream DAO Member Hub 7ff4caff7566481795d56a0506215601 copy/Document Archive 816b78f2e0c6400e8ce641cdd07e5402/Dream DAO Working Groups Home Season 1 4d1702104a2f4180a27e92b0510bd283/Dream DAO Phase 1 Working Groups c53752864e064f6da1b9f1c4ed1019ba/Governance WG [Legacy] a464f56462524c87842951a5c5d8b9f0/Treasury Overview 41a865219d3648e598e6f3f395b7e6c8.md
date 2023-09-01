# Treasury Overview

Main goal of Treasury is deciding in what form and where the DAO stores capital to cover short term operations as well as optimize for long term goals.

Current Treasury

Gnosis Safe: [https://gnosis-safe.io/app/eth:0x1a685948F476ad329d9c038c992dB79BDE9B89E6/balances](https://gnosis-safe.io/app/eth:0x1a685948F476ad329d9c038c992dB79BDE9B89E6/balances)

Current Value as of 3/26/2022

| ETH | 17.1 ETH | $53,400 |
| --- | --- | --- |
| GTC | 1900 GTC | $13,600 |
| wETH | 0.112 wETH | $350 |
| Total | Total |  $67,350 |

**Budget Requirements**

Rough 2022 annual budget total: **TBD, but see Season 2 Budget here:** [https://www.notion.so/cucrew/Season-1-Situational-Assessment-and-Season-2-Pre-Launch-Checklist-9b013fe713aa4feb8c6a2a1aa0e63c10#d66a8276420c40949d413fcae346de82](../../../../Design%20Documents%20&%20Braindumps%2096c62424d0454ec2bd5170ad5dce5dae/Season%201%20Situational%20Assessment%20and%20Season%202%20Pre-L%209b013fe713aa4feb8c6a2a1aa0e63c10.md)

**Treasury Management - Portfolio of Investment**

With heightened volatility, it’s important to convert treasury funds into something more risk averse to ensure coverage for short term direct expenses. Once we acquire more funding, we can explore more risk on investing approaches, depending a lot on if the donors have any restrictions on what we can do with funds. 

**Defi opportunities**

- staking eth (lido finance or yearnfinance) - 5% on ETH or stETH/wETH low risk
- Angel Protocol/Anchor Protocol - 19.5% stablecoins higher risk, need to hold assets in UST (algorithmically backed stablecoin, can depeg)
    - Will need to convert USDC into UST via wormhole & astroport
- curve/yearn - 5-10% on stables but requires more active management but low risk
- Check this:

[Earn Passive Income with Crypto | Staking Rewards](https://www.stakingrewards.com/)

**Proposed Allocation**

We want to prioritize having enough capital (stablecoins) in low risk strategies that can cover expected expenses for each phase. Any additional funds can be put into more risk - on strategies (ethereum). Moving funds across chains and in/out of defi protocols incurs transaction fees.

**Rest of Phase 1**

Expected budget (50k-75k Explorers program)

Current funds ~73k

| Asset | Defi protocol | yield | Total |
| --- | --- | --- | --- |
| Stablecoin (USD, USDC, UST) | Anchor | 19% APY | 100% |
| Ethereum | LIdo | 5% APY | 0% |

Until we get more funding, we propose selling off all of our ETH ☹️ so that we can guarantee full attendance for the Explorers Program.

**Phase 2**

Budget - ???

Funds - ???

For future phases, it’s important to have different risk levels based on how much excess capital we have. 

if Treasury - 6 month budget = 0

| Asset | Defi Protocol | yield | Total |
| --- | --- | --- | --- |
| Stablecoin | Anchor | 19% APY | 0% |
| Ethereum | Lido | 5% APY | 0% |
| Stablecoin | none |  | 100% |

if 0 < Treasury - 6 month budget < 100k

| Asset | Defi Protocol | yield | Total |
| --- | --- | --- | --- |
| Stablecoin | Anchor | 19% APY | 70% |
| Ethereum | Lido | 5% APY | 20% |
| Stablecoin | none |  | 10% |

if Treasury - 6 month budget > 100k (long term allocation plan) 

| Asset | Defi Protocol | yield | Total |
| --- | --- | --- | --- |
| Stablecoin | Anchor | 19% APY | 60% |
| Ethereum | Lido | 5% APY | 40% |
| Stablecoin | Angel | 19% APY | $10-20k |
| Stablecoin | none |  | $10-20k |

Longterm plan would include a monthly rebalancing of Stablecoin/ETH to maintain a 60/40 ratio, naturally buying low and selling high on ETH

### **Questions:**

- **What is the optimal % balance of the portfolio**?
    - How should money come in?
        - 30k from ETH Foundation
        - 100k from Coinbase
        - ?k from NEAR
        - NFT Sells
    - Around 5% in ETH mainly stablecoins / USD
    - Or simpler - keep just 1 ETH and the rest should be more stable
    - If we have a larger Treasury - we can consider having the cold wallet
    - Look into what Gnosis allows us to buy
- **Are we allowed to buy crypto if we receive donations in stablecoins/USD?**
    - Use Angel protocol
    - We need our funds to be liquid until we have a lot
- **What other crypto assets would we want to hold? (BTC, other NFTs**)
    - For now only Stablecoins + ETH
- **What is the frequency of review of the account?**
    - Assume weekly review of the trend, month rebalance
    - monthly rebalancing seems appropriate
- **How do you envision the operation process for the Treasury?**
    - Maybe establish a committee to operate it
    Some of the members’ responsibilities: choosing what assets to hold, and in what %s of total capital + when to rebalance them
    - 2-3 ppl from governance wg
    - Having a Meeting whenever we want to rebalance our portfolio / do something with the funds
    - A MultiSig for every chain aggregated in one dashboard
- **What return and cash position do we want to maintain at year end?**
    - Assume 5% yield from low risk
    - Assume continued volatility, which could be an advantage after the merge in Q2
    - Don’t make any assumptions on the yield now
    
    ### ideas:
    
    - Have a multichain Treasury