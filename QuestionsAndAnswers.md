# TSC Budget Proposal: Questions & Explanations

  - [TSC Budget Proposal](#tsc-budget-proposal-questions--explanations)
    - [Questions](#questions)
      - [Why is this budget not broken down into line items?](#why-is-this-budget-not-broken-down-into-line-items)
      - [Why not perform tendering directly on-chain?](#why-not-perform-tendering-directly-on-chain)
      - [How will the TSC ensure nobody is getting paid twice?](#how-will-the-tsc-ensure-nobody-is-getting-paid-twice)
      - [How does this proposal support competitive tender?](#how-does-this-proposal-support-competitive-tender)
      - [What is the TSC’s approach to reconciliation, changes and improvements to this proposal?](#what-is-the-tscs-approach-to-reconciliation-changes-and-improvements-to-this-proposal)
      - [What is the TSC’s position on Competing/Overlapping Proposals?](#what-is-the-tscs-position-on-competingoverlapping-proposals)
      - [What is the TSC’s position on Risk Management?](#what-is-the-tscs-position-on-risk-management)
      - [How does this proposal differ from the budget that was submitted by the TSC to Intersect?](#how-does-this-proposal-differ-from-the-budget-that-was-submitted-by-the-tsc-to-intersect)
      - [What is the TSC position on Value for Money?](#what-is-the-tsc-position-on-value-for-money)
      - [There appear to be some members of the TSC who are employed by or have some allegiance to companies that could be recipients of funds through the public tendering process proposed here. How does the TSC plan to addresses these perceived conflicts of interest?](#there-appear-to-be-some-members-of-the-tsc-who-are-employed-by-or-have-some-allegiance-to-companies-that-could-be-recipients-of-funds-through-the-public-tendering-process-proposed-here-how-does-the-tsc-plan-to-addresses-these-perceived-conflicts-of-interest)
      - [How will the funds be protected and distributed? If a multisig is used, what measures are in-place to protect the named individuals on the TSC from being socially-engineered or physically targeted?](#how-will-the-funds-be-protected-and-distributed-if-a-multisig-is-used-what-measures-are-in-place-to-protect-the-named-individuals-on-the-tsc-from-being-socially-engineered-or-physically-targeted)
      - [While I appreciate the intent to have domain experts within the TSC assess the technical feasibility of proposals through the tendering process, I worry that using TSC as a "middleman" between vendors and the greater community could cause unnecessary bloat, delays, or conflicts. How does the TSC intend to keep pushing the work forward such that vendors finish their deliverables within reasonable timeframes?
](#while-i-appreciate-the-intent-to-have-domain-experts-within-the-tsc-assess-the-technical-feasibility-of-proposals-through-the-tendering-process-i-worry-that-using-tsc-as-a-middleman-between-vendors-and-the-greater-community-could-cause-unnecessary-bloat-delays-or-conflicts-how-does-the-tsc-intend-to-keep-pushing-the-work-forward-such-that-vendors-finish-their-deliverables-within-reasonable-timeframes)
      - [Can you confirm whether people who have submitted budgets that overlap with the TSC budget are willing to bid?](#can-you-confirm-whether-people-who-have-submitted-budgets-that-overlap-with-the-tsc-budget-are-willing-to-bid)
      - [TSC member elections are one vote per intersect member, but this poses a somewhat high risk of attack, so will it be possible to switch to DRep voting for TSC elections from the next October election?](#tsc-member-elections-are-one-vote-per-intersect-member-but-this-poses-a-somewhat-high-risk-of-attack-so-will-it-be-possible-to-switch-to-drep-voting-for-tsc-elections-from-the-next-october-election)
      - [It seems that many of the proposed development items for this budget already are covered in IOG's core development budget proposal. I was under the assumption that IOG and Intersect members have been coordinating rather closely, but if there's this much confusion over who's responsible for core development costs I'm afraid that may not be true. I support Intersect, but until there is more clarity or some kind of reconsiliation in the funding appropriations process I'll favor the IOG proposal over this.](#it-seems-that-many-of-the-proposed-development-items-for-this-budget-already-are-covered-in-iogs-core-development-budget-proposal-i-was-under-the-assumption-that-iog-and-intersect-members-have-been-coordinating-rather-closely-but-if-theres-this-much-confusion-over-whos-responsible-for-core-development-costs-im-afraid-that-may-not-be-true-i-support-intersect-but-until-there-is-more-clarity-or-some-kind-of-reconsiliation-in-the-funding-appropriations-process-ill-favor-the-iog-proposal-over-this)
      - [Is it possible to list all budgets (excluding IOG) that have overlapping scopes with the TSC Budget?](#is-it-possible-to-list-all-budgets-excluding-iog-that-have-overlapping-scopes-with-the-tsc-budget)
      - [Where did $299,000 applied-to-every-engineer figure come from exactly?](#where-did-299000-applied-to-every-engineer-figure-come-from-exactly)
        
## Questions

### Why is this budget not broken down into line items?

There are two reasons. The first reason is that one major concern for the TSC in preparation of this budget was ensuring the continuity of expertise and skills related to development of the core node. Losing key contributors is often the death knell for many open source projects, and we wish to avoid this.

Most of these contributors work full-time on Cardano on both maintenance and feature development. Most likely they would not be available to work, say, only 30-40% on maintenance \- they would move to other projects. Securing the resources allows flexibility to alter the feature development priorities in the current year without threatening core maintenance activities.

The second reason is that such a breakdown would be necessarily fictitious. Without going through a process of competitive tender, the TSC does not have detailed cost breakdowns for each item. Such competitive tender will progress steadily throughout the year as projects become viable.

### Why not perform tendering directly on-chain?

An alternative to “paying for people”, as this proposal puts forward, would be for suppliers to directly submit proposals on-chain. This would have a number of disadvantages:

1. Proposals are not independent. Work affecting the core node (or future alternative nodes should they become widely used) must be coordinated in order to ensure that:  
   1. Any combination of proposed items is coherent \- for example, two proposals making changes to the reward calculation may not, if both carried out, lead to a function that makes any sense.  
   2. Any combination of proposed items can be worked on simultaneously \- e.g. it would make little sense to work on two items which require modifying the same sections of code, since they are likely to clash.  
   3. Any combination of proposed items is compatible and does not violate any chain security or performance requirements.  
2. Technical work must be integrated. This requires coordination with maintainers, testers and potentially other people working on similar areas. There are likely to be costs associated with such integration that must be considered as part of any proposal.  
3. Any work affecting consensus or ledger rules requires a hard fork and must therefore be coordinated with SPOs, providers of downstream tools etc.   
4. In order to ensure sufficient work to employ people, suppliers might be tempted to propose more work than they have the capacity for, in case some proposals are unsuccessful.

### How will the TSC ensure nobody is getting paid twice?

The TSC will propose to issue one or more maintenance/retainership contracts, whose purpose is to ensure the retention of those experts currently maintaining the core node infrastructure. Such contracts will name specific individuals and their roles, and require that suppliers inform us if said individuals leave or are replaced by others.

Any supplier bidding for a feature-based contract will be required to name the individuals working on that contract and to zero-rate any work carried out by individuals named in the retainership contracts. Suppliers and Intersect shall routinely publish reports of how much time for people employed on retainership contracts is spent on maintenance vs feature development.

### How does this proposal support competitive tender?

The TSC aims not only to retain existing experience but to grow the number of people contributing to core Cardano development. As such this proposal requests additional ADA beyond the retainership contract to support bringing new developers into the system.

When evaluating value for money, the TSC will compare costs including the value of any people zero-rated due to their being named in a retainership contract \- that is, costs will be compared assuming those people had been charged at full rate.

### What is the TSC’s approach to reconciliation, changes and improvements to this proposal?

While the TSC feels strongly that the principles of probity, order, honesty, security, sustainability, longevity and a proper respect for the governance process are essential to ensure sustainable core infrastructure development and maintenance, this proposal is presented to the community as a vehicle for constructive discussion.

The TSC recognizes the need for feedback and the continued inclusion of thoughts, suggestions and sentiment towards core development from all parts of the ecosystem. The TSC openly admits that it does not have all the answers. However this initial proposal serves as a reference point for an open, ongoing conversation. The TSC welcomes feedback through the reconciliation process and wider ecosystem collaboration, and is open to suggestions and changes to any part of the proposal as currently suggested. 

### What is the TSC’s position on Competing/Overlapping Proposals?

Following proper technical evaluation, the TSC is open to overseeing other core infrastructure work that the community wishes to progress under the same conditions that it is proposing.  Such work must be technically feasible, compatible with other core infrastructure work, have a proper plan for integration and rollout, meet all necessary security and other audit requirements, be aligned with the agreed community roadmap, and not be exploitative.  Proposed budgets may need to be adjusted to account for overlaps.

### What is the TSC’s position on Risk Management?

The TSC views proper management of risk as being essential to the delivery of all funded work.  It has identified a number of systemic risks and will update the proposal at a future date with a full risk analysis, including specific mitigations.
Each funded work item is expected to address technical risks in a sensible and consistent way.

### How does this proposal differ from the budget that was submitted by the TSC to Intersect?

The main difference is that this proposal is restricted to 12 months starting in June 2025.  The actual proposal is, of course, also much more detailed.

### What is the TSC position on Value for Money?

The TSC will use its knowledge and experience to obtain good value for money for any work that it oversees.
The TSC's position is that the lowest bid only reflects the best value for money if the best developer team is being employed.

### There appear to be some members of the TSC who are employed by or have some allegiance to companies that could be recipients of funds through the public tendering process proposed here. How does the TSC plan to addresses these perceived conflicts of interest?

We acknowledge this as a valid concern that has been addressed by Intersect.  There is a code of conduct that covers conflicts of interest, plus public accountability.  As per current practice, any TSC members would be expected to disclose conflicts of interest and recuse themselves from any votes or decisions with regard to those areas. Voting records and meetings would also be public such that this could be verified

### How will the funds be protected and distributed? If a multisig is used, what measures are in-place to protect the named individuals on the TSC from being socially-engineered or physically targeted?

TSC members have no direct access to funds.  Funds will be protected by a multi-party smart contract which is under development for which the TSC would be one signatory with Intersect and independent auditors.  This contract is expected to be used for all budget proposals, not just those that the TSC will administer.  The TSC will approve the release of funds only once technical milestone reviews have been completed.  This process has been trialled on various contracts during 2024/25.

### While I appreciate the intent to have domain experts within the TSC assess the technical feasibility of proposals through the tendering process, I worry that using TSC as a "middleman" between vendors and the greater community could cause unnecessary bloat, delays, or conflicts. How does the TSC intend to keep pushing the work forward such that vendors finish their deliverables within reasonable timeframes?

The TSC was reasonably happy with the intended process before the late-February ‘pivot’.  In that process it was envisaged that the TSC would, for core functionality only, act as the system integrator and technical design authority. 

On these assumptions the TSC has actively taken on this role since December last year. It negotiated the technical terms for the latest Peras development iteration, was present and actively contributed to the project as it was ongoing and was represented at the final review meeting.  

Up to this point the TSC has not had any particular issues in rapidly reaching a consensus on its actions and, as has been already illustrated, capable of progressing contracts rapidly.  The TSC members are required to act in a personal and professional capacity and take that requirement seriously. Where proposals have been received that seem to be making unreasonable technical assumptions we have sought clarification. That unreasonableness can take several forms: unjustified assumptions about technical limits; too little resources asked for; too much resources asked for etc.

The approach to date, where there is such gaps and given that the overall goals are reasonable has been to help structure the proposed development better (the use of Software Readiness Levels is part of that process) and, where needed, require small scale activities to de-risk the foreseen potential issues to act as progress gates.  Such structuring goes some way to helping contain bloat.

There is a wider issue of general uncertainty in such R&D processes (even where this is small ‘r’ and big ‘D) which is which parties take on latent risks. The TSC would like to investigate appropriate ways of ‘shared risk’ so that a) organisations are not forced to abandon development because unforeseen technical risks arise and b) they don’t make excessive ‘profit’ if the technical issues are much easier than expected. 

The TSC would like to create a collaborative, but not exploitative - on either side, collection of relationships with its supplier pool.

### Can you confirm whether people who have submitted budgets that overlap with the TSC budget are willing to bid?

We have spoken to major suppliers and they have confirmed that they are willing to bid.  They have also revealed their willingness to accept funding from the community by submitting their own bids.  

### TSC member elections are one vote per intersect member, but this poses a somewhat high risk of attack, so will it be possible to switch to DRep voting for TSC elections from the next October election?

This is a good suggestion and one that the TSC would support provided Intersect was willing to engage in this way and that a suitable process could be established (e.g. via GovTools)

### It seems that many of the proposed development items for this budget already are covered in IOG's core development budget proposal. I was under the assumption that IOG and Intersect members have been coordinating rather closely, but if there's this much confusion over who's responsible for core development costs I'm afraid that may not be true. I support Intersect, but until there is more clarity or some kind of reconsiliation in the funding appropriations process I'll favor the IOG proposal over this.

See the [Comparison with IOE Budget Proposal](https://github.com/intersect-tsc/gov.tools.proposal.2025/blob/main/ComparisonwithIOEBudgetProposal.md). 

The TSC proposal puts forward the items that had been presented to it, that align with the core roadmap and that reflect community priorities as understood via the Intersect survey.  As noted, the is open to adding additional work items.  Many of the current work items were proposed by IOE of course, so there is good alignment.  Some IOE-proposed items have not been included, since they were not proposed to the TSC or they are not clearly core infrastructure.  Other items in the TSC budget reflect gaps or omissions. 

The question is not generally one of what work will be done, nor even who will do the work, but about how it’s structured and how multiple work items are integrated. Effectively, the TSC is asking for delegated authority to manage multiple projects potentially across different vendors, in the name of ensuring technical coherence and adherance to community-defined needs and priorities.

### Is it possible to list all budgets (excluding IOG) that have overlapping scopes with the TSC Budget? 

See the comparison (link coming soon). It is possible to absorb these into the TSC budget.

### Where did $299,000 applied-to-every-engineer figure come from exactly?

This is a realistic number for budgeting purposes that has been aligned with prices that have been quoted to us by suppliers, and that has been verified by reference to other major core budget proposals. Unlike many other budget proposals, this does not set a rate that will be paid to the suppliers by the community, but just sets a total budget.  Since these suppliers are likely to form a significant part of the supplier base, this allows us to set a sensible budget.  In assigning contracts, the TSC will negotiate with suppliers to obtain the best value for money for the community, reporting transparently on the actual costs that are paid to suppliers. While actual developer salaries do vary, it is necessary to obtain and pay for high quality developer staff, so costs will be higher than for web development, for example.  Blockchain developers are in high demand, so can command higher than average salaries, and it is necessary to retain staff who have Cardano knowledge and experience.  Full consideration will be given to managing costs sensibly. 

We have discussed the possibility of paying actual costs (“full economic cost”) plus some agreed overhead costs (e.g. 20%) with some potential suppliers.  This is a fair way to ensure value that has been adopted by many public procurement processes that work in a similar way (e.g. the NSF, the European Union). This would create better alignment with actual costs (e.g. developer salaries), with a fair return to suppliers that reduces their risk of engaging with Cardano.  It also allows straightforward auditing by an independent party. If this approach was adopted here, for fairness, the same principle should, of course. be used by all approved budgets.
