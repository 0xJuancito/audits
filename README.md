# Smart Contracts Audits and Findings by juancito

| Project | Severity | Contest | Finding | Notes |
| --- | --- | --- | --- | --- |
| USSD | | Sherlock | | TBA |
| Footium | Medium | Sherlock | [Some ERC20 tokens can get permanently stuck in the contract due to use of `transfer()`](https://github.com/sherlock-audit/2023-04-footium-judging/issues/252) | |
| Footium | Medium | Sherlock | [Increasing _`maxGenerationId` allows extra minting of academy players on previous seasons](https://github.com/sherlock-audit/2023-04-footium-judging/issues/277) | |
| Footium | Medium | Sherlock | [One extra academy player can be minted per season due to mischeck in `mintPlayers`](https://github.com/sherlock-audit/2023-04-footium-judging/issues/273) | |
| Teller | High | Sherlock | [Borrowers can steal lenders principal without providing collateral by frontrunning `lenderAcceptBid` and updating the bid](https://github.com/sherlock-audit/2023-03-teller-judging/issues/250) | |
| Teller | High | Sherlock | [Adversary can modify the commited collateral of any bid at any time leading to lost or locked assets and DOS of the protocol](https://github.com/sherlock-audit/2023-03-teller-judging/issues/280) | |
| Teller | Medium | Sherlock | [Marketplaces owners can frontrun `submitBid` to steal collateral by modifying market parameters](https://github.com/sherlock-audit/2023-03-teller-judging/issues/289) | |
| Canto Identity Subprotocols | Medium | Code4rena | [Users can end up buying and paying for a different Tray than the one they were trying to acquire](https://github.com/code-423n4/2023-03-canto-identity-findings/issues/130) | 📝 [Selected for report](https://code4rena.com/reports/2023-03-canto-identity#m-07-users-can-end-up-buying-and-paying-for-a-different-tray-than-the-one-they-were-trying-to-acquire) |
| Neo Tokyo | High | Code4rena | [A malicious user can mint a huge amount of BYTES 2.0 tokens for himself](https://github.com/code-423n4/2023-03-neotokyo-findings/issues/366) | |
| Neo Tokyo | High | Code4rena | [Malicious users can claim BYTES rewards after withdrawing all of their LP stake](https://github.com/code-423n4/2023-03-neotokyo-findings/issues/374) | Duplicate |
| Wenwin | QA | Code4rena | [QA Report](https://github.com/code-423n4/2023-03-wenwin-findings/blob/main/data/juancito-Q.md) | |
| Hats | Medium | Sherlock | [Transactions will be frozen if incorrect settings are used during a deployment on HatsSignerGateFactory](https://github.com/sherlock-audit/2023-02-hats-judging/issues/78) | |
| Biconomy | QA | Code4rena | [QA Report](https://github.com/code-423n4/2023-01-biconomy-findings/blob/main/data/juancito-Q.md) | |
