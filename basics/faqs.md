# ❓ FAQs

### **How Do Protocols Work?**

Protocols function as smart contracts, programs that operate on a blockchain. Tokens like USDT and WETH also work as smart contracts.

### **What is the difference between CEX and protocol?**

Protocols operate in a decentralized manner. Even if the protocol team is not available, the users will still be able to continue working with the protocol without any issues. Also, usually, the development team does not have access to users’ assets, and it can only make updates to the protocol. Meanwhile, in CEXes, all money is in full control of the company, and they can lock users at any moment or go bankrupt.

### **Why is Eonian safer than wallets?**

Eonian provides insurance to return user money, while wallets do not return money if it is stolen.

### **What if Eonian's investment protocols get hacked?**

Eonian's rigorous audit and monitoring system minimizes this risk. But if such happens, we have an insurance pool from which we will be able to pay money back.

### How does Eonian's insurance against wallet hacks work?

The savings account protocol provides insurance against technical hacks of hot, cold, and hardware wallets. Distinctively, if your assets are maliciously withdrawn or if you lose your private key, Eonian ensures that your funds are returned.

An integral component of the protection system is the user's email, serving as a 2FA channel. It aids in direct communication and swift asset recovery in the unfortunate event of a hack or lost access. Through this email, the user can provide a new wallet address to which we can send reimbursement or transfer money from a wallet that is no longer accessible.

You can think of our decentralized savings account as a bank savings account but on the chain. Assets stored there will be used in a similar way as in a bank but fully automated and independent from any human operations through smart contracts. These smart contracts will invest (in other terms, give “loans”) to different protocols and use revenue from these protocols to fill the insurance pool and pay users’ premiums for holding their assets in the savings account.

The short overview of the process of getting insurance payment works this way:

