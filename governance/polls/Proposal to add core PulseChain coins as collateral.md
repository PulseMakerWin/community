---
title: Proposal to add core PulseChain coins as vault collateral. - November 21, 2024
summary: Signal your support or opposition to the proposal.
discussion_link: https://t.me/PulseChainMKR
parameters:
    input_format:
        type: single-choice
        abstain: [0]
    victory_conditions:
        - {
            type: 'and',
            conditions: [
                { type : plurality },
                { type : comparison, comparator : '>=', value: 500 }
            ]
        }
        - {type : default, value : 0 }
    result_display: single-vote-breakdown
version: v2.0.0
options:
   0: Abstain
   1: Yes
   2: No
start_date: 2024-11-21T23:00:00
end_date: 2024-12-6T23:00:00
---

# Poll: Proposal to add core PulseChain coins as vault collateral. - November 21, 2024

This proposal requests the onboarding of HEX, Pulse, and PulseX as collateral types in PulseMaker to peg pDAI to $1. The authors advocate for the use of these assets to support the pDAI peg without inflating the current supply, ensuring over-collateralisation.

By submitting this proposal, we are exercising our right to Freedom of Speech, Movement and Assembly. The authors represent the interests of the pDAI and Pulsechain community, who believe in the creation of a decentralised, censorship-resistant stablecoin in support of free and open financial systems controlled by the people. 

Pegging pDAi is essential to both PulseChain achieving it’s goal of becoming the world’s largest decentralised blockchain and the formation of our own economic area, commonly referred to as “Hexico”.

**This is a binary vote.**

- **You may vote for a single option.**
- **You should vote for the option which you prefer.**
- **If you would accept either option, you should vote 'Abstain'.**

## Review

The community can vote in this poll to express support or opposition to the proposal. For further details, refer to the discussion in the [Telegram chat](https://t.me/PulseChainMKR).

## Proposal Summary

The authors propose onboarding HEX, Pulse, and PulseX as collateral types with the primary goal of enabling the Origin Address (OA) to back the existing pDAI supply. This approach aligns with the community’s commitment to financial freedom and decentralisation.  

### Proposed Collateral Overview

| Token      | Description                                                                                         | Address                                      |
|------------|-----------------------------------------------------------------------------------------------------|----------------------------------------------|
| **HEX**    | Blockchain certificate of deposit.                                                                 | `0x2b591e99afE9f32eAA6214f7B7629768c40Eeb39` |
| **Pulse**  | PulseChain native token, used for fees and staking.                                                 | `0xA1077a294dDE1B09bB078844df40758a5D0f9a27` |
| **PulseX** | PulseChain DEX token, incentivising liquidity and buy-and-burn mechanisms.                         | `0x95B303987A60C71504D99Aa1b13B4DA07b0790ab` |

### Parameters and Initial Settings

| Parameter                 | HEX   | Wrapped Pulse | PulseX |
|---------------------------|-------|---------------|--------|
| Proposed Debt Ceiling     | 0     | 0             | 0      |
| Collateralisation Ratio   | 110%  | 110%          | 110%   |
| Liquidation Ratio         | 10%   | 10%           | 10%    |
| Stability Fee             | 0%    | 0%            | 0%     |

*Note: These parameters may be revisited after a 10-day pause.*

---

### Objectives and Benefits

- **Peg Support Without Inflation**: Support the pDAI peg without minting additional pDAI supply.  
- **PulseChain Ecosystem Growth**: Enhance liquidity for PRC20 tokens, promoting parity within the ecosystem.  
- **Decentralised Stability**: Strengthen pDAI as a decentralised alternative to fiat currencies.  

---

### Non-Disclosure Agreement

The authors agree to treat correspondence regarding this proposal with confidentiality unless waived by Richard Heart or his team.

---

### Conclusion

This proposal seeks to onboard HEX, Pulse, and PulseX as collateral types in PulseMakerDAO, enabling the OA to back existing pDAI supply and secure its peg to $1 while promoting decentralisation and financial freedom.  

---

### Authors and Contacts

- **DcentraliseMe**  
  - Role: Community Member  
  - Contact: Telegram @DcentraliseMe  

- **NineIronCapital**  
  - Role: Community Member  
  - Contact: Telegram @NineIronCapital  

- **Konenstein**  
  - Role: Community Member  
  - Contact: Telegram @Konenstein  

- **Freedom_777**  
  - Role: Community Member  
  - Contact: Telegram @FREEDOM_Tokens777  

