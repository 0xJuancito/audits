# Juancito Smart Contract Audits

| Project | Severity | Contest | Finding | Notes |
| --- | --- | --- | --- | --- |
| Teller | High | Sherlock | [Borrowers can steal lenders principal without providing collateral by frontrunning `lenderAcceptBid` and updating the bid](https://github.com/sherlock-audit/2023-03-teller-judging/issues/250) | |
| Teller | High | Sherlock | [Adversary can modify the commited collateral of any bid at any time leading to lost or locked assets and DOS of the protocol](https://github.com/sherlock-audit/2023-03-teller-judging/issues/280) | |
| Teller | Medium | Sherlock | [Marketplaces owners can frontrun `submitBid` to steal collateral by modifying market parameters](https://github.com/sherlock-audit/2023-03-teller-judging/issues/289) | |
| Hats | Medium | Sherlock | [Transactions will be frozen if incorrect settings are used during a deployment on HatsSignerGateFactory](https://github.com/sherlock-audit/2023-02-hats-judging/issues/78) | |
