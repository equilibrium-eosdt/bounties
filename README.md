# Equilibrium’s Bug Bounty Program

## What should you know about Equilibrium?

[Equilibrium](https://equilibrium.io/) is an all-in-one Interoperable DeFi hub that consists of several main products:  

|Product|Brief Description|
|-------|-----------------|
|[EOSDT](https://equilibrium.io/eosdt/en)   |EOSDT is an asset-backed stablecoin that is pegged to the U.S. dollar (1:1). It leverages underlying EOS & BTC collateral and adds extra liquidity to the market. |
|[Native Utility Token (NUT)](https://medium.com/@Equilibrium_EOSDT/how-to-use-equilibriums-nut-token-68d6c06a4730)   |Is a token that gives users access to a number of the framework’s functionalities: decentralized governance; payment of fees; access to discounted collateral; Block Producer voting. |
|[Block Producer voting](https://equilibrium.io/voting)   |Users can vote for their favorite block producer and get a reward. |
|[Staking Pool](https://equilibrium.io/staking/en) |Users deposit their holdings in EOSDT/NUT/EOS and earn risk-free savings. |
|[Rates Subscription](https://knowledgebase.equilibrium.io/tools-and-products/products/rates) |Any third party account or smart contract may subscribe to the price feed to receive timely updates required for business logic. |

To check other products and find more information about smart contracts, use our [specifications](https://equilibrium.io/en/specification) and [knowledge base](https://knowledgebase.equilibrium.io/).

## Scope

The scope for this bounty program includes frontend and smart contracts. The following contracts are in the scope:

|Product|Brief Description|
|-------|-----------------|
|eosdtnutoken|NUT token contract|
|eosdtsttoken|EOSDT token contract|
|eosdtgovernc|Governance contract|
|eosdtcntract|EOS positions contract|
|eosdtpbtcpos|BTC positions contract|
|eosdtliqdatr|EOS liquidator contract|
|eosdtpbtcliq|BTC liquidator contract|
|eosdtorclize|Price feed contract|
|eosdtarmseos|Pyramiding contract|
|eosdtsavings|Savings rate contract|
|eosdtbpproxy|Block producer voting proxy account|

## Rewards

|Category|Frontend|Smart contracts|Rewards|
|--------|--------|---------------|-------|
|Low|-|Not optimized consumption of resources, usage of deprecated practices etc.|$0-\$100 in NUT</br>To be paid until the 15th day of the next month after the report is accepted|
|Medium|Misleading or insecure frontend behavior, vulnerabilities leading to potential attacks|Logic errors, low impact vulnerabilities (not causing losses)|$100-\$500 in NUT</br>To be paid until the 15th day of the next month after the report is accepted|
|High|-|Vulnerabilities that might cause losses, critical logic bugs|$500-\$2,000 in NUT</br>In 5 business days after the report is accepted and confirmed|
|Critical|-|Serious vulnerabilities that might cause serious losses and application shutdown|$2,000-\$5,000 in NUT</br>In 5 business days after the report is accepted and confirmed|

The severity of reported vulnerabilities will be graded according to the [CVSS](https://www.first.org/cvss/calculator/3.1) (Common Vulnerability Scoring Standard).

## Rules

The report should contain the following sections:

- **Bug Introduction**: A brief description of the vulnerability
- **Bug Description**: A detailed description of the vulnerability
- **Potential cause of the bug.**
- **Detailed scenario explaining an attack vector.**
- **Potential damage caused by this bug.**  
- Please submit your report at [support@eosdt.zendesk.com](mailto:support@eosdt.zendesk.com)

### Disclosure Policy

By participating in the bug bounty, you are agreeing to adhere to the following rules:

- Let us know as soon as you discover a security risk
- Please provide detailed reports with reproducible steps. Failing this, the issue will not be eligible for a reward.
- Please be available to cooperate with Equilibrium’s engineering team to provide further information on the bug if needed.
- In case of duplicates, we will only award the first report that was received, provided that it can be fully reproduced.
- Multiple vulnerabilities caused by one underlying issue will be awarded one bounty.
- Social engineering (e.g. phishing, vishing, smishing) is prohibited.
- Bug reports that are known to us cannot be accepted.
- Your testing must not violate any law or compromise any data that is not yours.
- Judgments of submissions are at Equilibrium’s sole discretion as is the award of payments. It is possible that you may receive a lower reward than you expected or no reward at all.
- Please respect third party applications and understand that issues that are not specific to Equilibrium smart contracts are not part of the bounty program. Equilibrium reserves the right to forward details of the issue to that party without further discussion with the program participant.
- We can close the program at any time.
