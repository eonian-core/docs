---
description: Explantion of our emergency losses prevention system
---

# ⏰ Intelligent Emergency Shutdown

In our protocol, each strategy monitors their losses during investment cycles. If a strategy starts losing money, they automatically go to **Emergency Shutdown Mode** to save money from bigger losses.

### Emergency Shutdown Mode

The Emergency Shutdown Mode - is a state in which the strategy tries to withdraw all funds as quickly and cost-effectively as possible. To activate the strategy, the back Eonian core team will manually check and review the strategy and protocol state, understand what causes losses, and if they cannot occur and market conditions are restored again, reactive strategy.

## For Developers

***

### How it works

Eonian strategies work in polling lending protocol mode every 6 hours (more details in a Strategy lifecycle documentation). Strategies get profit, debt, loss, and gas cost parameters to decide if it should harvest profit.

In some very rare cases, significant losses are possible, for instance, in case of emergency in market conditions.

There are three possible cases:

* If a profit is above zero and the strategy is healthy, then it returns PASS
* If a loss is above zero but still an acceptable level (that is possible due to short market fluctuations), then it returns ACCEPTABLE\_LOSS and will allow to finish a transaction.
* If a loss is above 5% of total debt, then the strategy will be shut down automatically. And withdraw all money on the same harvest cycle.

<div data-full-width="true">

<figure><img src="../.gitbook/assets/Emergency shutdown strategy sequence diagram.drawio (1).png" alt=""><figcaption></figcaption></figure>

</div>

In the picture above, the scheme for the whole flow. The harvest logic tries to collect profit and check how healthy the strategy is. The logic checks if a strategy has losses and how big the losses are.
