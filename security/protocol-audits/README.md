---
description: This a page with audits of Eonian protocol conducted by third-party companies
---

# 📑 Audits

Security is critical for us, which is why we need to ensure that our smart contract code doesn't contain any vulnerabilities, exploits, or security issues.  We perform different automated checks through linters and code analyzers for our codebase on each update. You can read about it there:

{% content-ref url="../security-overview.md" %}
[security-overview.md](../security-overview.md)
{% endcontent-ref %}

Additionally, we plan to validate each significant smart contract protocol change through third-party audit firms.  Starting from the first audit performed before our public beta release.

## Audits

### Quick Check by TechRate

First quick check audit of our protocol that was performed by [TechRate ](https://techrate.org/)during closed beta.

{% file src="../../.gitbook/assets/Quick Check Audit (TechRate).pdf" %}

**Summary**

{% hint style="success" %}
No vulnerabilities were found.
{% endhint %}

### Audit by Bunzz

The first full audit was conducted by the [Bunzz team ](https://www.bunzz.dev/audit)as part of the preparation for the public beta release.

{% file src="../../.gitbook/assets/bunz_audit_final.pdf" %}
[Audit source on Bunzz site](https://www.bunzz.dev/audit/reports/057100c0-7023-4247-8c39-31d43e979f76?name=Eonian)
{% endfile %}

**Summary**

{% hint style="success" %}
Only three low-impact potential vulnerabilities were found. All are fixed by our team.
{% endhint %}

## Code Analysis

We conduct automated code analysis on all changes in smart contracts. You can see them in real-time in our [repository](https://github.com/eonian-core/farm). There we collect few latest reports.

### OpenZeppling Defender Code Inspector

Analysis was conducted using the [OpenZepplin Defender](https://www.openzeppelin.com/) Code Inspector tool.&#x20;

{% file src="../../.gitbook/assets/openzepplin-defender-conde-inspector-report.pdf" %}

**Summary**

{% hint style="success" %}
No high or medium-impact potential vulnerabilities were found.&#x20;
{% endhint %}

## Vertical Audits

Our team also performs independent audits on other protocols before we integrate with them:

{% content-ref url="vertical-audits.md" %}
[vertical-audits.md](vertical-audits.md)
{% endcontent-ref %}
