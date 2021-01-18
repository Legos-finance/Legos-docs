---
description: Legos.finance unites stablecoins. Legos.finance first legosAsset is LUSD.
---

# legosAssets

## Overview

Legos.finance can support numerous legosAssets. Each legosAssets is pegged to a unique asset, such as fiat currency \(US Dollar\) or a cryptocurrency like Bitcoin. legosAssets are backed by a basket of existing and whitelisted tokenised assets of that same peg, and held by the user.

legosAssets are minted/redeemed permissionlessly and on-chain via the Legos.finance smart contracts.

- **To mint an** `LUSD`, for example, a user sends 1 USDT and receives 1 `LUSD` in return. This whole process is completed autonomously by Legos.finance smart contracts and the user interacting with those smart contracts.
- **To redeem,** the user sends an `LUSD` to the contract and can choose which bAsset to receive in return for the swap fee, which has been set by Meta Governors to be 6 basis points. In the current implementation, if maximum weights are reached, the user will receive a mix of bAssets that are reflective of the current basket composition at a 3 basis point fee. Once the user receives the bAsset\(s\), the legosAssets is then burned, i.e. taken out of circulation. This process is completed autonomously by Legos.finance smart contracts.

Each bAsset has a maximum weight that determines its highest possible weighting in that basket. A maximum weight is important because it creates an upper-bound to the proportion of a bAsset the legosAssets in question is backed by; put differently, it caps a user's exposure to any one stablecoin.

Meta Governors determine:

- The maximum weight of each bAsset;
- Any new bAssets that are to be added should they be deemed secure and stable by Meta Governors. Conversely, a bAsset can be removed should Meta Governors consider it too risky for inclusion in a basket.

Possible future mAssets:

- LBTC \(Bitcoin\)
