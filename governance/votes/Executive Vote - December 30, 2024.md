---
title: Template - [Executive Vote] WPLS Onboarding, DAI Savings Rate Adjustment - December 30, 2024
summary: Onboarding WPLS-A and adjusting the DAI Savings Rate.
date: 2024-12-30T00:00:00.000Z
address: "$spell_address"
---

# [Executive Proposal] WPLS Onboarding, DAI Savings Rate Adjustment - December 30, 2024

MKR Holders should vote for this proposal if they support the following alterations to the Maker Protocol.

If you are new to voting in the Maker Protocol, please see the [voting guide](https://github.com/makerdao/community/blob/master/content/en/learn/governance/how-voting-works.mdx) to learn how voting works, and this [wallet setup guide](https://github.com/makerdao/community/blob/master/content/en/learn/governance/voting-setup.mdx) to set up your wallet to vote.

---

## Executive Summary

If this executive proposal passes, the following **changes** will occur within the Maker Protocol:

- The DAI Savings Rate will be increased from 1% to **4%**, as detailed below.

If this executive proposal passes, the following **additions** will be made to the Maker Protocol:

- WPLS-A (Wrapped Pulse) will be onboarded to the protocol with the initial parameters detailed below.

**Voting for this executive proposal will place your MKR in support of the changes and additions outlined above.**

Unless otherwise noted, the changes and additions listed above are subject to the [GSM Pause Delay](https://manual.makerdao.com/parameter-index/core/param-gsm-pause-delay). This means that if this executive proposal passes, the changes and additions listed above will only become active in the Maker Protocol after the GSM Pause Delay has expired. The GSM Pause Delay is currently set to **48 hours**.

This executive proposal includes an office-hours modifier that means that it **can only be executed between 14:00 and 21:00 UTC, Monday - Friday**. This is to ensure that at least some auction keepers are available to react to unforeseen issues with their bots in the event of early liquidations on new collateral types.

If this executive proposal does not pass within 14 days, then it will expire and can no longer have any effect on the Maker Protocol.

---

## Proposal Details

### Onboard WPLS-A as a New Vault Type

As per this successful [governance poll](https://pulsemaker.win/polling/Qmaa3Vbd), WPLS-A will be onboarded to the Maker Protocol with the following parameters, if this executive proposal passes.

#### Initial Vault Parameters

- **Underlying Collateral**: WPLS (Wrapped Pulse)
- **[Stability Fee](https://manual.makerdao.com/parameter-index/vault-risk/param-stability-fee)**: 10%
- **[Liquidation Ratio](https://manual.makerdao.com/parameter-index/vault-risk/param-liquidation-ratio)**: 175%
- **[Debt Floor (`dust`)](https://manual.makerdao.com/parameter-index/vault-risk/param-debt-floor)**: 0 DAI
- **[Maximum Debt Ceiling (`line`)](https://manual.makerdao.com/module-index/module-dciam#maximum-debt-ceiling-line)**: 5 million DAI  
- **[Target Available Debt (`gap`)](https://manual.makerdao.com/module-index/module-dciam#target-available-debt-gap)**: 3 million DAI  
- **[Ceiling Increase Cooldown (`ttl`)](https://manual.makerdao.com/module-index/module-dciam#ceiling-increase-cooldown-ttl)**: 8 hours

#### Liquidation Parameters

- **[Auction Price Function (`calc`)](https://manual.makerdao.com/parameter-index/collateral-auction/param-auction-price-function)**: Exponential Stair Step
- **[Price Change Multiplier (`cut`)](https://manual.makerdao.com/parameter-index/collateral-auction/param-auction-price-function#cut)**: 0.99  
- **[Price Change Interval (`step`)](https://manual.makerdao.com/parameter-index/collateral-auction/param-auction-price-function#step)**: 60 seconds
- **[Auction Price Multiplier (`buf`)](https://manual.makerdao.com/parameter-index/collateral-auction/param-auction-price-multiplier)**: 1.15 (115%)
- **[Liquidation Penalty (`chop`)](https://manual.makerdao.com/parameter-index/vault-risk/param-liquidation-penalty)**: 15%

#### Limits

- **[Local Liquidation Limit (`ilk.hole`)](https://manual.makerdao.com/parameter-index/collateral-auction/param-local-liquidation-limit)**: 2 million DAI
- **[Maximum Auction Drawdown (`cusp`)](https://manual.makerdao.com/parameter-index/collateral-auction/param-max-auction-drawdown)**: 0.15 (15%)
- **[Maximum Auction Duration (`tail`)](https://manual.makerdao.com/parameter-index/collateral-auction/param-max-auction-duration)**: 8,400 seconds
- **[Breaker Price Tolerance (`tolerance`)](https://manual.makerdao.com/parameter-index/collateral-auction/param-breaker-price-tolerance)**: 0.20 (20%)

---

### DAI Savings Rate Adjustment

As per this [governance poll](https://vote.makerdao.com/polling/914), the following changes will be made to the Maker Protocol, if this executive proposal passes:

- Increase the [DAI Savings Rate](https://manual.makerdao.com/parameter-index/core/param-dai-savings-rate) from 1% to **4%**.

Please review the [discussion thread](https://forum.makerdao.com/t/parameter-changes-proposal-ppg-omc-001-24-november-2022/18925#dai-savings-rate-adjustment-3) containing information about the DAI Savings Rate Adjustment to inform your position before voting.

For more information on the DAI Savings Rate please refer to the documentation [here](https://manual.makerdao.com/parameter-index/core/param-dai-savings-rate).

---

## Review

Community debate on these topics can be found on the MakerDAO [Governance forum](https://forum.makerdao.com/). Please review any linked threads to inform your position before voting.

Additionally, these changes may have been discussed further in recent Governance calls. [Video](https://www.youtube.com/playlist?list=PLLzkWCj8ywWNq5-90-Id6VPSsrk4OWVan) for these calls is available to review.

---

## Resources

Additional information about the Governance process can be found in the [Governance](https://community-development.makerdao.com/en/learn/governance) section of the MakerDAO community portal.

To participate in future Governance calls, please [join us](https://github.com/makerdao/community/tree/master/governance/governance-and-risk-meetings) every Thursday at 17:00 UTC.

To add current and upcoming votes to your calendar, please see the [MakerDAO Public Events Calendar](https://calendar.google.com/calendar/embed?src=makerdao.com_3efhm2ghipksegl009ktniomdk%40group.calendar.google.com&ctz=UTC&mode=week&showCalendars=0&showPrint=0).
