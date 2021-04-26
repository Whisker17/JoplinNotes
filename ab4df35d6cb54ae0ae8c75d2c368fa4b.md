# 讨论

- We are preparing a longer response for comparisons of Zeitgeist to other prediction markets. The gist of it is that Zeitgeist builds on the ground that Augur broke in decentralized prediction markets, namely by building out new primitives for prediction markets and ways to trade them. We also are focusing on how prediction markets can be a cornerstone in our on-chain governance mechansim by using Futarchy.
- Zeitgeist is taking a different approach from polkamarkets afaik, we are building an ecosystem and hub for application based on prediction markets. This includes our own application and front-end but also an SDK for others to use zeitgeist as a tech stack.
- Polkamarkets is not building a parachain I thought, but rather a single application being deployed to a parachain. Zeitgeist could potentially support thousands of polkamarket-like applications on its base layer parachain.

- From my perspective, the reason prediction markets haven't picked up huge adoption yet has been both for scalability and usability reasons, as well as not being tapped for their full potential. For example, you can create risk markets in which you hedge yourself against a certain event and I think this application has been underexplored

- It comes down to a liquidity problem, in this case you want to have an efficient way to have liquidity on markets. For markets with low volume what will probably work well is a dynamic fee pricing model where fees are high when liquidity is low, since the LP is taking on risk by being your counter-party.

- The biggest difference between Zeitgeist and Pollkamarkets or Option Room is that Zeitgeist will be deployed as a parachain while the others are smart contract applications. Being a parachain allows Zeitgeist to have robust and adaptable governance and evolvability controlled by the ZTG holders. Another difference would be the type of markets that Zeitgeist supports. While other platforms may only support Binary markets that can trade Yes or No, Zeitgeist will support various other types of markets including combinatorial markets that can be composed out of many potential conditional outcomes. Zeitgeist is also researching and planning to implement a LMSR AMM design, and support this alongside traditional order book trading and Swap-style AMMs.

- Zeitgeist on a protocol level is permissionless for anyone to create markets or trade them.

- One would be a more optimized and streamlined experience. Besides that some of the new features I'm excited about are futarchy, implementation of the LMSR for trading, combinatorial markets in an accessible format, and market curation abilities.

- I'll also add that the cool part about being an evolving protocol is that even when new advancements to prediction market tech is discovered, we will able to add it to Zeitgeist as an upgrade.

- The way that disputes are handled any time a market is resolved is through the Zeitgeist court system. The court is a group of staked ZTG holders that have chosen to participate in the dispute resolution process. They are responsible for deciding the actual outcome of the markets.

- The example that we've been talking about is the one for bug bounty markets. You can imagine that when an upgrade is proposed, a market can be created asking "Will a bug be found one week after the runtime upgrade happens?" And traders can trade what they think is the probability of that. Then on a protocol level we can have a rule that for example if the probability is over 60% in this market, the runtime upgrade is blocked.

id: ab4df35d6cb54ae0ae8c75d2c368fa4b
parent_id: a7447bf6f33b41ddb1e201f14029d0ea
created_time: 2021-04-26T08:32:05.147Z
updated_time: 2021-04-26T08:41:59.687Z
is_conflict: 0
latitude: 0.00000000
longitude: 0.00000000
altitude: 0.0000
author: 
source_url: 
is_todo: 0
todo_due: 0
todo_completed: 0
source: joplin-desktop
source_application: net.cozic.joplin-desktop
application_data: 
order: 0
user_created_time: 2021-04-26T08:32:05.147Z
user_updated_time: 2021-04-26T08:41:59.687Z
encryption_cipher_text: 
encryption_applied: 0
markup_language: 1
is_shared: 0
type_: 1