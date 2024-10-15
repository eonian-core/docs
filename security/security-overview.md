---
description: >-
  Security is paramount for Eonian.  We did multiple research and audits to
  increase the security level of DeFi and bring it closer to the traditional
  financial security level.
---

# 🛡️ Security Overview

<div data-full-width="true">

<figure><img src="../.gitbook/assets/image (8) (1).png" alt=""><figcaption></figcaption></figure>

</div>

Security is a more complicated topic in DeFi than in traditional finances. We described the [basis of the DeFi Protocol Triemma](https://blog.eonian.finance/how-defi-works-understanding-protocols-trilemma-a1bb985ff5a3), which prevents the majority of DeFi projects from building safe and reliable protocols.

To solve DeFi security issues, we use many different approaches and strategies, which include:

* **SecOps and Secure SDLC -** We take a security-first approach to ensure that all of our contracts are safe to use. We use enterprise-level software security practices such as SecOps and Secure SDLC, which have already shown great results in the Web2 world but have been overlooked by many Web3 developers.
* **Continuous Monitoring -** We don't stop at the audit of the protocol. Security is not a point where you can stop working. We monitor new breaches and hacks in DeFi to quickly react and fix vulnerabilities where others may be failing. You can see the list of vulnerabilities that we collected and monitor [there](https://leovs09.notion.site/DeFi-Hacks-and-Vulnerabilities-a53964267ca14f87af2a3cc0e40130f8?pvs=74).
* **Rigorous Testing -** We use code review, automated testing, and code coverage reports. We investigate and will build a solution for automated code analysis for vulnerabilities.
* **Attack Analysis -** We collected more than 40 smart contract vulnerabilities and different hack cases. During development, we are making vector attack analyses using these vulnerabilities to find ways the hackers can attack our protocol.
* **Attack Simulations -** We are working on instruments to test protocol by making possible attack simulations on the blockchain before deploying new changes for the mainnet.
* **Multi-layer Testing -** We test our protocol on three different levels: Preview (On testnet), Development (on mainnet, but only accessible to the main team), and Staging (On Mainnet, but accessible to the team and dedicated alpha testers). You can read about it [there](https://github.com/eonian-core/farm/blob/main/docs/protocol-updates-workflow.md).
* **Insurance Pool -** At the current moment, our insurance pool is mainly bootstrapped on founders’ money. It means that in case of any issue or hack, we will first who lose money as we will be forced to repay users their losses. This way, we want to show how much we trust our solution and how motivated we are to keep the safety of the solution at the highest level. The pool is stored separately from the main protocol. This ensures we will be able to repay users’ money even if the Eonian protocol is compromised.
* **Next-generation security system -** We are working on protocol monitoring on blockchain. It will monitor not only our protocol but also the protocols in which we move liquidity. At any moment, monitoring will be able to provide the current state of money flow and the health state's overall investment system. It will also use the mempool of the blockchain to monitor future transactions and to understand when there will be possible hacks or issues that can result in money loss. By using such information, we will be able to automatically send withdrawal transactions before bad transactions are committed and save all money from vulnerable protocols.
* **Third-party Audits** - our smart contract protocol is continuously validated by third-party audit companies before each significant change is deployed to the public.
* **Vertical Audits -** We make independent vertical audits of all protocols in which our protocol invests. Unlike standard audits, which primarily focus on code, vertical audits offer a holistic examination. This includes not only the code but also the operational mechanisms, administrative roles, upgrade paths, and, critically, the team behind the protocol. You can see the list of audits [there](https://www.notion.so/7eb42e1464f84a62bd33353ccf483707?pvs=21).
* **Circuit Breakers** - If our protocol detects significant losses, it automatically pauses itself and withdraws all money to prevent further damage. You can read about it [there](https://www.notion.so/Intelligent-Emergency-Shutdown-Mode-9a00c3924ff2460fbb3b08cc63750c7c?pvs=21).

## Learn More

We place the central place of our development on the security of protocol. You can read more about it on our [website](https://eonian.finance/security). In these documents, you can read additional information and explanations of the different safety systems that we use.

Audits of our protocol by third-party providers:

{% content-ref url="protocol-audits/" %}
[protocol-audits](protocol-audits/)
{% endcontent-ref %}

&#x20;Audits performed by our team for third-party investment protocols:

{% content-ref url="protocol-audits/vertical-audits.md" %}
[vertical-audits.md](protocol-audits/vertical-audits.md)
{% endcontent-ref %}

The system that prevents excessive losses of assets:

{% content-ref url="intelligent-emergency-shutdown.md" %}
[intelligent-emergency-shutdown.md](intelligent-emergency-shutdown.md)
{% endcontent-ref %}

### Additional Resources

* [List of audits](https://leovs09.notion.site/Protocols-Audits-6bfdf8b29fb245b2be8db5c24726e795?pvs=4) conducted by our core development team.
* [The checklist](https://leovs09.notion.site/Crypto-Project-Audit-Checklist-e24414dcd1c94b5f818343d46f25013d?pvs=4) that we use to audit new projects.
* [List of hacks](https://www.notion.so/leovs09/DeFi-Hacks-and-Vulnerabilities-a53964267ca14f87af2a3cc0e40130f8) and resources to fight with them that our core team collected and maintained.
* Series "How We Fight DeFi Vulnerabilities"
  * [Part 1 - Smart Contracts](https://blog.eonian.finance/how-we-fight-defi-vulnerabilities-part-1-smart-contracts-b198e33db9ad)
  * [Part 2 - Flash Loans](https://blog.eonian.finance/how-we-fight-defi-vulnerabilities-part-2-flash-loan-2b9765aaaf76?source=collection\_home---2------5-----------------------)
  * [Part 3 - Economic Exploits](https://blog.eonian.finance/how-we-fight-defi-vulnerabilities-part-3-economic-exploits-2547f936b8e8?source=collection\_home---2------4-----------------------)
  * [Part 4 - Centralized Decision-Making](https://blog.eonian.finance/how-we-fight-defi-vulnerabilities-part-4-centralized-decision-making-accf8e5e5b1c?source=collection\_home---2------2-----------------------)
