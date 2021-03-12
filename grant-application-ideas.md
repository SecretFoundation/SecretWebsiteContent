---
layout: ~/layouts/MainPageLayout
---

<template v-slot:title>

## Secret Network Grant Application Ideas

</template>

<slim-column>

***Secret Apps***


**Secret DeFi**
is a privacy-first, front-running resistant DeFi ecosystem. After the release of SNIP-20 (a fungible privacy token standard) and the launch of the Secret Network - Ethereum bridge on mainnet, the community is now getting ready for the launch of SecretSwap, the first front-running resistant, cross-chain DEX!
With the building blocks of Secret DeFi ready, we welcome the community to submit grant proposals to build any of the applications below:

**Staking** derivatives to create capital efficiency in the Secret Network. Staking derivatives allow staked SCRT to be used for further yield opportunities in Secret DeFi. Here’s one attempt on a product roadmap.

**Variable interest lending products**: Either Secret-based implementations of ETH DeFi projects such as Compound or Aave, or brand new lending products leveraging Secret’s unique properties.

**Algorithmic stable coin projects** (such as Maker-type implementations). We believe it’s critical for the Web3 ecosystem to have a decentralized stable coin with privacy.

**Dark pools (private orderbook exchange) for privacy preserving trading.** A Dark Pools secret contract manages the encrypted order book in its state and can run multiple order matching methods such as Market / Limit / Stop-Loss orders. You can build on the SecretAuction repo, which uses a single sided orderbook.

**Fixed income products:** Fixed interest lending / borrowing products with insurance / liquidity pool to guarantee fixed payments.

**Credit scoring and under collateralized lending** using liquidity / insurance pools and Secret Oracles that tap into Web2 data sources like Plaid or centralized exchange balances. Undercollateralized loans can be built on top of Secret Network using on-chain privacy-preserving reputation credit scoring contracts.

**Advanced AMM / CFMM DEXs** optimized for low slippage trading (like Curve) or multiple pools (like Balancer) to create decentralized index funds. We encourage participants to launch the protocol with indices like Privacy Index, Data economy index etc.
Derivatives and Contract for Difference products with SCRT and SNIP20 collaterals.

**Options contracts:** Put / call options based on an orderbook or AMM model with SCRT and SNIP20 collaterals.

**Synthetic Asset creation** with SCRT and SNIP20 collaterals.

**Decentralized Perpetual Swap products** leveraging SecretSwap (with vAMM similar to Perpetual Protocol with front-running resistance for more efficient capital deployment).

**Insurance products** for Secret DeFi.

**Decentralized Substack:** Build a decentralized content (audio, blog) monetization tool for content stored on IPFS or another decentralized storage platforms. You can refer to this article for more information. Padlock and SecretVault contracts can also be an inspiration for access control related cases.

**Ocean Data Token integration:** Integrate Ocean Data Tokens to SecretVaults to allow trustless access to data token content.

**Dead Man Switch:** An event on the Secret Network (such as block numbers / elapsed time or a payment) triggers a secret contract to release a "secret" either to a selected recipient (private output) or the entire network (public state).Note: SecretVaults require whitelisted addresses to prevent offline data leakage attacks. Please get in touch with us to discuss secret contract security models.

**Data Marketplaces**

Trustless private computations for Ocean Protocol data marketplace.

Crowd-sourced signal generation with staking incentives for SNIP20 and synthetic (Mirror Protocol) asset trading.

Decentralized and privacy preserving machine learning use-cases (image recognition etc.)
 
 
**Secret NFTs**

Finalize SNIP-721 standard that allows for private ownership of NFTs and private metadata in NFTs. **(funded / in process)**

Create SNIP-1155, based on ERC-1155 standard that allows for private ownership of NFTs and private metadata in NFTs
Secret Lootbox for Ethereum games: Lootbox NFTs used in Ethereum games would be represented with secretNFTs to reveal rewards only after NFT is claimed.

**Decentralized Governance and DAOs**

SecretFund: Build a DAO funded by block rewards of delegators participating in the DAO. Delegators receive governance tokens proportional to their contribution. Governance tokens determine how the funds in SecretFund are managed.

SecretLaunchPad: Create a crowdfunding mechanism like Polkastarter, where Secret Network participants can support the launch of products built on Secret Network or Ethereum (using the bridge). Using SNIP-20s, secretLaunchPad would allow anonymous investments.

Encrypted group messaging: Build a decentralized Signal / Telegram designed for encrypted group messaging. Determine a group admin to manage access rights to group and use secret contracts with encrypted state to host your secret group conversations.

***Ecosystem***

Secret Network - BTC Bridge.

Secret Network - Polkadot Bridge: Either building on Wormhole or a bridge to EVM substrates like Moonbeam or Plasm

SecretTunnel - Interoperable Secrets: Create a contract to verify state changes and allow asset transfers between Secret Network and L2 
Secret Network forks for big data and high throughput use-cases.

**Oracles**

Secret Oracles: Build TLS connection from validator enclaves to certain APIs to create private data feed for secret contracts (i.e. Binance and other exchange balances for decentralized credit scoring / leverage)

Public API oracles: Allow Secret Network validators (or nodes) to query public APIs for on-chain secret contract based oracle. Validators would reach on-chain consensus on inputs

Oracle support for Secret Network using Band Protocol

Oracle support for Secret Network using Chainlink

**Developer tools and improvements**

Tooling for one-click-run-and-deploy of contracts

Network forks suitable for Big Data and high throughput (< 1 second block time for orderbook based DEXs). This grant can be combined with Secret Tunnel

Create a library for running Secret Contract integration tests (like how Truffle uses Mocha/JS for Solidity)
Network improvements

***Protocol Improvements***

ML Library that can run on-chain (requires deterministic floats or fixed-point support).

Differential privacy library for getter methods.

Light-client validation inside of the enclave in order to validate untrusted data (Bitcoin and Ethereum lite-clients etc).

Fully Homomorphic encryption backend.
 
</slim-column>