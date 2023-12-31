# Smart Contract Audits and Findings by 0xJuancito

Reach out on Twitter [@0xJuancito](https://twitter.com/0xJuancito) for security consulting and private audits.

## Audit Competitions

| Project | Severity | Contest | Finding | Notes |
| --- | --- | --- | --- | --- |
| EigenLayer | High | Code4rena | [It is impossible to slash queued withdrawals that contain a malicious strategy due to a misplacement of the ++i increment](https://github.com/code-423n4/2023-04-eigenlayer-findings/issues/205) | [📝 Selected for Report](https://code4rena.com/reports/2023-04-eigenlayer#h-02-it-is-impossible-to-slash-queued-withdrawals-that-contain-a-malicious-strategy-due-to-a-misplacement-of-the-i-increment) |
| EigenLayer | Medium | Code4rena | [Conflicting strategy can lead to reverting the whole withdrawal and temporary freeze user assets from other strategies](https://github.com/code-423n4/2023-04-eigenlayer-findings/issues/218) | |
| EigenLayer | QA | Code4rena | [QA Report](https://github.com/code-423n4/2023-04-eigenlayer-findings/blob/main/data/juancito-Q.md) | |
| Ajna | High | Code4rena | [Anyone can call memorializePositions() on behalf of other user's position due to lack of access control]([https://github.com/code-423n4/2023-05-ajna-findings/issues/488](https://github.com/code-423n4/2023-05-ajna-findings/issues/259)) | |
| Ajna | Medium | Code4rena | [Adversary can prevent the creation of any extraordinary funding proposal by frontrunning `proposeExtraordinary()`](https://github.com/code-423n4/2023-05-ajna-findings/issues/260) | [📝 Selected for Report](https://code4rena.com/reports/2023-05-ajna#m-09-adversary-can-prevent-the-creation-of-any-extraordinary-funding-proposal-by-frontrunning-proposeextraordinary) |
| Chainlink Admin | Report | Code4rena | [Ranking](https://code4rena.com/contests/2023-07-chainlink-cross-chain-contract-administration-multi-signature-contract-timelock-and-call-proxies#top) | 🥉 3rd place |
| Lybra | High | Code4rena | [Missmatch in supportVotes[] order in LybraGovernance](https://github.com/code-423n4/2023-06-lybra-findings/issues/744) | |
| Lybra | Medium | Code4rena | [Incorrect use of `token.decimals()` leads to error in rewards calculation and distribution](https://github.com/code-423n4/2023-06-lybra-findings/issues/553) | |
| Lybra | Medium | Code4rena | [`StakingRewardsV2` does not impose any restriction regarding `esLBRBoost` unlock time](https://github.com/code-423n4/2023-06-lybra-findings/issues/838) | |
| Lybra | Medium | Code4rena | [It is impossible to mint PeUSD tokens via the `LybraRETHVault` and `LybraWBETHVault` contracts due to incorrect interface](https://github.com/code-423n4/2023-06-lybra-findings/issues/545) | |
| Stader Labs | Medium | Code4rena | [`addBid()` does not increment the `endBlock` of the auction when it is close to the end, preventing the protocol from capturing extra value](https://github.com/code-423n4/2023-06-stader-findings/issues/426) | |
| Stader Labs | Medium | Code4rena | [Stale or incorrect results from data feeds can affect assets and shares calculation on deposits and withdrawals](https://github.com/code-423n4/2023-06-stader-findings/issues/312) | |
| Stader Labs | Medium | Code4rena | [Lack of Pause and Unpause Functionality in Auction Contract](https://github.com/code-423n4/2023-06-stader-findings/issues/315) | |
| Stader Labs | QA | Code4rena | [QA Report](https://github.com/code-423n4/2023-06-stader-findings/issues/327) | |
| Stader Labs | Gas | Code4rena | [Gas Report](https://github.com/code-423n4/2023-06-stader-findings/blob/main/data/LaScaloneta-G.md) | |
| Frankencoin | High | Code4rena | [Fresh positions can be instantly challenged leading to unrestricted minting of ZCHF tokens](https://github.com/code-423n4/2023-04-frankencoin-findings/issues/309) |  |
| Frankencoin | High | Code4rena | [Position owners can perform a sandwich attack against challengers to steal their collateral](https://github.com/code-423n4/2023-04-frankencoin-findings/issues/572) | |
| Frankencoin | High | Code4rena | [Adjusting position prices can lead to unavertable challenges that the protocol will have to pay for](https://github.com/code-423n4/2023-04-frankencoin-findings/issues/566) | |
| Frankencoin | High | Code4rena | [Lack of validation in opening positions parameters can lead to critical vulnerabilities at protocol level](https://github.com/code-423n4/2023-04-frankencoin-findings/issues/954) | |
| Frankencoin | Medium | Code4rena | [`restructureCapTable()` only wipes out the first address on the list](https://github.com/code-423n4/2023-04-frankencoin-findings/issues/989) | |
| Frankencoin | Medium | Code4rena | [No way to transfer minter role or rennounce to it](https://github.com/code-423n4/2023-04-frankencoin-findings/issues/990) | |
| Frankencoin | QA | Code4rena | [QA Report](https://github.com/code-423n4/2023-04-frankencoin-findings/blob/main/data/juancito-Q.md) | [📝 Selected for Report](https://code4rena.com/reports/2023-04-frankencoin#low-risk-and-non-critical-issues) |
| USSD | High | Sherlock | [`USSDRebalancer::getOwnValuation()` is easy to manipulate as it doesn't use TWAP for getting the pool price](https://github.com/sherlock-audit/2023-05-USSD-judging/issues/287) | |
| USSD | High | Sherlock | [`USSD::UniV3SwapInput()` executes swaps with no slippage protection](https://github.com/sherlock-audit/2023-05-USSD-judging/issues/229) | |
| USSD | High | Sherlock | [The protocol can't rebalance because `USSD::UniV3SwapInput()` will revert as it is missing the `deadline` when creating the `ExactInputParams` for the swap](https://github.com/sherlock-audit/2023-05-USSD-judging/issues/226) | |
| USSD | High | Sherlock | [`StableOracleWBTC::getPriceUSD()` is using ETH/USD as its price feed](https://github.com/sherlock-audit/2023-05-USSD-judging/issues/121) | |
| USSD | High | Sherlock | [`getPriceUSD` in `StableOracleDai` is miscalculated with wrong decimals from the `priceFeedDAIETH` Chainlink feed](https://github.com/sherlock-audit/2023-05-USSD-judging/issues/103) | |
| USSD | High | Sherlock | [`StableOracleDAI` calculates getPriceUSD with inverted base/rate tokens for Chainlink price](https://github.com/sherlock-audit/2023-05-USSD-judging/issues/102) | [📝 Selected for Report](https://audits.sherlock.xyz/contests/82/report) |
| USSD | High | Sherlock | [Static oracles in `StableOracleDAI` and `StableOracleWBGL` have wrong addresses](https://github.com/sherlock-audit/2023-05-USSD-judging/issues/95) | |
| USSD | High | Sherlock | [`ethOracle` is not defined in `StableOracleDAI` making `getPriceUSD` always revert](https://github.com/sherlock-audit/2023-05-USSD-judging/issues/93) | |
| USSD | High | Sherlock | [Missing access control on `burnRebalancer` allows unrestricted burning of USSD tokens by anyone affecting pool balance on rebalance](https://github.com/sherlock-audit/2023-05-USSD-judging/issues/86) | |
| USSD | High | Sherlock | [Missing access control on `mintRebalancer` allows unrestricted minting of USSD tokens by anyone affecting pool balance on rebalance](https://github.com/sherlock-audit/2023-05-USSD-judging/issues/85) | |
| USSD | Medium | Sherlock | [`latestRoundData` from Chainlink might return stale or incorrect results](https://github.com/sherlock-audit/2023-05-USSD-judging/issues/104) | |
| USSD | Medium | Sherlock | [There is no method for redeeming DAI to prevent negative scenarios described in the whitepaper](https://github.com/sherlock-audit/2023-05-USSD-judging/issues/218) | |
| USSD | Medium | Sherlock | [Collateral tokens will be stuck on the contract and will be unusable after calling USSD::removeCollateral()](https://github.com/sherlock-audit/2023-05-USSD-judging/issues/261) | |
| Footium | Medium | Sherlock | [Some ERC20 tokens can get permanently stuck in the contract due to use of `transfer()`](https://github.com/sherlock-audit/2023-04-footium-judging/issues/252) | |
| Footium | Medium | Sherlock | [Increasing _`maxGenerationId` allows extra minting of academy players on previous seasons](https://github.com/sherlock-audit/2023-04-footium-judging/issues/277) | |
| Footium | Medium | Sherlock | [One extra academy player can be minted per season due to mischeck in `mintPlayers`](https://github.com/sherlock-audit/2023-04-footium-judging/issues/273) | |
| Gravita | Low | Hats | [Out of gas in collectFees](https://github.com/Gravita-Protocol/Gravita-SmartContracts/issues/222) | |
| Teller | High | Sherlock | [Borrowers can steal lenders principal without providing collateral by frontrunning `lenderAcceptBid` and updating the bid](https://github.com/sherlock-audit/2023-03-teller-judging/issues/250) | |
| Teller | High | Sherlock | [Adversary can modify the commited collateral of any bid at any time leading to lost or locked assets and DOS of the protocol](https://github.com/sherlock-audit/2023-03-teller-judging/issues/280) | |
| Teller | Medium | Sherlock | [Marketplaces owners can frontrun `submitBid` to steal collateral by modifying market parameters](https://github.com/sherlock-audit/2023-03-teller-judging/issues/289) | |
| Caviar Private Pools | Medium | Code4rena | [Adversary can prevent the creation of any private pools by frontrunning the deployer](https://github.com/code-423n4/2023-04-caviar-findings/issues/567) | |
| Canto Identity Subprotocols | Medium | Code4rena | [Users can end up buying and paying for a different Tray than the one they were trying to acquire](https://github.com/code-423n4/2023-03-canto-identity-findings/issues/130) | [📝 Selected for report](https://code4rena.com/reports/2023-03-canto-identity#m-07-users-can-end-up-buying-and-paying-for-a-different-tray-than-the-one-they-were-trying-to-acquire) |
| Neo Tokyo | High | Code4rena | [A malicious user can mint a huge amount of BYTES 2.0 tokens for himself](https://github.com/code-423n4/2023-03-neotokyo-findings/issues/366) | |
| Neo Tokyo | High | Code4rena | [Malicious users can claim BYTES rewards after withdrawing all of their LP stake](https://github.com/code-423n4/2023-03-neotokyo-findings/issues/374) | |
| Wenwin | QA | Code4rena | [QA Report](https://github.com/code-423n4/2023-03-wenwin-findings/blob/main/data/juancito-Q.md) | |
| Hats | Medium | Sherlock | [Transactions will be frozen if incorrect settings are used during a deployment on HatsSignerGateFactory](https://github.com/sherlock-audit/2023-02-hats-judging/issues/78) | |
| Biconomy | QA | Code4rena | [QA Report](https://github.com/code-423n4/2023-01-biconomy-findings/blob/main/data/juancito-Q.md) | |
| Polynomial | High | Code4rena | [KangarooVault.removeCollateral doesn't remove the collateral from the position](https://github.com/code-423n4/2023-03-polynomial-findings/issues/261) | |
| Polynomial | Medium | Code4rena | [Invalid and stale prices from Synthethix are not validated](https://github.com/code-423n4/2023-03-polynomial-findings/issues/260) | |
| Polynomial | Medium | Code4rena | [Spamming deposit and withdraw queues](https://github.com/code-423n4/2023-03-polynomial-findings/issues/262) | |
| Polynomial | QA | Code4rena | [QA Report](https://github.com/code-423n4/2023-03-polynomial-findings/blob/main/data/juancito-Q.md) | |
| Asymmetry | High | Code4rena | [Adversary can alter derivatives balances in contracts to steal Ether](https://github.com/code-423n4/2023-03-asymmetry-findings/issues/454) | |
| Asymmetry | Medium | Code4rena | [Precision loss in stake function affects share calculation](https://github.com/code-423n4/2023-03-asymmetry-findings/issues/1044) | |
| Asymmetry | Medium | Code4rena | [Remaining dust from Ether deposits is not returned to users](https://github.com/code-423n4/2023-03-asymmetry-findings/issues/455) | |
| Asymmetry | QA | Code4rena | [QA Report](https://github.com/code-423n4/2023-03-asymmetry-findings/blob/main/data/juancito-Q.md) | |
| Arcade | QA | Code4rena | [Report TBA](https://code4rena.com/contests/2023-07-arcadexyz#top) | 📝 Selected for Report |
| Chainlink Staking | Medium | Code4rena | Report TBA | |
| Chainlink Staking | Medium | Code4rena | Report TBA | |
| Chainlink Staking | Medium | Code4rena | Report TBA | |
| Chainlink Staking | Medium | Code4rena | Report TBA | |
| Chainlink Staking | QA | Code4rena | Report TBA | |
| Dopex | High | Code4rena | Report TBA | |
| Dopex | Medium | Code4rena | Report TBA | |
| Dopex | Medium | Code4rena | Report TBA | |
| Dopex | QA | Code4rena | Report TBA | |
| Lens Protocol | Medium | Code4rena | [Report TBA](https://code4rena.com/contests/2023-07-lens-protocol-v2#top) | |
| Lens Protocol | Medium | Code4rena | [Report TBA](https://code4rena.com/contests/2023-07-lens-protocol-v2#top) | |
| Lens Protocol | Medium | Code4rena | [Report TBA](https://code4rena.com/contests/2023-07-lens-protocol-v2#top) | |
| Lens Protocol | Medium | Code4rena | [Report TBA](https://code4rena.com/contests/2023-07-lens-protocol-v2#top) | |
| Lens Protocol | Medium | Code4rena | [Report TBA](https://code4rena.com/contests/2023-07-lens-protocol-v2#top) | |
| Lens Protocol | QA | Code4rena | [Report TBA](https://code4rena.com/contests/2023-07-lens-protocol-v2#top) | |
| Rubicon v2 | High | Code4rena | [Report TBA](https://code4rena.com/contests/2023-04-rubicon-v2#top) | |
| Rubicon v2 | Medium | Code4rena | [Report TBA](https://code4rena.com/contests/2023-04-rubicon-v2#top) | |
| Rubicon v2 | Medium | Code4rena | [Report TBA](https://code4rena.com/contests/2023-04-rubicon-v2#top) | |
| Contest 225 | High | Code4rena | [Report TBA](https://code4rena.com/contests/2023-03-contest-225-contest) | |
| Contest 225 | High | Code4rena | [Report TBA](https://code4rena.com/contests/2023-03-contest-225-contest) | |
| Contest 225 | High | Code4rena | [Report TBA](https://code4rena.com/contests/2023-03-contest-225-contest) | |
| Contest 225 | High | Code4rena | [Report TBA](https://code4rena.com/contests/2023-03-contest-225-contest) | |
| Contest 225 | High | Code4rena | [Report TBA](https://code4rena.com/contests/2023-03-contest-225-contest) | |
| Contest 225 | High | Code4rena | [Report TBA](https://code4rena.com/contests/2023-03-contest-225-contest) | |
| Contest 225 | Medium | Code4rena | [Report TBA](https://code4rena.com/contests/2023-03-contest-225-contest) | |
| Contest 225 | Medium | Code4rena | [Report TBA](https://code4rena.com/contests/2023-03-contest-225-contest) | |
| Contest 225 | QA | Code4rena | [Report TBA](https://code4rena.com/contests/2023-03-contest-225-contest) | |
