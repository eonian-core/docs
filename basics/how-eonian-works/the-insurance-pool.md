# The Insurance Pool

Our protocol maintains an insurance pool from which we can pay users’ compensation in case of a hack. This insurance pool is bootstrapped from protocol founders’ money, showcasing our trust in the solution's safety. Insurance from this pool is paid from the revenue of the protocol, not by users directly.

The revenue mainly comes from the investment of assets, which is covered by insurance. At this stage, the protocol works as a traditional yield aggregator. Assets invested in different lending protocols and DEXes, where they earn returns from fees of these protocols. Nevertheless, our protocol works a little bit differently from other yield aggregators. While they prioritize returns on investment, our protocol invests in a way that decreases the risk of investment. It distributes assets between multiple protocols, which decreases the risk of losing all assets in case of a one-protocol hack.

Our protocol and protocols in which we invest are also covered by insurance, which results in much lower investment risks.

To maintain the stability of the pool size, we have in place three strategies:

* We can dynamically adjust the amount of premium that we pay to users. This increases the amount of profits that go directly to the insurance pool.
* We can dynamically decrease the coverage percentage size to influence the demand in our savings account. As a result, it will decrease the new liquidity flow and give the protocol time to grow the insurance pool size until it is able to cover more money.
* In the future, we will also provide liquidity providers the ability to invest directly in the insurance pool. They will be able to earn high APY as a reward for covering the risks for regular holders.
