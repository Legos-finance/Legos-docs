---
description: >-
  Welcome to Legos.finance docs. This is a live document that will be updated as
  legos.finance evolves. Currently, we aim to provide a high level overview of the
  protocol and its existing components.
---

# Getting Started

{% hint style="info" %}
These docs are still being worked on. Some parts may be unfinished or pending updates.
{% endhint %}

## What is legos.finance?

Legos.finance is a collection of **autonomous, decentralised,** and **non-custodial** smart contracts. It is built on Binance Smart Chain.

Legos.finance was created to address three major problems that confront stablecoin users:

- significant fragmentation in same-peg stablecoins \(there are currently over 5 major USD pegged stablecoins for example\)
- lack of yield in fiat currencies and stablecoins
- lack of protection against permanent capital loss in stablecoins

Legos.finance assets \(hereafter legosAssets\) represent some underlying value peg and are minted/redeemed on-chain via smart contracts.

A user minting an legosAssets interacts only with the Legos.finance contracts, which are non-custodial. This means that no third party ever takes custody of a user's assets. In other words, Legos.finance is a "peer to pool" protocol, where the pool of deposited stablecoins "live" in a non-custodial smart contracts.

legosAssetss are fully backed by a basket of existing stablecoins \(hereafter bAssets\).

Each legosAssets represents a share of liquidity in that legosAssets's basket as well as a stablecoin in its own right. A legosAssets can be used as a medium of exchange, unit of account and store of value.

Each legosAssets is designed to produce an above-average native interest rate \(although this of course is never guaranteed\). This rate is derived from the Legos.finance contracts autonomously and programatically lending bAssets to third party lending protocols, generating interest income. The Legos.finance contracts simultaneously allow for bAssets to be exchanged or "swapped" for a fee. All interest and exchange income is automatically and programmatically sent to legosAssets _savers_.

The Legos.finance protocol is governed by Meta \(`LEGO`\) Governors. Those who have the `LEGO` token can stake \(i.e. deposit in a governance smart contract\) their tokens to become protocol governors, allowing them to govern the Legos.finance protocol.

**Every participant who interacts with Legos.finance has the option to earn** `LEGO`**, either through contributing to its utility \(through EARN\) or by saving a legosAssets \(through SAVE's deposit box\).** `LEGO` **is emitted in this way to facilitate decentralised, collective and user-driven governance.**

### **Characteristics**

- **Non Custodial** - Legos.finance users always have custody of their funds.
- **Robust** - Collateral is diversified across multiple stablecoins.
- **Stable** - legosAssets are stablecoins in their own right.
- **Decentralised** - `LEGO` governs Legos.finance. Every user can earn `LEGO` and participate in Legos.finance collective governance.

### Use cases

- **Composable** **Yield**
  - legosAssetss should earn an outsized yield \(derived from interest income + swap fees + other income\).
- **Traders & Arbitrageurs**
  - Traders can swap stablecoins efficiently using SWAP.
  - Arbitrage opportunities exist using Legos.finance swap.
- **Security conscious stablecoin users**
  - Legos.finance issues assets aim to be more secure than the sum of their parts. Each legosAssets diversifies risk between different asset issuers and stability mechanisms, and caps exposure to any one asset.

### Features

- [Minting and Redemption](legos-assets/massets/minting-and-redemption/#redemption)
- [Swaps](legos-assets/massets/swapping.md)
- [Native Interest Rate](legos-assets/massets/native-interest-rate.md)
- [Meta Governance](legos-assets/functions/governance.md)

{% hint style="success" %}
Now you've got the high level! Time to dig a little deeper.
{% endhint %}
