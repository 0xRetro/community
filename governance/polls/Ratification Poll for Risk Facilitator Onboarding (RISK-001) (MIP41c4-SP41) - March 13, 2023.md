---
title: Ratification Poll for Risk Facilitator Onboarding (RISK-001) (MIP41c4-SP41) - March 13, 2023
summary: This subproposal onboards BA Labs, LLC as a Facilitator for the Risk (RISK-001) Core Unit, represented by @rema and @monet-supply
discussion_link: https://forum.makerdao.com/t/mip41c4-sp41-risk-facilitator-onboarding-risk-001/19739
parameters:
    input_format:
        type: single-choice
        abstain: [0]
    victory_conditions:
        - {
            type: 'and',
            conditions: [
                { type : plurality },
                { type : comparison, comparator : '>=', value: 10000 }
            ]
        }
        - {type : default, value : 2 }
    result_display: single-vote-breakdown
version: v2.0.0
options:
   0: Abstain
   1: Yes
   2: No
start_date: 2023-03-13T16:00:00
end_date: 2023-03-27T16:00:00
---
# Ratification Poll for Risk Facilitator Onboarding (RISK-001) (MIP41c4-SP41) - March 13, 2023

The Governance Facilitators have placed a ratification poll into the [voting system](https://vote.makerdao.com/polling) as part of the responsibilities defined in [MIP51](https://mips.makerdao.com/mips/details/MIP51). This Governance [Poll](https://manual.makerdao.com/governance/governance-cycle/weekly-governance-cycle#weekly-governance-cycle-definitions-mip16c1) will be active for fourteen days beginning on Monday, March 13 at 16:00 UTC.

**This is a binary vote.**
- **You may vote for a single option.**
- **You should vote for the option which you prefer.**
- **If you would accept either option, you should vote 'Abstain'.**

## Review

The community may vote in this poll to express support or opposition to MIP41c4-SP41 being accepted and implemented in the Maker Protocol.

A brief summary of this proposal has been provided by the MIP Author and is shown below:

*This subproposal onboards BA Labs, LLC as a Facilitator for the Risk (RISK-001) Core Unit, represented by @rema and @monet-supply*

Please review the links below to inform your position on this proposal before voting.
* [Canonical Proposal Version](https://github.com/makerdao/mips/blob/2cabd82abb6b908293e94003d05890513704e2ca/MIP41/MIP41c4-Subproposals/MIP41c4-SP41.md)
* [Latest Proposal Version](https://mips.makerdao.com/mips/details/MIP41c4SP41)
* [Proposal Discussion Thread](https://forum.makerdao.com/t/mip41c4-sp41-risk-facilitator-onboarding-risk-001/19739)

## Outcomes

This poll implements a **Minimum Positive Participation** value. The Minimum Positive Participation is currently set to **10,000 MKR**.

**If the votes for the 'Yes' option exceed the votes for the 'No' option AND the votes for the 'Yes' option exceed 10,000 MKR, then the following actions will be taken:**
* The MIP Editors will mark the proposal **Accepted** and the Governance Facilitators will confirm its passage on the Governance and Risk call on Thursday, March 30.
* Any further work required to implement the proposal will be tasked to the relevant [Core Units](https://mips.makerdao.com/mips/details/MIP38#mip38c2-core-unit-state).
* As BA Labs is a Responsible Facilitator in the Decentralized Collateral Scope, this proposal *will* be enacted in the event that the Constitution MIP Set is approved.

**Otherwise, this proposal will be marked as rejected per [MIP51](https://mips.makerdao.com/mips/details/MIP51#mip51c2-ratification-poll).**

---

## Resources

[MIP51: Monthly Governance Cycle](https://mips.makerdao.com/mips/details/MIP51) describes this type of poll and its position and significance within the rest of the governance cycle.

If you are new to voting in the Maker Protocol, please see the [voting guide](https://manual.makerdao.com/governance/voting-in-makerdao/on-chain-governance) to learn how voting works.

Additional information about the Governance process can be found in the [Maker Operational Manual](https://manual.makerdao.com).

To participate in future Governance calls, please [join us](https://forum.makerdao.com/tag/pubcall-:-governance-and-risk) every Thursday at 17:00 UTC.

To add current and upcoming votes to your calendar, please see the [MakerDAO Governance Calendar](https://manual.makerdao.com/makerdao/calendars/governance-calendar).