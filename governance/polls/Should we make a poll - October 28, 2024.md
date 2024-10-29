---
title: Should we make a poll - October 28, 2024
summary: Should we make a poll for PulseMaker
parameters:
    input_format:
        type: single-choice
        abstain: [0]
    victory_conditions:
        - {
            type: 'and',
            conditions: [
                { type : plurality },
                { type : comparison, comparator : '>=', value: 20000 }
            ]
        }
        - {type : default, value : 2 }
    result_display: single-vote-breakdown
version: v2.0.0
options:
   0: Abstain
   1: Yes
   2: No
start_date: 2024-10-28T16:00:00
end_date: 2024-10-31T16:00:00
---
### Poll: How about we make a poll
Looking for your vote

---

### Review

Look it up
---

### Next Steps

Make one

---

### Resources

TODO