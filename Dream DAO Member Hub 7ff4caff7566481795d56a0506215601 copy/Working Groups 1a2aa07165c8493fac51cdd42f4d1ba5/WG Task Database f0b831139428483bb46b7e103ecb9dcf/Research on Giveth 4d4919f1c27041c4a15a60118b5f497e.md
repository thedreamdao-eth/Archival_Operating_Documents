# Research on Giveth

Context: Deep dive on policies, requirements,  reliability, process to use the platform; how can the dao use it; what’s it for
Deadline: March 17, 2023
Peeps: Aaryan Chadha
Season: S3
Status: Done
WG: Grants

**Questions to answer:**

Giveth helps raise finance for listed projects, they operate in a decentralized manner, dont take any charges/fees and provide donor benefits as well

- Project Details→ They use their own platform to raise finance + conduct checks to ensure whether any project is a registered non-profit/business, non registered projects can also apply based on my understanding. However, there is an aspect of Giveth that incentivizes non-profits and donors to not withdraw and instead stake to earn ‘rewards’ which seems counterintuitive in situations since a large portion of active projects are for disaster relief, e.g. Turkey earth quake. They are themselves a registered 501c3 (same as CU) and part of SDG impact fund → however, I checked that SDG impact fund is not related to the UN, it is another donor advised fund. Also they don’t check up with registered projects to check whether they support donor tax deduction. Rn, they don’t have support for non-crypto donations either. They do have GIVTrace which is optional, so there are projects that don’t let users see where they spend their funds + there is no accountability for completion of projects (that’s a problem with normal donations as well). No funding caps.
- Process to create a project is pretty simple but they have to be approved first.
- Verification Process → The details of internal verification after application to submit a project are:
    - [https://docs.giveth.io/dapps/projectVerification/](https://docs.giveth.io/dapps/projectVerification/)
    - Becoming verified, makes GIVbacks eligible, that give donors GIV tokens for donating, there are periods of givbacks and this encourages more donations to the project, can be very helpful for DreamDAO
    - The details can be changed after a project is published including name + email.
- If we link to a wallet of a current Co-Steward, will we be able to unlink/change it later down the line? → Yes, project details can be changed even after publishing the project. Also even at the beginning we can enter 2 addresses for Mainnet and Gnosis but idt that’s relevant to DreamDAO, I can be wrong so I put it here for reference. New owner must be whitelisted by previous one however and TRACES is required (details and whitepaper below)
- Features of Giveth:
    - GIV → their erc20 token
    - GIVBacks → Only on Gnosis, They happen in rounds where GIV are alloted to be given back to the community in exchange for donations for verified projects, for this round the allocation is 1 Million GIV
    - GIVGarden → iHive based voting mechanism, so if DreamDAO holds their GIV tokens which they receive via donation/buying, they can vote in decisions regarding sponsorships, goods, public and donor benefits, funding which can help DreamDAO grow as well. Voting is of 2 types: conviction which is for general purpose and Tao which is for emergencies
    - Giveth TRACE → Dapp that allows project owners to define funding objectives and adds an extra layer of accountability (optional) but helps DAOs build more trust. (recently deprecated → everything has moved on to [giveth.io](http://giveth.io) but same functionality). IMPORTANT FOR OWNERSHIP TRANSFER AS IT CAN ONLY BE DONE IF TRACES IS ENABLED USING VAULT CONTRACT
    - $nice token → recently launched to promote direction donations to Giveth
        - they implemented NFT PFPs with this token, which is similar to DreamDAO and also rewards programs for nice holders (might open similar features for other projects in the future which can be good for dreamdao to encourage more donations)
    - Upcoming features:
        - GIVPower → staking feature, locking GIV tokens for GIVpower (higher return), only for donors
        - GIVmatching → Top ranked verified projects can get their donations matched through a collectively funded matching pool (questionable success rate)
        - GIVfi → smart contracts generating yield on idle donations (unclaimed ones), the yield goes to funding the DAO and buying back GIV, encourages non-liquidation which is counterproductive at times
        - Gurves → Allowing projects on GIV to become DAOs by being collaterized by GIV and having their own micro-economies. Donors can become investors, volunteers and shareholders. Since this is under development, there can be features related to helping existing DAOs in a similar manner which can help DreamDAO grow, gain participants
    - Distribution structure
    
    ![Untitled](Research%20on%20Giveth%204d4919f1c27041c4a15a60118b5f497e/Untitled.png)
    
- Decision Making and Governance
    - On-chain: Gardens as mentioned above. Enforcement happens using Celeste which is a democratic dispute resolution method. All proposals using GIVGarden require GIV deposits
        - Specifics regarding on chain governance and voting processes (some has been summarized already): [https://docs.giveth.io/whatisgiveth/governanceProcess/](https://docs.giveth.io/whatisgiveth/governanceProcess/)
    - Off-Chain: Advice process is used where if a large no-code decision has to be made (non-financial), votes are conducted using Discord polls or a Forum. A decisions is considered legitimate if results are not challenged in 2 weeks, and respects the covenant (social contract)
    - Gravity Conflict Management is used, details → [https://forum.tecommons.org/t/gravity-general-process/173](https://forum.tecommons.org/t/gravity-general-process/173) (an alternative dispute resolution tailored system) There are trained Giveth gravitons who promote open and healthy communication and mediate conflict resolution. Voting members can also express interested in joining.
    - Code of Conduct → [https://www.contributor-covenant.org/version/1/4/code-of-conduct.html](https://www.contributor-covenant.org/version/1/4/code-of-conduct.html)
    - 3 Circles: i) Community →  Comms, Connect, Conflict resolution WGs ii) Platform → Design, Dev, GIVeconomy WGs iii) GIVernance → Governance, DAO WGs w/ weekly meetings. The platforms used are very similar to DreamDAO
- *important → Fundraising Guide for Projects, includes how to launch, build brand, get higher donations, engage with community using stewardships, handle social media (very summarized format) →* [https://docs.giveth.io/whatisgiveth/fundraisingGuide](https://docs.giveth.io/whatisgiveth/fundraisingGuide)
- Project Quality Assurance Guide →
    - Clear project descriptions explaining who they are and what they want to do with the funds
    - ✔️ A unique or custom banner photo
    - ✔️ No violations of our [Covenant](https://docs.giveth.io/whatisgiveth/covenant/) and/or **Terms of Use**
    - ✔️ (Optional) Embedded photos, videos or legitimate external links
    - ✔️ (Optional) For open-source projects, a link to their repository
    - E.g. [https://giveth.io/project/the-giveth-community-of-makers](https://giveth.io/project/the-giveth-community-of-makers)
- Project Verification Details Needed →
    - details can be changed
        1. Your full name
        2. Your email address
        3. If your project is part of a registered non-profit organization, you will need to upload documentation to prove your registered status. Having obtained non-profit status is not a requirement, but it is helpful for the verification process.
        4. If your project is not a registered non-profit, the team will need to know how your organization is structured.
        5. Links and/or usernames to the social media accounts that are owned by both you and the organization. eg. Twitter, Github, Discord, Facebook, etc.
        6. The name of your project
        7. Information about the history of your project, e.g., when it was founded, which milestones your organization/project has achieved since conception, etc. Please provide links to photos, videos, testimonials or other evidence of your project's impact.
        8. The funds raised are expected to be used for public benefit and not for personal gain - Giveth will need to know how you will use the funds that your project raises. We are looking for detailed funding goals as well as an overall roadmap/action plan of the project.
        9. A list of all wallet addresses used for managing funds within your project.
        10. In order to ensure that you are actually a representative of the project you're applying for, we ask that you post/share a link to your Giveth project **from the organization's Twitter or social media account.** You will need to provide a link to the Twitter or social media post.
        11. Confirm “Yes”: We pledge that funds raised will be used for public benefit, not for personal gain.
        12. Confirm “Yes”: We understand Giveth will be analyzing all donations looking for fraud or abuse. If Giveth has any reason to suspect abuse, we understand our donors may not receive any GIVbacks and that Giveth may share any evidence of fraud publicly.
        13. Confirm “Yes”: We will only accept new, external donations through Giveth, and we understand that if we are found to be recirculating our own funds through Giveth, this will be considered abuse of the system.
        14. Confirm “Yes”: We understand our donation data will be reviewed, and if it seems like in any way we are abusing the system, our donors will not receive GIVbacks, and we will lose our verified status.
        15. Our goal is to ensure there is no fraudulent use of GIVbacks. We will need to know what reputation is at stake for you and/or your project if you were to be found participating in malicious activity. *Please provide links to proof of reputation if available.
    - Disqualifiers from GIVBacks: using incentives such as services (e.g. builder status) or goods to get donations, misuse of funds, fraud, circulating donations raised by other means (so using donations to donate to get GIVbacks)
- Giveth Roles
    - Website User
    - Giver → donor, can get delegated into a project/campaign (verified)
    - Community Manager → owner of a community project, delegating funds can be done by them  to their community, has to be whitelisted by DApp admin
    - Campaign manager → giveth users who make their project traceable, they can edit campaign (needed for DreamDAO), delegate, add traces
    - Campaign Reviewer → review locked donations
    - Trace Manager → Add, edit, update traces
    - Trace Reviewer
    - Recipient
    - Currency Flow
        
        Giveth TRACE on a technical level is a system for managing currency. Terms referring to the movement of funds within the Giveth system are defined as follows:
        
        - **Donation:** When a Giver sends funds from their wallet to a Trace, Campaign, or Community.
        - **Collecting:** When the Recipient sends or "collects" funds from a Trace to their wallet.
        - **Disbursing:** When a Trace Manager sends funds from a Trace account to the Recipient's wallet.
        - **Delegation:** When a Campaign Manager or Community Manager sends money from the Campaign or Community account to Trace account on behalf of the original Giver. A Giver can reject Delegation within 72 hours, after which the Currency transfer becomes irreversible.
        - **Refund:** A Giver who has contributed to a Community can withdraw their funds as long as they are not yet committed to a Campaign or Trace. A Giver contributing to a Campaign can withdraw their funds as long as they are not yet committed to a Trace.
        - **Refund:** A Giver who has contributed to a Community can withdraw their funds as long as they are not yet committed to a Campaign or Trace. A Giver contributing to a Campaign can withdraw their funds as long as they are not yet committed to a Trace.
    - 
    
    ![Untitled](Research%20on%20Giveth%204d4919f1c27041c4a15a60118b5f497e/Untitled%201.png)
    
- White Paper on Traces (technical), deprecated but still useful as features exist → [https://docs.giveth.io/technicalWhitePaper/](https://docs.giveth.io/technicalWhitePaper/)
- Dev Guides to do local installs, add customization, do testing → [https://docs.giveth.io/dapps/contributors](https://docs.giveth.io/dapps/contributors)
- I don’t 100% understand all the technical details of the GIVeconomy yet but i have summarized most of the important details above but here are the docs for reference → [https://docs.giveth.io/giveconomy](https://docs.giveth.io/giveconomy)
- !!!There have been exploitations of GIVfarm as recent as OCT 2022 on ETH!!!

**Resources:** 

- Project owners 101 - playlist. 
Short course about setting up the project, verifying it, policies, etc.
    
    [https://www.youtube.com/playlist?list=PL4Artm1rmCWFi-qEkOtjl9nL4tojSIIKm](https://www.youtube.com/playlist?list=PL4Artm1rmCWFi-qEkOtjl9nL4tojSIIKm)