* The user deposits tokens that he wants to save in our Vault using his wallet and links his email, which will be used for recovery. At this point, all deposited assets are automatically covered.
* Our Vault invests tokens in different lending protocols to earn fees from them. These fees are used to fill the insurance pool, and some parts are shared with a user account.
* When the user noticed that his wallet was hacked, he contacted us using his email to start the recovery process. If assets have not yet been withdrawn by hackers from Vault, we lock them to send them later, when the user will create a new wallet.
* If assets were withdrawn, we start the investigation process. Big wallet hacks, which start to be more common, are easy to identify, so we will be able to pay reimbursement very fast.
* In rare cases, when it is hard to understand the reason for the hack, we can start the dispute process, which will result in voting by our DAO. This DAO includes the same users that hold assets in Eonian, so they are most interested in correct results. You can read more [there](https://app.gitbook.com/o/xgYiQpRVz9aTVJOJJ1bx/s/VE523Jodte4jjJfssUo3/\~/changes/21/protocol/governance-trust-and-dao/dispute-process).
* After that, we pay reimbursement from our insurance pool to a new wallet, which the user will create and provide as an email.

You can get more info about covered cases in [our insurance coverage policy](https://leovs09.notion.site/Insurance-Coverage-Policy-b33c682e8d49426f80fee2bd14525edd#5732d510b435492386ff16a52f5824b5).

You can read more about protocol work there.

{% content-ref url="how-eonian-works/" %}
[how-eonian-works](how-eonian-works/)
{% endcontent-ref %}

### How does insurance compare to existing solutions in the market?

Despite the fact that crypto wallet and DeFi hacks are growing significantly each year, there are still not many insurance protocols in crypto. Also, all of them currently have one common flaw: they are all centralized. So, if you currently want to decrease risks while investing in crypto, you need to be ready to trust some central entity, which is usually the main thing that people want to avoid when going to crypto. This already sounds silly.

On top of that, all of them require paying some fee, in percent of your invested assets. The insurance solutions in crypto are split into two categories:

* The first category is insurance for tokens invested in some DeFi protocols. After he provides liquidity to some protocol like Uniswap or Compound, the user needs to deposit his liquidity tokens to the insurance protocol. This protocol, in the best case, takes some percent of profit, or, in the worst case, some percent of total assets. It is not only complex but requires you to trust some company whose insurance pool size you cannot see.
* The second category provides insurance to wallets directly. There is usually no possibility of staying anonymous or making it autonomous. All known companies in this area operate fully off-chain. So, their fee, insurance pool size, and success coverage cases are unknown.

We are different from all of them, firstly because our protocol is decentralized and transparent. You can check the insurance pool size and total covered liquidity directly on the blockchain at any moment. On top of that, you can vote for coverage cases and control how protocol evolves through DAO. There is currently no one, who has been able to develop a decentralized insurance protocol.

Secondly, our protocol covers both sides of the equation: the wallet and DeFi protocols together. We cover wallets from profits that generate DeFi protocols in which our Vaults invest. Additionally, we cover these DeFi protocols with insurance. So even if they are hacked, you still do not lose money. This way, we can monitor and audit protocols independently, and, as a result, diversify investment between them in the most secure way, in real-time.

Thirdly, we do not take any fees from users’ money. Deposit, withdraw, or assets that you hold do not encounter any fees. So you can just save and forget about money till the moment when they need you. On top of that, we pay a premium on money that the user saves in protocol, so you can even earn passively with us.

[More info on hacks amount](https://www.chainalysis.com/blog/2022-biggest-year-ever-for-crypto-hacking/)

### How is Eonian's insurance pool funded?

This insurance pool is bootstrapped from protocol founders’ money, showcasing our trust in the solution's safety. In the future, any liquidity provider will be able to invest in it to receive returns from insurance fees. Insurance from this pool is paid from the revenue of the protocol, not by users directly.

The revenue mainly comes from the investment of assets, which is covered by insurance. At this stage, the protocol works as a traditional yield aggregator. Assets invested in different lending protocols and DEXes, where they earn returns from fees of these protocols. Nevertheless, our protocol works a little bit differently from other yield aggregators. While they prioritize returns on investment, our protocol invests in a way that decreases the risk of investment. It distributes assets between multiple protocols, which decreases the risk of losing all assets in case of a one-protocol hack.

Our protocol and protocols in which we invest are also covered by insurance, which results in much lower investment risks.

The majority of revenue generated from investment protocols is used to pay and fill the insurance pool, but when the insurance pool is bigger than the need to cover users’ assets, the revenue is redistributed back to users as a premium. This allows users to not only save their assets but also grow them while they are holding them.

### What measures ensure insurance pool sustainability?

Our insurance pool model generally works similarly to traditional banks. They earn money from giving loans and pay from profits in case of losses or other issues. So, even on a high level, you can see that it is a very sustainable model. But crypto still has some differences.

At the current moment, the amount of wallet hacks is between 0.2-2% per year, and with our diversification of investments between protocols, we can expect between 0.5-2% of TVL loss because of DeFi hacks. Also, on average, yield aggregators generate around 5% APY. Our investment strategies historically generate from 5% to 15% APY.

These numbers show that after all covers, we can expect that the insurance pool will grow from -14% to 92% per year. So, even in the case of abnormal growth in hacks during the year and low APY on the DeFi market, we will be able to pay users money. But to maintain the stability of the pool size, we have in place three strategies:

* We can adjust the amount of premium that we pay to users dynamically, to increase the amount of profits that go directly to the insurance pool.
* We can dynamically decrease the coverage percent size, to make for people less interested in saving money in Vaults. As a result, it will decrease the new liquidity flow and give the protocol time to grow the insurance pool size until it is able to cover new money.
* In the future, we will also provide liquidity providers the ability to invest directly in the insurance pool. They will be able to earn high APY as a reward for covering the risks for regular holders.

You can read more about the economic model behind the insurance pool there.

{% content-ref url="../protocol/economic-model/" %}
[economic-model](../protocol/economic-model/)
{% endcontent-ref %}
