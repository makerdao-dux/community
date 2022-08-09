---
title: Approval Voting Surplus Buffer Example
summary: Signal your support for the Surplus Buffer Options.
discussion_link: https://forum.makerdao.com/t/mip40c3-sp52-development-ux-core-unit-budget-dux-001/12085
parameters:
  input_format: 
    type: choose-free
    options: [1,2,3,4]
    abstain: [0]
  victory_conditions:
    - { 
        type: 'and', 
        conditions: [
          { type : approval },
          { type: majority, percent: 50 },
        ]
      }
    - { type : default, value : 3 }
  result_display: approval-breakdown
options:
  0: Abstain
  1: 150 million DAI
  2: 200 million DAI
  3: 250 million DAI (current value)
  4: 300 million DAI
version: v2.0.0   
start_date: 2022-08-08T16:00:00
end_date: 2022-08-11T16:00:00
---

# Poll: Approval Voting Surplus Buffer Example

This is an example of a surplus buffer vote that uses approval voting. The vote will be active for three days, beginning Monday, August 8 2022 at 16:00 UTC.

**This is an approval vote.**

- **You may vote for multiple options.**
- **You should select all the options that you support.**
- **If you wish to abstain, that must be your one and only choice.**

In this vote voters will be able to select from 4 options:

* Option 0: Abstain
* Option 1: Set the Surplus Buffer to 150 million DAI
* Option 2: Set the Surplus Buffer to 200 million DAI
* Option 3: Set the Surplus Buffer to 250 million DAI (current value)
* Option 4: Set the Surplus Buffer to 300 million DAI

## Review

This poll allows the MakerDAO governance community to signal their support for the proposed Surplus Buffer values. They can choose from the following options:

* Set the Surplus Buffer to 150 million DAI
* Set the Surplus Buffer to 200 million DAI
* Set the Surplus Buffer to 250 million DAI (current value)
* Set the Surplus Buffer to 300 million DAI

## Outcomes

**If Option 3 receives the most votes, no further action will be taken at this time.**
**If any of the other options exceeds the votes for Option 3 AND attracts support from a majority of non-abstain votes, then the following actions will be taken:**

* This change will be included in an upcoming Executive Vote as the Protocol Engineering Core Unit's schedule allows.
* It is expected that this Executive Vote will take place within 30 days of this poll passing, absent external factors.
* If the Executive Vote passes, then these changes will become active in the Maker Protocol after the [GSM Pause Delay](https://manual.makerdao.com/parameter-index/core/param-gsm-pause-delay) has expired.

---

## Resources

If you are new to voting in the Maker Protocol, please see the [voting guide](https://community-development.makerdao.com/en/learn/governance/how-voting-works/) to learn how voting works, and this [wallet setup guide](https://community-development.makerdao.com/en/learn/governance/voting-setup/) to set up your wallet to vote.

Additional information about the Governance process can be found in the [Governance](https://community-development.makerdao.com/en/learn/governance) section of the MakerDAO community portal.

To participate in future Governance calls, please [join us](https://github.com/makerdao/community/tree/master/governance/governance-and-risk-meetings) every Thursday at 17:00 UTC.

To add current and upcoming votes to your calendar, please see the [MakerDAO Public Events Calendar](https://calendar.google.com/calendar/embed?src=makerdao.com_3efhm2ghipksegl009ktniomdk%40group.calendar.google.com&ctz=UTC&mode=week&showCalendars=0&showPrint=0).
