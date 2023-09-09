---
layout: ../../layouts/PostLayout.astro
title: Digital Governance
date: '2023-06-04'
tags: ['web3','DAOs']
summary: Simple rules, messy outcomes.
images: []
---
Decentralized Autonomous Organizations are often governed by simple rules. A membership is auctioned off each day. Someone pays to become a member. That money flows to a treasury. People send proposals to the DAO on how to use the money and if the members vote in favor, the money is paid out.

Apparently, these simple rules are all it takes to build a large financial machine. Nouns, the biggest of this kind of DAO, currently sells memberships for about 25 ETH each day and governs a treasury of 28,000 ETH (50 million dollars). Recently, they spent 42,000 USD to fund a global pizza party.

They're also all it takes to create hot debate. In the last few days there has been a flood of discussion about what kind of proposals a particular DAO (Purple) should vote on, which resulted in a new DAO forming (Purpler). Purpler, as opposed to Purple, only funds projects retroactively, with the idea that this leads to more efficient use of the treasury's money.

Regardless of your view on DAOs, it's an interesting thought experiment. How do you create a simple set of rules that allows people who don't know or trust each other to collaborate around economic decisions without centralization?

Governance can be improved in three main ways: First, by ensuring that as many members as possible participate directly or indirectly in voting. Second, by ensuring that competitive proposals are presented to the DAO to vote on. Third, by ensuring that when the DAO decides to spend money, that money is used efficiently and in accordance with the proposal.

First and foremost, the number one goal of a DAO should be to increase direct and indirect voter participation. If members don't vote the whole idea fails. When a significant fraction of the members aren't exercising their votes, the decisions made don't necessarily reflect the will of the members. There can be non-protocol initiatives to nudge members toward delegating their votes, but it's more robust to make protocol-level changes to incentivize voting.

To emphasize on a protocol level the importance of voting, members should risk losing their membership if they don't participate. A reasonable mechanism would be that a super-majority, such as two-thirds or 80% can decide to renounce a membership. The downside of this is that by unfairly voting out members, malevolent actors can increase their relative control over the treasury. Such behavior can be prevented by hard-coding compensation for those who are ousted. The value of memberships is known since they are marked to market as new ones are auctioned off. In this way, the DAO can renounce memberships to maintain an active membership base, but they need to pay for it. To further prevent attacks, the rule can state that not only must a vote be taken with a decision to renounce a membership, but a predefined criteria must also be fulfilled. For instance, a member hasn't voted directly or via delegation in, say, 90% or more of the votes during a year.

The goal of these mechanisms is to increase direct voter participation as well as delegation. Delegation is desirable because it increases voter representation while fewer people have to invest their time (and gas) in voting on every proposal. The problem with delegation is that it introduces agency problems. But this issue can be mitigated with digital voting since a member has the choice to change the delegation or vote directly in every vote. You can delegate your vote as a default, but when there's a particularly important vote where you have a strong will you can always choose to vote yourself. It's no less complicated to run a voting process with all of the voters compared to via delegation. Some of the practical barriers in an analog voting procedure are minuscule in the digital world.

The second way to improve governance is to ensure that the DAO has competitive proposals to vote on. A current problem is that most votes are simple yes/no decisions. This type of choice makes it hard for a DAO to make good decisions. For an important spending decision, it's good governance to consider multiple offers. If a certain proposal is to do work for some amount of ETH, there is a good chance that someone else has a similar proposal for a lesser amount of ETH or can do more work for the same amount. Increasing competitiveness means creating better offers for the DAO to decide on. It's also easier for members to make a decision when there are multiple choices rather than just a yes/no decision. Thus, the protocol should allow for more types of votes than just simple yes/no decisions.

The third part is more operational and relates to how the money is utilized after the DAO has decided to spend it. Since there is less trust between actors in a DAO than in traditional business this part of governance is crucial. When the DAO decides to send significant amounts of money to unknown people, it should have safeguards in place to ensure that the money is spent as intended.

One way to do so is by retroactive funding, as suggested by Purpler. This probably works best for small projects where someone is willing to take the financial risk of potentially not getting funded. But it doesn't work for larger projects. That doesn't mean that the DAO should pay out everything upfront. Rather, a small payment upfront combined with installments upon deliveries is a good way to share the risk between the DAO and those working.

There must be trust somewhere in the system because small payment decisions need to be made to do work. It's not practically feasible for the DAO to be involved in every small decision. On a day-to-day basis, there should be a trusted representative from the DAO to OK payments. This representative is responsible for operations and should be compensated for their work. There should be many different representatives from the DAO - they'd work on a project basis. A representative is only necessary in the case where there is no trust between the DAO and the supplier. If the supplier is recurring, trust can be built between the supplier and DAO. In those cases, there wouldn't be a need for a representative.

So there you have it, some simple ideas on how to improve governance. Incentivize members to stay involved, ensure that they get competitive decisions to vote on and that the money is used as intended.
