---
description: >-
  There, we will take a look at the most simplified risk model version. It does
  not cover all risks but is close enough to a real model to form result
  expectations.
---

# Risks and Revenue Analysis

On the one hand, we provide insurance for multiple people and support many different types of wallets. The chances that all wallets of all people will be hacked are very low. At the same time, the chance that at least one will be hacked is relatively high. It means that at any moment, we need to have an insurance pool that fully covers the average wallet hack amount for all of our users.

There are currently not many statistics directed to wallet hacks on average due to the complexity of differentiating wallet hacks from key losses. But we can base the average amounts on top of the last 5 years of transaction volume received by wallet hacks in relation to the whole transaction volume from illegal actions. According to [Chainalisis](https://www.chainalysis.com/blog/2022-biggest-year-ever-for-crypto-hacking/), it is around 0.2 - 2%.

In such cases, we can expect, on average yearly 2% of wallets will be hacked. For 1000 users, it gives us 20 users hacked per year. Additionally, we currently plan to support the top 20 wallets. For the same 1000 users and with normal distribution, it results in around 50 users being hacked in case of a full wallet hack independently from the user. In other words, from 2% to 5% of protocol users, on average, will be hacked. If we assume that, on average, all users will have a similar amount deposited, then yearly, we will need to cover around 2%-5% of TVL.

Additionally, we need to cover our vaults and investment protocols with insurance from the same pool. We expect to have at least 10 Vaults with 3-5 protocols per Vault. It gives us an expectation of losing around 2% of TVL in case of one protocol hack. With the earlier security measures described, we expect very low chances of protocol hacking. But even in such cases, in total, with wallet hacks, it will require us to maintain no more than 4%-7% of TVL in the insurance pool.

To support the full money flow, we need to have a minimum of 7% of TVL in the insurance pool at any moment. But we can expect that insurance cases do not happen in a normal distribution. They usually tend to happen in short periods of time in big amounts. This requires us to have some buffer to be able to cover picks of reimbursements. For simplicity, we will assume that the reserve part of insurance is the same size as the minimal insurance pool size. So, we need to have 7%-14% of TVL in the insurance pool at any moment.

On average, yield aggregators generate around 5% APY. Our investment strategies historically generate from 5% to 15% APY. This gives us from -2% to 13% returns per year after all hacks are covered. (Cases with abnormal distribution will be described in the whitepaper).

This means that the insurance pool, after all covers, will be able to receive from -14% to 92% APY as insurance payments and support itself in a balanced state on average.
