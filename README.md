# Smart Contract Audits and Findings by 0xJuancito

Reach out on Twitter [@0xJuancito](https://twitter.com/0xJuancito) for security consulting and private audits.

## Audit Competitions

#### 🔐 94 High/Medium severity bugs found in public competitions

###### Notes: 🏆 *Selected for Report*

| Project | Severity | Finding | Notes |
| :---: | :---: | --- | :---: |
| EigenLayer | High | [It is impossible to slash queued withdrawals that contain a malicious strategy due to a misplacement of the ++i increment](https://github.com/code-423n4/2023-04-eigenlayer-findings/issues/205) | [🏆](https://code4rena.com/reports/2023-04-eigenlayer#h-02-it-is-impossible-to-slash-queued-withdrawals-that-contain-a-malicious-strategy-due-to-a-misplacement-of-the-i-increment) |
| EigenLayer | Medium | [Conflicting strategy can lead to reverting the whole withdrawal and temporary freeze user assets from other strategies](https://github.com/code-423n4/2023-04-eigenlayer-findings/issues/218) | |
| EigenLayer | QA | [QA Report](https://github.com/code-423n4/2023-04-eigenlayer-findings/blob/main/data/juancito-Q.md) | |
| Lens Protocol | Medium | [Lens Handles from v1 can be minted by other users on v2 before they are migrated to their corresponding owner](https://github.com/code-423n4/2023-07-lens-findings/issues/105) | |
| Lens Protocol | Medium | [Users can make any user follow them via FollowNFT::tryMigrate() without their consent](https://github.com/code-423n4/2023-07-lens-findings/issues/104) | [🏆](https://code4rena.com/reports/2023-07-lens#m-10-users-can-make-any-user-follow-them-via-follownfttrymigrate-without-their-consent) |
| Lens Protocol | Medium | [Users can self-follow via FollowNFT::tryMigrate() on Lens V2](https://github.com/code-423n4/2023-07-lens-findings/issues/106) | [🏆](https://code4rena.com/reports/2023-07-lens#m-09-users-can-self-follow-via-follownfttrymigrate-on-lens-v2) |
| Lens Protocol | Medium | [Implementation error of EIP-712 due to wrong Typehash can lead to tx reverts](https://github.com/code-423n4/2023-07-lens-findings/issues/107) | |
| Lens Protocol | Medium | [Missing pause modifier on important LensV2Migration and FollowNFT functions](https://github.com/code-423n4/2023-07-lens-findings/issues/108) | |
| Lens Protocol | QA | [QA Report](https://github.com/code-423n4/2023-07-lens-findings/blob/main/data/juancito-Q.md) | |
| Chainlink | Report | [2nd Best Report](https://code4rena.com/contests/2023-07-chainlink-cross-chain-contract-administration-multi-signature-contract-timelock-and-call-proxies#top) | 🥈 |
| Ajna | High | [Anyone can call memorializePositions() on behalf of other user's position due to lack of access control](https://github.com/code-423n4/2023-05-ajna-findings/issues/259) | |
| Ajna | Medium | [Adversary can prevent the creation of any extraordinary funding proposal by frontrunning `proposeExtraordinary()`](https://github.com/code-423n4/2023-05-ajna-findings/issues/260) | [🏆](https://code4rena.com/reports/2023-05-ajna#m-09-adversary-can-prevent-the-creation-of-any-extraordinary-funding-proposal-by-frontrunning-proposeextraordinary) |
| Lybra | High | [Missmatch in supportVotes[] order in LybraGovernance](https://github.com/code-423n4/2023-06-lybra-findings/issues/744) | |
| Lybra | Medium | [Incorrect use of `token.decimals()` leads to error in rewards calculation and distribution](https://github.com/code-423n4/2023-06-lybra-findings/issues/553) | |
| Lybra | Medium | [`StakingRewardsV2` does not impose any restriction regarding `esLBRBoost` unlock time](https://github.com/code-423n4/2023-06-lybra-findings/issues/838) | |
| Lybra | Medium | [It is impossible to mint PeUSD tokens via the `LybraRETHVault` and `LybraWBETHVault` contracts due to incorrect interface](https://github.com/code-423n4/2023-06-lybra-findings/issues/545) | |
| Stader Labs | Medium | [`addBid()` does not increment the `endBlock` of the auction when it is close to the end, preventing the protocol from capturing extra value](https://github.com/code-423n4/2023-06-stader-findings/issues/426) | |
| Stader Labs | Medium | [Stale or incorrect results from data feeds can affect assets and shares calculation on deposits and withdrawals](https://github.com/code-423n4/2023-06-stader-findings/issues/312) | |
| Stader Labs | Medium | [Lack of Pause and Unpause Functionality in Auction Contract](https://github.com/code-423n4/2023-06-stader-findings/issues/315) | |
| Stader Labs | QA | [QA Report](https://github.com/code-423n4/2023-06-stader-findings/issues/327) | |
| Stader Labs | Gas | [Gas Report](https://github.com/code-423n4/2023-06-stader-findings/blob/main/data/LaScaloneta-G.md) | |
| Dopex | High | [All options settlements can be blocked with a permanent DOS of the settle() function](https://github.com/code-423n4/2023-08-dopex-findings/issues/1019) | |
| Dopex | Medium | [Missing slippage parameter on Uniswap addLiquidity() function](https://github.com/code-423n4/2023-08-dopex-findings/issues/1032) | [🏆](https://code4rena.com/reports/2023-08-dopex#m-06-missing-slippage-parameter-on-uniswap-addliquidity-function) |
| Dopex | Medium | [The owner of RPDX Decaying Bonds is not updated on token transfers](https://github.com/code-423n4/2023-08-dopex-findings/issues/1030) | [🏆](https://code4rena.com/reports/2023-08-dopex#m-07-the-owner-of-rpdx-decaying-bonds-is-not-updated-on-token-transfers) |
| Dopex | QA | [QA Report](https://github.com/code-423n4/2023-08-dopex-findings/blob/main/data/juancito-Q.md) | [🏆](https://code4rena.com/reports/2023-08-dopex#low-risk-and-non-critical-issues) |
| Frankencoin | High | [Fresh positions can be instantly challenged leading to unrestricted minting of ZCHF tokens](https://github.com/code-423n4/2023-04-frankencoin-findings/issues/309) |  |
| Frankencoin | High | [Position owners can perform a sandwich attack against challengers to steal their collateral](https://github.com/code-423n4/2023-04-frankencoin-findings/issues/572) | |
| Frankencoin | High | [Adjusting position prices can lead to unavertable challenges that the protocol will have to pay for](https://github.com/code-423n4/2023-04-frankencoin-findings/issues/566) | |
| Frankencoin | High | [Lack of validation in opening positions parameters can lead to critical vulnerabilities at protocol level](https://github.com/code-423n4/2023-04-frankencoin-findings/issues/954) | |
| Frankencoin | Medium | [`restructureCapTable()` only wipes out the first address on the list](https://github.com/code-423n4/2023-04-frankencoin-findings/issues/989) | |
| Frankencoin | Medium | [No way to transfer minter role or rennounce to it](https://github.com/code-423n4/2023-04-frankencoin-findings/issues/990) | |
| Frankencoin | QA | [QA Report](https://github.com/code-423n4/2023-04-frankencoin-findings/blob/main/data/juancito-Q.md) | [🏆](https://code4rena.com/reports/2023-04-frankencoin#low-risk-and-non-critical-issues) |
| NextGen | High | [Max minting limit can be bypassed via re-entrancy](https://github.com/code-423n4/2023-10-nextgen-findings/issues/742) | |
| NextGen | High | [Ether from the Auction contract can be stolen on the block the auction ends](https://github.com/code-423n4/2023-10-nextgen-findings/issues/735) | |
| NextGen | High | [Highest bidder can cancel their bid to win auctions for free](https://github.com/code-423n4/2023-10-nextgen-findings/issues/733) | |
| NextGen | High | [Adversary can block claimAuction() due to push-strategy to transfer assets to multiple bidders](https://github.com/code-423n4/2023-10-nextgen-findings/issues/734) | [🏆](https://code4rena.com/reports/2023-10-nextgen#h-03-adversary-can-block-claimauction-due-to-push-strategy-to-transfer-assets-to-multiple-bidders) |
| NextGen | Medium | [The owner of the auctioned token does not receive the funds after an auction ends](https://github.com/code-423n4/2023-10-nextgen-findings/issues/738) | |
| NextGen | Medium | [Artist signatures can be forged to impersonate the artist behind a collection](https://github.com/code-423n4/2023-10-nextgen-findings/issues/741) | [🏆](https://code4rena.com/reports/2023-10-nextgen#m-06-artist-signatures-can-be-forged-to-impersonate-the-artist-behind-a-collection) |
| NextGen | Medium | [Auction winner can prevent payments via safeTransferFrom callback](https://github.com/code-423n4/2023-10-nextgen-findings/issues/739) | [🏆](https://code4rena.com/reports/2023-10-nextgen#m-07-auction-winner-can-prevent-payments-via-safetransferfrom-callback) |
| NextGen | Qa | [QA Report](https://github.com/code-423n4/2023-10-nextgen-findings/issues/747) | [🏆](https://code4rena.com/reports/2023-10-nextgen#low-risk-and-non-critical-issues) |
| USSD | High | [`USSDRebalancer::getOwnValuation()` is easy to manipulate as it doesn't use TWAP for getting the pool price](https://github.com/sherlock-audit/2023-05-USSD-judging/issues/287) | |
| USSD | High | [`USSD::UniV3SwapInput()` executes swaps with no slippage protection](https://github.com/sherlock-audit/2023-05-USSD-judging/issues/229) | |
| USSD | High | [The protocol can't rebalance because `USSD::UniV3SwapInput()` will revert as it is missing the `deadline` when creating the `ExactInputParams` for the swap](https://github.com/sherlock-audit/2023-05-USSD-judging/issues/226) | |
| USSD | High | [`StableOracleWBTC::getPriceUSD()` is using ETH/USD as its price feed](https://github.com/sherlock-audit/2023-05-USSD-judging/issues/121) | |
| USSD | High | [`getPriceUSD` in `StableOracleDai` is miscalculated with wrong decimals from the `priceFeedDAIETH` Chainlink feed](https://github.com/sherlock-audit/2023-05-USSD-judging/issues/103) | |
| USSD | High | [`StableOracleDAI` calculates getPriceUSD with inverted base/rate tokens for Chainlink price](https://github.com/sherlock-audit/2023-05-USSD-judging/issues/102) | [🏆](https://audits.sherlock.xyz/contests/82/report) |
| USSD | High | [Static oracles in `StableOracleDAI` and `StableOracleWBGL` have wrong addresses](https://github.com/sherlock-audit/2023-05-USSD-judging/issues/95) | |
| USSD | High | [`ethOracle` is not defined in `StableOracleDAI` making `getPriceUSD` always revert](https://github.com/sherlock-audit/2023-05-USSD-judging/issues/93) | |
| USSD | High | [Missing access control on `burnRebalancer` allows unrestricted burning of USSD tokens by anyone affecting pool balance on rebalance](https://github.com/sherlock-audit/2023-05-USSD-judging/issues/86) | |
| USSD | High | [Missing access control on `mintRebalancer` allows unrestricted minting of USSD tokens by anyone affecting pool balance on rebalance](https://github.com/sherlock-audit/2023-05-USSD-judging/issues/85) | |
| USSD | Medium | [`latestRoundData` from Chainlink might return stale or incorrect results](https://github.com/sherlock-audit/2023-05-USSD-judging/issues/104) | |
| USSD | Medium | [There is no method for redeeming DAI to prevent negative scenarios described in the whitepaper](https://github.com/sherlock-audit/2023-05-USSD-judging/issues/218) | |
| USSD | Medium | [Collateral tokens will be stuck on the contract and will be unusable after calling USSD::removeCollateral()](https://github.com/sherlock-audit/2023-05-USSD-judging/issues/261) | |
| Footium | Medium | [Some ERC20 tokens can get permanently stuck in the contract due to use of `transfer()`](https://github.com/sherlock-audit/2023-04-footium-judging/issues/252) | |
| Footium | Medium | [Increasing _`maxGenerationId` allows extra minting of academy players on previous seasons](https://github.com/sherlock-audit/2023-04-footium-judging/issues/277) | |
| Footium | Medium | [One extra academy player can be minted per season due to mischeck in `mintPlayers`](https://github.com/sherlock-audit/2023-04-footium-judging/issues/273) | |
| Gravita | Low | [Out of gas in collectFees](https://github.com/Gravita-Protocol/Gravita-SmartContracts/issues/222) | |
| Teller | High | [Borrowers can steal lenders principal without providing collateral by frontrunning `lenderAcceptBid` and updating the bid](https://github.com/sherlock-audit/2023-03-teller-judging/issues/250) | |
| Teller | High | [Adversary can modify the commited collateral of any bid at any time leading to lost or locked assets and DOS of the protocol](https://github.com/sherlock-audit/2023-03-teller-judging/issues/280) | |
| Teller | Medium | [Marketplaces owners can frontrun `submitBid` to steal collateral by modifying market parameters](https://github.com/sherlock-audit/2023-03-teller-judging/issues/289) | |
| Caviar Private Pools | Medium | [Adversary can prevent the creation of any private pools by frontrunning the deployer](https://github.com/code-423n4/2023-04-caviar-findings/issues/567) | |
| Canto Identity Subprotocols | Medium | [Users can end up buying and paying for a different Tray than the one they were trying to acquire](https://github.com/code-423n4/2023-03-canto-identity-findings/issues/130) | [🏆](https://code4rena.com/reports/2023-03-canto-identity#m-07-users-can-end-up-buying-and-paying-for-a-different-tray-than-the-one-they-were-trying-to-acquire) |
| Neo Tokyo | High | [A malicious user can mint a huge amount of BYTES 2.0 tokens for himself](https://github.com/code-423n4/2023-03-neotokyo-findings/issues/366) | |
| Neo Tokyo | High | [Malicious users can claim BYTES rewards after withdrawing all of their LP stake](https://github.com/code-423n4/2023-03-neotokyo-findings/issues/374) | |
| Wenwin | QA | [QA Report](https://github.com/code-423n4/2023-03-wenwin-findings/blob/main/data/juancito-Q.md) | |
| Hats | Medium | [Transactions will be frozen if incorrect settings are used during a deployment on HatsSignerGateFactory](https://github.com/sherlock-audit/2023-02-hats-judging/issues/78) | |
| Biconomy | QA | [QA Report](https://github.com/code-423n4/2023-01-biconomy-findings/blob/main/data/juancito-Q.md) | |
| Polynomial | High | [KangarooVault.removeCollateral doesn't remove the collateral from the position](https://github.com/code-423n4/2023-03-polynomial-findings/issues/261) | |
| Polynomial | Medium | [Invalid and stale prices from Synthethix are not validated](https://github.com/code-423n4/2023-03-polynomial-findings/issues/260) | |
| Polynomial | Medium | [Spamming deposit and withdraw queues](https://github.com/code-423n4/2023-03-polynomial-findings/issues/262) | |
| Polynomial | QA | [QA Report](https://github.com/code-423n4/2023-03-polynomial-findings/blob/main/data/juancito-Q.md) | |
| Asymmetry | High | [Adversary can alter derivatives balances in contracts to steal Ether](https://github.com/code-423n4/2023-03-asymmetry-findings/issues/454) | |
| Asymmetry | Medium | [Precision loss in stake function affects share calculation](https://github.com/code-423n4/2023-03-asymmetry-findings/issues/1044) | |
| Asymmetry | Medium | [Remaining dust from Ether deposits is not returned to users](https://github.com/code-423n4/2023-03-asymmetry-findings/issues/455) | |
| Asymmetry | QA | [QA Report](https://github.com/code-423n4/2023-03-asymmetry-findings/blob/main/data/juancito-Q.md) | |
| Arcade | QA | [Report TBA](https://code4rena.com/contests/2023-07-arcadexyz#top) | 🏆 |
| reNFT | High | Report TBA | |
| reNFT | High | Report TBA | |
| reNFT | High | Report TBA | |
| reNFT | Medium | Report TBA | |
| reNFT | Medium | Report TBA | |
| reNFT | Medium | Report TBA | |
| reNFT | Medium | Report TBA | |
| reNFT | Medium | Report TBA | |
| reNFT | QA | Report TBA | |
| zkSync Era | Medium | Report TBA | |
| zkSync Era | Medium | Report TBA | |
| zkSync Era | QA | Report TBA | |
| Chainlink Staking | Medium | Report TBA | |
| Chainlink Staking | Medium | Report TBA | |
| Chainlink Staking | Medium | Report TBA | |
| Chainlink Staking | Medium | Report TBA | |
| Chainlink Staking | QA | Report TBA | |
| Rubicon v2 | High | [Report TBA](https://code4rena.com/contests/2023-04-rubicon-v2#top) | |
| Rubicon v2 | Medium | [Report TBA](https://code4rena.com/contests/2023-04-rubicon-v2#top) | |
| Rubicon v2 | Medium | [Report TBA](https://code4rena.com/contests/2023-04-rubicon-v2#top) | |
| NextGen | High | Report TBA | |
| NextGen | High | Report TBA | |
| NextGen | High | Report TBA | |
| NextGen | Medium | Report TBA | |
| NextGen | Medium | Report TBA | |
| NextGen | Medium | Report TBA | |
| NextGen | QA | Report TBA | |
| Contest 225 | High | [Report TBA](https://code4rena.com/contests/2023-03-contest-225-contest) | |
| Contest 225 | High | [Report TBA](https://code4rena.com/contests/2023-03-contest-225-contest) | |
| Contest 225 | High | [Report TBA](https://code4rena.com/contests/2023-03-contest-225-contest) | |
| Contest 225 | High | [Report TBA](https://code4rena.com/contests/2023-03-contest-225-contest) | |
| Contest 225 | High | [Report TBA](https://code4rena.com/contests/2023-03-contest-225-contest) | |
| Contest 225 | High | [Report TBA](https://code4rena.com/contests/2023-03-contest-225-contest) | |
| Contest 225 | Medium | [Report TBA](https://code4rena.com/contests/2023-03-contest-225-contest) | |
| Contest 225 | Medium | [Report TBA](https://code4rena.com/contests/2023-03-contest-225-contest) | |
| Contest 225 | QA | [Report TBA](https://code4rena.com/contests/2023-03-contest-225-contest) | |
