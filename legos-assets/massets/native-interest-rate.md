---
description: "Legos.finance SAVE aims to be an accessible, reliable and high-yielding."
---

# SAVE

## **How does SAVE work?**

Legos.finance assets are designed to generate a native interest rate. This is done through the Legos.finance smart contracts programatically depositing bAssets to decentralised lending markets such, combined with mStable's swap fees and other sources of income.

As interest and fees accrue, new legosAssets are minted and sent to the relevant SAVE contract. This means that `LUSD` is always 1:1 backed. Users who opt in to receive interest by depositing a mAsset balance into the SAVE contract receive these newly minted legosAssets.

## How is the APY displayed?

SAVE shows a historical 7 day moving average APY that has accrued to savers over the last week.

**Who has benefited from this rate?**

Savers who had funds in the SAVE contract for the previous 7 days.

**Is this indicative of future yield?**

This rate has benefited those Savers over the past 7 days, but given the short time between the timestamps, is likely to fluctuate on a regular basis. It is **not** a prediction of future savings rates. There are a lot of factors that regularly affect the rate - basket composition \(and thus yield generated from the bAssets\), SWAP fees and the percentage of the total legosAssets that are held in the Savings contract.

## **Example**

A basket with a total value of 1000 `LUSD`, comprised of equal parts DAI, USDC, USDT, and BUSD earns interest at the following APY derived from the Legos.finance smart contracts automonously lending deposits onto decentralised lending protocols.

- DAI - 5%
- USDC - 4%
- USDT - 3%
- BUSD - 2%

A user deposits 100 `LUSD` into the SAVE contract, alongside others who have already deposited 400 `LUSD`. The SAVE contract has a total of 500 `LUSD` \(50% of LUSD supply\) in it, and over the course of 6 months accrues interest.

At the end of 6 months, assuming no bAssets have breached their max weights, the basket is comprised of the following: 256.25 DAI, 255 USDC, 253.75 USDT, and 252.5 BUSD. In total, the basket has accrued 17.5 USD of value in interest at an average rate of 3.5% APY.

During this period, the platform also collects 10 `LUSD` in total as fees across swaps and redemption activity. This brings the total USD value accrued in the savings contract to 27.5 USD.

During this period, the protocol also received $10 worth of other1 tokens from lending on that protocol and $10 worth of other2 tokens from lending on that protocol. This $20 worth of tokens are autonomously liquidated into `LUSD`. This brings the total USD value accrued in the savings contract to 47.5 USD.

Our user, having contributed one fifth of the total USD in the savings contract over 6 months, earns a corresponding 9.5 `LUSD` in interest.

_NB - This example assumes most of the system to be static over this 6 month term. Realistically, the Legos.finance system is a dynamic one, and returns will be influenced by multiple factors in the system changing on a regular basis, such as users minting and redeeming every day._
