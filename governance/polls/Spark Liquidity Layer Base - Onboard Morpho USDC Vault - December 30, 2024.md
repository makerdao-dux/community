---
title: Spark Liquidity Layer Base - Onboard Morpho USDC Vault - December 30, 2024
summary: Signal your support or opposition to onboarding the Morpho USDC Vault to the Spark Liquidity Layer on Base.
discussion_link: https://forum.sky.money/t/27-dec-2024-proposed-changes-to-spark-for-upcoming-spell/25760
parameters:
    input_format: single-choice
    victory_conditions:
        - { type : plurality }
    result_display: single-vote-breakdown
version: v2.0.0
options:
   0: Abstain
   1: Yes
   2: No
start_date: 2024-12-30T16:00:00
end_date: 2025-01-02T16:00:00
---
# Poll: Spark Liquidity Layer Base - Onboard Morpho USDC Vault - December 30, 2024

The Governance Facilitators have placed a Governance Poll into the voting system on behalf of the Stability Facilitators. This Governance [Poll](https://sky-atlas.powerhouse.io/#A.1.9.1_Operational_Weekly_Cycle-b189fa17-57a9-4d4e-9780-0ce4efd94211%7C0db30308) will be active for three days beginning on Monday, December 30 at 16:00 UTC.

**This is a binary vote.**
- **You may vote for a single option.**
- **You should vote for the option which you prefer.**
- **If you would accept either option, you should vote 'Abstain'.**

## Review

The community can vote in this poll to express support or opposition to onboarding the Morpho USDC Vault to the Spark Liquidity Layer on Base with the following parameters:
* `max amount` (maximum amount that can be executed at once) for deposits: **50 million USDC**.
* `slope` (recharging rate of capacity): **25 million USDC per day**.
* `max amount` for withdrawals: **unlimited**.

The relevant vault address is [0x305E03Ed9ADaAB22F4A58c24515D79f2B1E2FD5D](https://basescan.org/address/0x305E03Ed9ADaAB22F4A58c24515D79f2B1E2FD5D).

The following changes will be made to the vault:

- Add the USDC idle market with unlimited (type(uint184).max) supply cap.
- Add the RELAYER multisig as an allocator.
- Increase the supply cap on cbBTC/USDC market ([0x9103c3b4e834476c9a62ea009ba2c884ee42e94e6e314a26f04d312434191836](https://app.morpho.org/market?id=0x9103c3b4e834476c9a62ea009ba2c884ee42e94e6e314a26f04d312434191836&network=base)) to **100m illion USDC**.

Please review the discussion [thread](https://forum.sky.money/t/27-dec-2024-proposed-changes-to-spark-for-upcoming-spell/25760) to help inform your position before voting.

## Outcomes

**If the votes for the 'Yes' option exceed the votes for the 'No' option then the following actions will be taken:**
* This change will be included in an upcoming Executive Vote.
* It is expected that this Executive Vote will take place within 30 days of this poll passing, absent external factors.
* If the Executive Vote passes, then these changes will become active in the Sky Protocol after the [GSM Pause Delay](https://sky-atlas.powerhouse.io/#A.1.8.2.1_Pause_Delay-a98b8227-95f6-4711-9d8d-f52cbc6ad2d0%7C0db30758e055) has expired.

**If the votes for the 'No' option equal or exceed the votes for the 'Yes' option then no further action will be taken at this time.**

---

## Resources

If you are new to voting in the Sky Protocol, please see the [voting guide](https://manual.makerdao.com/governance/voting-in-makerdao/on-chain-governance) to learn how voting works.

Additional information about the Governance process can be found in the [Operational Manual](https://manual.makerdao.com).

To add current and upcoming votes to your calendar, please see the [Sky Governance Calendar](https://manual.makerdao.com/makerdao/calendars/governance-calendar).
