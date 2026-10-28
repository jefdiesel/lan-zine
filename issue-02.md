---
title: "Local Area Network — Issue 02"
subtitle: "A Self Installation Guide to Reformatting Society"
issue: 2
date: 2026-10
publisher: Logos Collective Association
source: "Local Area Network print zine, issue 02 (A5 booklet, 24 pages)"
contact: pressengine@logos.co
format_note: >
  Transcribed from the print PDF for agent use. Article text is kept close to
  the original; images are described in brackets. Page numbers refer to the
  printed booklet. Facts and claims are the zine's, not independently verified.
---

# Local Area Network (LAN) — Issue 02, October 2026

## How to use this file (for agents)

- **What it is:** LAN is the Logos movement's monthly zine ("the record of the parallel society"). Issue 02 covers Sep 2026 activity from Logos Circles (local chapters), Logos tech releases, and essays.
- **Structure:** six sections — Understanding Whole Systems, Parallel Infrastructure, Parallel Economy, Parallel Action, Parallel Education, Parallel Culture. Each article has a `Source:` line with the original report/author/date.
- **Quick-reference indexes** (tech facts, Circles, links) are at the top; full article text follows.
- **Terminology:** "Circle" = a local Logos chapter, named `Logos Circle / <City>`. "Winnable issue" = a Circle's chosen concrete local problem for the month. "λPrize" = Logos bounty programme.

## Quick reference: Logos tech facts in this issue

| Item | Fact | Date | Page |
|---|---|---|---|
| Logos Basecamp | Runs on Windows (Intel + AMD) from v0.3.0, thanks to dlipicar; Khushboo-dev-cpp's work lets you uninstall apps from inside Basecamp, lets apps pass requests to each other, adds a download progress bar. Installer: file ending `windows-setup.exe` at github.com/logos-co/logos-basecamp/releases | 22 Sep | 7 |
| Testnet v0.3 | Before 30 Sep, testnet tokens needed a faucet + approval. v0.3 introduces **EmPoWering**: mine testnet tokens yourself — "no tokens, no stake, no permission" (Marcin Pawlowski's Proof-of-Work LIP). Set up a node via docs.logos.co/run-a-node, then `logosctl call blockchain_module pow_start_mining` | 30 Sep | 7 |
| Testnet v0.3 → Logos Chat | Multiple devices per account (each revocable), delivery receipts, group names, post-quantum encryption for groups and DMs | — | 9 |
| Logos Messaging de-MLS | Decentralised MLS: no server; a rotating member holds the commit role; anyone proposes add/remove/key-rotation, group votes; updating your own key needs no vote; nothing onchain. Uses Scalable Data Sync (SDS) for ordering | 18 Sep | 9 |
| λPrize winners | Pramadanif (multisig for Logos Execution Zone), Timidian (DistributionX private token distribution), Aegonmyy (AI agent as a Logos module with own wallet) — $1,200 / $600 / $1,200. Open prizes: github.com/logos-co/lambda-prize | 21 Sep | 7 |
| Activist Builder | New role: people who build shared tools for Circles (savings/lending, mutual aid, voting, directories). Apply at logos.co/activist-builder | 30 Sep | 7 |
| Keycard libraries | Mmlado's admin-authority and freeze-authority libraries (λPrize LP-0009/LP-0010, RFP-001/RFP-002); the RFP-008 lending protocol winner depends on the admin library | 29 Sep | 10 |
| PriFi | Logos design philosophy: privacy-preserving financial primitives across the whole transaction supply chain, not just settlement. Article: logos.co/prifi | — | 5 |

## Quick reference: Circle activity

| Circle | Location | Issue / action | Page |
|---|---|---|---|
| Kampala | Uganda | SACCO ledger on Logos Blockchain; builders sessions (60 people at Makerere, 35 at Victoria University) | 8 |
| Awka | Anambra, Nigeria | Training → internship pipeline; 15 trained, 11 placed; 80 accelerator registrations | 11 |
| Accra | Ghana | Scam-awareness / financial-literacy outreach, 20 members, 15 Aug | 11 |
| Kaduna | Nigeria | Medical outreach for widows: hepatitis B/C tests, vaccine, BP, eyes; 100+ attended | 14 |
| Kano | Nigeria | Helped run the Kaduna outreach | 14 |
| Gombe | Nigeria | Free genotype testing (sickle cell), 49 samples, 20 Sep | 14 |
| Wukari | Taraba, Nigeria | Orphanage (23 children): tutor found, raising money for beds; borehole next | 15 |
| Keffi | Nigeria | Ar-Rajah Centre for Widows and Orphans (77 children) — needs list | 15 |
| Port Harcourt | Nigeria | Gracelife Children's Home visit | 15 |
| Benin City | Edo, Nigeria | Paid hospital bills so two discharged patients' families could go home | 16 |
| Ibadan | Oyo, Nigeria | Street clean-up without permission; 250+ waste bags to 150+ households | 17 |
| London | UK | gapmap.uk mapping project (referenced) | 18 |
| Katsina | Nigeria | 3-week maths/English programme, ~60% score gain | 19 |
| Bauchi | Nigeria | Career talk to 100+ students, first-aid box donated | 19 |
| Rajasthan | India | Field Station residency at Dhun, 23–31 Oct | 20 |

## Links

- Contribute: pressengine@logos.co
- logos.co/prifi — "PriFi: Securing the Entire Transaction Supply Chain"
- logos.co/past-present-future — interactive initiative
- github.com/logos-co/logos-basecamp/releases
- docs.logos.co/run-a-node
- github.com/logos-co/lambda-prize
- logos.co/activist-builder
- forum.logos.co — Logos Messaging Deep Dive (18 Sep 2026)
- mmlado.com/blog/keycards-for-a-building-nobody-can-renovate
- grassrootseconomics.org · github.com/grassrootseconomics/sarafu.network
- foodcoop.com
- github.com/FoggedLens/deflock
- tur-tyhyi.github.io/the-shadow-phase
- logos.co/get-started · logos.co/movement · logos.co/node-programme

---

## Editorial (p. 2)

### Purpose
The parallel society already exists. It is a food bank in Ibadan, a node running behind a hotel router in Prague, a permissionless school under a tree in Delhi, activists in Benin City raising money to pay for a member's health treatment, and a developer in Los Angeles compiling a messaging node from source. Local Area Network is the record where these smaller stories are remembered, and the bigger story told. From the many, one.

### Function
LAN is the Logos movement's record of itself: what our activists are building, who they are helping, what they are running, what they are inspired by, and what they are learning on the way. It functions as a mirror: we collect the best of these experiences to create a shared image of ourselves.

A piece is fit for LAN if it:
- Highlights a win, a lesson, or a story from a Logos Circle, its activists or community.
- Showcases an improvement, update or novel use of Logos technology.
- Explains how relevant systems work: both those we are building and those we are exiting.
- Is a relevant development in the categories of parallel infrastructure, economy, education, action, or culture.
- Is on the cultural edge of technology, the internet, politics and philosophy.

### From the editors
This publication takes direct inspiration from the seminal Whole Earth Catalog by Stewart Brand. Published between 1968 and 1972, it was a highly functional access-to-tools guide to empower individual autonomy in the face of big government, big business and other orthodoxies. The WEC brought together co-curated products and ideas by and for a varied mix of innovators and iconoclasts: computer hackers, hippies, alternative designers, architects, builders and environmentalists who shared a countercultural view of learning, building, organising and thinking. This publication shares the same spirit: from a diverse crowd living in different geographies and working in different fields, a common vision emerges.

### LAN guide
Contribution is open through action. Send field reports, technical walkthroughs, essays, data, visuals, lessons learned and working prototypes to **pressengine@logos.co**.

### Print guide
- A5 booklet, with stapled inserts, print double sided.
- Crop marks included, please cut out of the print.
- Regular printing paper in terms of thickness. Use recycled paper where possible to cut costs.
- Printing it yourself: Acrobat Reader > Print > Booklet, Both sides, binding Left.
- 24 pages = 6 sheets of A4, folded and stapled on the fold.
- At a print shop, ask for an A5 saddle-stitched booklet.
- Black and white is fine.

## Index (p. 3)

- **Understanding Whole Systems:** 04 The Patriot Act at 25 · 05 The Case for PriFi · 06 Past. Present. Future.
- **Parallel Infrastructure:** 07 Monthly Highlights · 08 Every Shilling Accounted For · 09 Who Keeps the Member List? · 10 Keycards for a Building Nobody Can Renovate
- **Parallel Economy:** 11 From Training to Internship · 11 How to Spot the Scam · 12 Pooling Commitments · 13 The Shopper-Controlled Shop
- **Parallel Action:** 14 Where the Health System Doesn't Reach · 15 From Meetup to Action · 16 Two Families Went Home · 17 Action, Not Permission · 18 Mapping the Cameras
- **Parallel Education:** 19 Three Weeks, Sixty Percent · 19 More Than Doctors and Lawyers
- **Parallel Culture:** 20 Test It Before You Leave · 21 From Report to Story · 22 The Shadow Phase

---

# Section: Understanding Whole Systems

> A parallel society starts from a clear view of how the existing order works, why it fails most, and how a better one could work. This section carries essays, history, and reading on that order and on how people are choosing to leave it.

## The Patriot Act at 25 (p. 4)

[Photo: President George W. Bush signs the USA PATRIOT Act in the East Room of the White House, 26 October 2001. White House photo by Eric Draper, National Archives. Public domain.]

On 26 October 2001, 45 days after the September 11 attacks, President George W. Bush signed the USA PATRIOT Act into law after it was rushed through Congress. The whole argument behind it rested on a single trade: privacy and freedom given up in exchange for security, a logic that has framed the debate over surveillance ever since.

Predictably, the Patriot Act has been at the root of many of the most serious abuses of government surveillance power. Before it passed, the FBI needed specific and articulable facts giving reason to believe a person was a foreign power or an agent of one before it could demand their phone, internet, or bank records with a national security letter. Afterwards, vague relevance to an investigation, without any actual suspicion of a crime, was enough, and no judge had to be involved. National security letter requests rose from about 8,500 in 2000 to about 56,000 in 2004, routinely sweeping up personal information about people with no connection to terrorism. The letters also came with gag orders that, for years, courts had no real power to review.

Other provisions allowed the government to obtain surveillance orders that identified neither the person nor the facility to be tapped, collect records of people's web activity, conduct secret "sneak and peek" searches of their homes without telling them, label people terrorists for belonging to peaceful dissident groups, seize their property without prior notice or a hearing, and even detain non-US citizens indefinitely on the Attorney General's say-so. Together with the laws that followed, it also laid the groundwork for global surveillance through secret court orders and dragnet collection of emails.

Even more jarring is that, before Edward Snowden's leaks in 2013, the public had no official confirmation of the scale of mass surveillance, and the Director of National Intelligence, James Clapper, denied it under oath.

Perhaps the most insidious part of the whole setup is how the Patriot Act reached beyond America's borders and citizens. It created what the art collective Metahaven called a "supra-jurisdiction": authority over information held by any US-registered company, wherever its servers happen to be. This became part of what the theorist Benjamin Bratton called a "vast software/hardware formation, a proto-megastructure of both bits and atoms, literally circumscribing the planet, which [...] not only perforates and distorts Westphalian models of State territory, it also produces new spaces in its own image: clouds, networks, zones, social graphs, ecologies, megacities, formal and informal violences, weird theologies, each superimposed on the other." Seen in this light, the state is no longer the only aggressor in surveillance. We have all become entangled in multiple overlapping jurisdictions and are, in Metahaven's words, "captives of the cloud".

Even though the internet was transformed, gradually and mostly in secret, into a massive surveillance machine that affected everyone in the world, the security benefits proved hard to find. Reviewing the bulk phone records programme built on the Act's Section 215, the government's own Privacy and Civil Liberties Oversight Board reported in 2014 that it had "not identified a single instance involving a threat to the United States in which the program made a concrete difference in the outcome of a counterterrorism investigation." Section 215 was finally allowed to expire in 2020. In short, we gave up our privacy for a security that, in the case of the Act's flagship programme, never materialised.

## The Case for PriFi (p. 5)

**The transaction supply chain** (diagram; settlement is highlighted as "the only link where value moves"):

1. **Discovery** — Finding a counterparty who has what you want.
2. **Diligence** — Verifying they are who they claim.
3. **Negotiation** — Agreeing on price and terms.
4. **Contracting** — Committing in enforceable form.
5. **Ordering** — Deciding whose transaction goes when.
6. **Settlement** — The only link where value moves.
7. **Enforcement and recourse** — Making the outcome stick, or proving what happened when it does not.

**TLDR:** PriFi, or private finance, is a technical design philosophy espoused by Logos. It involves deploying privacy-preserving financial primitives on peer-to-peer infrastructure and hardware you control. PriFi is not privacy bolted onto existing systems, but rather systems designed from the ground up to allow counterparties to conceal valuable and exploitable information, so they can confidently enter into trades.

Blockchains solved one of the oldest economic problems: how to make a promise hold even when the party making it would prefer otherwise. But transactions do not begin or end at settlement; they comprise steps before and after, including discovering someone to deal with, checking they can uphold their end of the bargain, and so on. If security is concentrated at the moment value moves, while information and discretion remain exposed everywhere around it, the transaction remains vulnerable. PriFi aims to secure the entire transaction supply chain.

For most of crypto's history, we have treated onchain transactions as if they were atomic events. We tend to consider them as self-contained moments: a signed instruction enters the network, executes, and settles. In reality, they comprise a series of links in a wider chain. They include discovery, diligence, negotiation, contracting, ordering, settlement, and enforcement.

Settlement is where blockchains are extraordinary. Bitcoin demonstrated that monetary rules could be enforced without reliance on a central operator who can make exceptions. Ethereum extended the principle to programmable agreements. A valid state transition is accepted; an invalid one is rejected. Counterparties do not need to trust a minister, bank manager, or platform operator to consistently honour rules.

Institutions have always struggled with the problem of credible commitment: How can we trust that a party will act in accordance with agreements made when breaking their word may be in their interest? Blockchains realised historically unprecedented guarantees by removing the discretion to defect and making rules self-enforcing.

Yet the absolute transparency that enables blockchain to structurally constrain defection introduces new attack surfaces by making information about the transaction available to every network observer. These attack surfaces discourage wider participation in onchain finance and define the problem space for those building PriFi infrastructure.

The proposition is not simply that financial transactions should be "more private". It is that the correct unit of analysis is the entire transaction lifecycle, and that strengthening commitments requires heightened privacy and security at each link.

Source: "PriFi: Securing the Entire Transaction Supply Chain", logos.co/prifi.

## Past. Present. Future. (p. 6)

[Photo: three young people, one holding up a phone showing a face-scan screen.]

Mike is eighteen, eager to succeed in the world and make his dad proud. At this point in his life, he must make a choice: be the first in his family to go to university or start work straight away?

If he goes to university, he borrows three years of tuition and living costs before he earns a penny, and the interest starts on day one. Fees are £9,250 a year, up from £3,290 in 2010. If he goes to work, he can legally be paid £10.85 an hour, £2.60 below the real Living Wage.

A steady job, however, only plays into two decades of stagnation, with British wages roughly £15,000 a year lower than if pre-financial crisis growth had continued. A business of his own is no safer, since only 38% of new UK businesses are still trading five years on.

In both cases any cash he might be able to save lost ground when inflation hit 11.1% in October 2022.

What would you do in Michael's shoes? Try it out for yourself with our interactive initiative: Past. Present. Future. is an initiative highlighting why a movement like Logos has never been more important.

In Past, we went to the Museum of Civil Liberties, an Arctic archive of major events that resulted in encroachment of personal freedoms (which is now taking visitor exhibit submissions). In Present, we follow three very different stories: Michael, Amanda, and a still-unrevealed character. As the player takes each character's major decisions, three widespread symptoms of a society in rapid decline emerge.

Michael's story is about debt and how it restricts our choices. We join as he considers whether to borrow money to go to university or go straight into employment. Amanda's story revolves around social media harms and how her health declines as her data is used against her.

[QR code.] Source: logos.co/past-present-future, read 9 October 2026.

---

# Section: Parallel Infrastructure

> Every parallel institution must run on sovereign infrastructure, which nobody can corrupt, switch off, or seize. This section covers the networks, software, and hardware a parallel society runs on, and how they work and how to build them.

## Monthly Highlights (p. 7)

### 21 Sep — λPrize winners
Congratulations to Pramadanif, Timidian, and Aegonmyy, who each won a λPrize. Logos sets most of these prizes where it finds a gap in its stack. Any individual or team can enter. Entries are judged against each prize's criteria and must be open source.

Pramadanif built a multisig for the Logos Execution Zone, a shared account that pays out only after enough of its members sign off. They approve from private accounts, and the chain counts the approvals without recording who they're from.

Timidian's DistributionX hands out tokens to a list of people. Only a hash of the list and the payout amounts go on the chain. Everyone gets their own entry encrypted and claims it with a proof that leaves their address out.

Aegonmyy built an AI agent that runs as a Logos module and has its own wallet. It spends up to a limit you set, and asks you over an encrypted channel before it goes over it.

The three prizes were worth $1,200, $600, and $1,200. The ones open now also ask for evidence that what you build is being used. They're listed at github.com/logos-co/lambda-prize.

### 22 Sep — Basecamp on Windows
Logos Basecamp runs on Windows from version 0.3.0, on Intel and AMD machines, thanks to dlipicar. Khushboo-dev-cpp's work in the same release lets you uninstall apps from inside Basecamp, lets apps pass requests to each other and adds a progress bar to downloads. The installer is the file ending in `windows-setup.exe` at github.com/logos-co/logos-basecamp/releases.

### 30 Sep — Testnet v0.3
Until 30 September, getting testnet tokens meant asking a faucet and waiting for approval. Testnet v0.3 introduces EmPoWering, so you can mine them yourself: "no tokens, no stake, no permission", in the words of Marcin Pawlowski's Proof-of-Work LIP. Set up a node with the guide at docs.logos.co/run-a-node, then run:

```sh
logosctl call blockchain_module pow_start_mining
```

### 30 Sep — Introducing the Activist Builder
Circles across the network keep hitting the same problems. They need ways to save and lend money as a group, organise mutual aid, vote on proposals, or keep a directory of who does what in town, among other things. One tool that works for all of them makes more sense than every Circle solving its own, and building that tool is the job of an Activist Builder.

Logos is looking for people who start from a real problem and work towards building the tool. You talk to the people who have the problem, test the idea with them before writing code, and build in the open so others can pick it up. Developers are welcome, and so are researchers, product designers, educators, and translators, because the work covers research and media too. Interested? Apply at logos.co/activist-builder.

[Photos: a rugged laptop case running in the field on rocky ground; a person installing a weather/antenna mast on a mountain.]

## Every Shilling Accounted For — Kampala, Uganda (p. 8)

[Photo: builders session in a conference room, faces blurred.]

Across Uganda, savings and credit cooperatives, known as SACCOs, hold the money of ordinary members, and in the words of Logos Circle / Kampala, "serve as the financial backbone for millions of citizens". What members often can't see transparently is where that money goes inside the system. This is mostly because records are kept on paper by hand, making loan approvals and spending hard to trace. The Circle's field research in July found that this gap was costing trust between SACCO members and the people who run them.

The Circle's answer is to build the record on the Logos Blockchain as a ledger in which every deposit, loan, repayment, and expense is recorded as it occurs. This means any member can check it, without changing how the SACCO itself is run.

To work on some fixes, in late August, 60 people came to a conference room at Makerere University for a builders session, among them were students, developers, SACCO stakeholders, and researchers. They split into workstreams covering design, frontend, backend, and blockchain integration, and set up their development environments on the spot. A month later, in September, the Circle took the project to Victoria University, where many of the 35 who came had never used a blockchain before. The session showed them how they could help anyway, through design, research, testing, or documentation, and several said they wanted to.

As of today, the next steps are the first GitHub issues for each workstream, tests for deposits, loan approvals, and repayments, and a prototype that members can try out.

Source: Logos Circle / Kampala, reports by Makmot256, 9 and 28 September 2026.

## Who Keeps the Member List? (p. 9)

[Image: handwritten historical membership ledger, "Members in 1795 / 1796 / 1805 / 1806".]

Every encrypted group chat still needs a mechanism to distribute keys and track who is in the group. MLS, the standard for this, assumes a server that is always online will do the job, which means whoever runs the server holds the member list. This is an obvious point of centralisation that can lead to abuse and fragility in the system.

Logos Messaging's version, de-MLS, removes that server and assigns the job to one member at a time, with the role rotating. Anyone in the group can propose adding or removing someone, or rotating the keys. The group then votes over the network, and if the vote passes, the proposal becomes a normal MLS update. If the member holding the role sits on a proposal, the role moves on. Updating your own key doesn't require a vote. And none of it requires anything onchain.

The difficult part is keeping everyone in step. The keys remain secure only if every member applies the same changes in the same order, so a single disagreement splits the group. Changes to the group, therefore, have to arrive almost without fail, while ordinary messages can be looser. Logos Messaging handles this with Scalable Data Sync, where every message points back to the messages that led to it. Each member can then tell which messages they're missing and ask for them to be sent again, without the network being flooded with receipts.

Losing a phone works similarly. Each app and device gets its own key tied to your account, so a lost phone means revoking that one installation rather than your whole identity.

Testnet v0.3 brings this to Logos Chat, with several devices per account that can each be revoked, delivery receipts, group names, and post-quantum encryption for groups and direct messages.

Source: Logos Messaging Deep Dive, forum.logos.co, 18 September 2026.

## Keycards for a Building Nobody Can Renovate (p. 10)

[Diagram: "The mall, as a floor plan" — rooms `open` (#[require_admin], #[freeze_exempt]; owner only, stays open in a lockdown), `set_rent` (#[require_admin]; owner only, locks down with the rest), `shop` (no lock; anyone's card opens it, locks down with the rest, a banned visitor is turned away), `leave` (#[freeze_exempt]; anyone's card, any time, even in a lockdown). Door legend: keycard reader = owner only (#[require_admin]); lockdown wiring = shut by one switch with the rest, or exempt (#[freeze_exempt]); nothing on the door = anyone. "Doors the libraries bring: hand over the keycard or destroy it, lock the mall and reopen it, ban a visitor and let one back, name a new chief or let the chief leave."]

During a crypto event, I got a Logos fanzine from someone I can now call a friend. I dropped it into a bag and didn't pay much attention to it. Some time passed, and we met again and talked properly this time. He told me to read the fanzine he gave me. I did, and it hooked me, though I didn't act on it. I had a steady job. Why rock the boat?

Then, my mom died, and I was looking at my own clock and the choices I'd made. Less than two months later, I was on the EthBelgrade stage telling my story, telling the audience they don't need to ask for permission. The target audience was me, all along. The ideas from that fanzine had been sitting in the back of my mind for years, and they all came out at once. Steady wasn't enough anymore. I joined the cypherpunk movement, and I didn't ask for permission.

I was looking for proof that my new freelancer life could work, by earning just a cent from something. Logos' λPrize opened with two Keycard-related entries, LP-0009 and LP-0010, which were right up my alley… and I snatched them! I tried to compete for other prizes, too, and the tech drew me in. I sent in proposals for two of Logos' Requests for Proposals, RFP-001 and RFP-002, the admin and freeze authority. I knew these set a base that many programs on the Logos Blockchain would build on.

Modern malls have card readers on their doors. Some doors open only for the owner's keycard, and the owner is whoever swiped first on opening day. There are doors of a store, for example, that anyone's card opens, including the owner's. The owner can give their keycard to someone else, and they become the new owner of the building. The keycard can also be destroyed. Then those doors never open again, and the mall is a public space without an owner. This is the first library: admin authority.

The builder can also install a lockdown system. Every door gets a lock by default, and the builder picks the ones that do not. The owner can hire a security chief. The moment a visitor looks suspicious, the chief can lock down every door with the locking mechanism. Nobody gets in, not even the owner. This is the second library: freeze authority.

Immutable cuts both ways, and on the Logos Blockchain, it cuts harder. There's no renovation. Not by the owner, not by anyone.

The admin library is barely out of development, and the lending protocol that won RFP-008 already lists it as a dependency. That made me grin. It was the whole point. I built the libraries so nobody else would have to.

There is also the λPrize list, where prizes come in sizes, and the small ones are a way into the ecosystem. That is the door I came through.

Source: Mmlado, "Keycards for a building nobody can renovate", 29 September 2026. Full post: mmlado.com/blog/keycards-for-a-building-nobody-can-renovate.

---

# Section: Parallel Economy

> People cannot exit an unfair system they still depend on to earn, save, and live. This section covers money, payments, savings, work, and trade that run independently of the institutions that monopolise them.

## From Training to Internship — Awka, Anambra State, Nigeria (p. 11)

When LAN Issue 01 went to print, Logos Circle / Awka had just set a target for itself: to get at least 20 people in Anambra State into work. Its first real step towards that was an accelerator.

Together with LaunchPad Community, the Circle ran a content creation and social media management programme, including practical training in storytelling, account management, workplace readiness, and portfolio building. Activists Emma, Lucy, and Oma mentored the 15 attendees through the training, 11 of whom were placed in internships.

When 17 Circle members met later, on 5 September, to review it, they agreed that the hands-on training had worked better than theory would have, and that the 80 registrations for the accelerator showed the demand was real. What they couldn't yet do was measure their progress towards their winnable issue, as they had no way to track those who had completed the training. The list of needs for that pipeline is specific, with role descriptions, supervisors, regular check-ins, feedback from the companies hosting interns, and a record of who turns an internship into a job.

Keeping that record is what the Circle is working on now. It is following up with all 11 interns and their host companies, looking for more employers, and planning its next courses around what local employers are asking for, from sales and content marketing to customer support. In the Circle's own words, the path runs "Training → Internship → Experience → Employment".

Source: Logos Circle / Awka, report by Icodejsx, 8 September 2026.

## How to Spot the Scam — Accra, Ghana (p. 11)

[Photo: rugged feature phone showing a mobile-money menu.]

In July, Logos Circle / Accra spent its meetup talking about financial literacy. In August, the Circle took that conversation out into the wider community.

On 15 August, 20 returning members ran an outreach on budgeting, saving, and making responsible decisions with money, and on how to spot a scam, from the warning signs of a fake investment, a fake job, an online offer, or a phishing message, to how to check an opportunity before handing over money or personal details.

According to the report, practical examples made the difference, and the main lesson of the day was that some fraudulent offers look legitimate, which makes checking the most useful habit to teach. As more of people's money moves online, the Circle points out, financial literacy and digital safety have become closely connected.

Next up, the Circle is putting together a short scam-awareness guide that people can pass on, choosing a specific group to reach next, with students and young adults among the ideas, and setting itself a goal it can measure.

Source: Logos Circle / Accra, report by EOvie, 4 September 2026.

## Pooling Commitments — Kenya (p. 12)

[Photo: shoe artisan in front of a "Sarafu-Credit — inatumika hapa" sign and a "Budget Shoes Artisans" board.]

Crypto built rails for a parallel economy and then used them mostly for financial products. However, there are still examples of what a real onchain economy looks like. One such example is the Sarafu Network, a platform for community economies where people actually transact in their own parallel money, backed by goods and services their neighbours need. Grassroots Economics, a non-profit foundation in Kilifi, has run these community projects since 2010. It is designed to be accessed through simple phones and currently settles on the Celo blockchain.

The Sarafu currency used by these economies is issued by a mechanism called commitment pooling. It works like this: a savings group writes down what its members can supply, for example, seeds, water, cooking, or a day's labour. The group issues vouchers backed by those commitments so that anyone holding a voucher can redeem it for the goods and services behind it. Neighbouring groups can then agree to accept each other's vouchers, creating direct swaps of value that do not rely on scarce national currencies. In the example Grassroots Economics uses to teach it, one group's vouchers are backed by seeds and labour, the next group's by erosion control and water management. If it is mutually beneficial for these groups, they simply exchange their services through the vouchers.

Until now, the state monopoly on money has already tested their setup once. In May 2013, the founder, Will Ruddick, and five others were charged with forgery for launching Bangla-Pesa, a community currency in the informal settlement, or slum, known as Bangladesh in the town of Mombasa on the Kenyan coast. In August of that same year, the Director of Public Prosecutions cleared all six, finding that no law had been broken. The currencies kept running, a testament to the effectiveness of parallel organising.

Today, the Sarafu network runs at scale. A peer-reviewed dataset published in Scientific Data covers around 55,000 Sarafu accounts and every transaction on the network between January 2020 and June 2021. In a 2025 phone survey of 855 active users, 71% were women. Five new neighbourhood pools opened in January 2026, and the code behind the app is open on GitHub, which means a Logos Circle anywhere can fork the commitment pooling protocol and run its own version. As of October 2026, the network is moving to a successor platform, Cosmo-Local Credit.

Source: grassrootseconomics.org · github.com/grassrootseconomics/sarafu.network

## The Shopper-Controlled Shop — Brooklyn, New York (p. 13)

[Photo: The Rochdale Pioneers. The Co-op Group, Wikimedia Commons, CC BY 2.0.]

A parallel economy allows people to provide for each other's needs autonomously. Brooklyn has had a local version of one for 53 years in the form of a grocery store. The Park Slope Food Coop is a member-owned and operated food store where members contribute labour in exchange for being able to shop. As a cooperative, it is an autonomous association of people joined voluntarily to meet their common social, cultural, and economic needs. In this way, they build trust through cooperation, allowing them to keep prices as low as possible while having access to healthy, nutritious food. In 2024, Joe Holtz, one of the founders, gave the reason it started: "We wanted to be able to afford to eat better food." He adds that in a country "very much focused on individual success", they believed it mattered to have some community successes.

The Park Slope Coop runs on principles common to most cooperatives, which trace back to 1844, when weavers in Rochdale, England, tired of being sold flour cut with chalk, pooled a pound each and opened a shop of their own. In Park Slope the same principles run a store of 16,000 to 17,000 members.

The rule is that only members may shop there and all of them must contribute their time to keep it operational. Members do about 75% of the work, and the coop's own survey puts what that saves them at 20 to 40% of a weekly grocery bill. In the year to 1 February 2026, the store had about $63 million in sales and a net income of about $47,000. The coop describes itself as "a buying agent for our members and not a selling agent for any industry". Decisions are debated and taken at a monthly meeting any member can attend, with one vote each.

A Circle's version could start the way this one did, with the added perk of running on onchain rails that could expand the model beyond the hyperlocal.

Source: foodcoop.com

---

# Section: Parallel Action

> As official institutions weaken, a parallel society depends on communities that can solve their own problems without waiting on them. This section reports the problems they take on without permission, from health checks to clean ups.

## Where the Health System Doesn't Reach — Kaduna and Gombe, Nigeria (p. 14)

[Photo: blood sample being drawn; Logos Gombe Circle λ logo.]

In August, Logos Circle / Kaduna set out to help 50 widows in their community with a medical outreach action day. The event was a success, with more than 100 people attending, widows and elderly members of the community among them.

The outreach was set up as a series of stations. It began with a talk on hepatitis B and C and how they spread, followed by blood pressure and blood sugar checks and hepatitis tests. Anyone who tested non-reactive for hepatitis B was offered a first dose of the vaccine. Doctors then went through each person's results and prescribed treatment, a pharmacy handed out the medication, and optometrists from Eagle Eye Clinic Kaduna examined their eyes. DJFL Foundation, House of Abundance RCCG, and members of Logos Circle / Kano helped run the day. For several of those who came, according to the report, it was "the first time a medical outreach of this nature had been organised within their community."

The Circle ran it with very little outside funding. The second vaccine dose is still to come, and the next phase moves on to the widows' livelihoods, with small business grants, support for businesses they already run, and financial literacy.

Logos Circle / Gombe took on another health gap: helping people who don't know their genotype, and so can't know whether their children could be born with sickle cell disease. On 20 September, the Circle ran free genotype testing at ECWA Urshalima Bagadaza. Four medical laboratory scientists collected 49 samples, seven local volunteers helped bring people in, and everyone who took part was told what their result means for starting a family. It was the first stop in a series the Circle plans to take to other communities across Gombe State, so stay tuned.

Source: Logos Circle / Kaduna, report by Evelyn, 2 September 2026. Logos Circle / Gombe, report by SALSSIFY, 21 September 2026.

## From Meetup to Action — Wukari, Port Harcourt and Keffi, Nigeria (p. 15)

[Photo: group of children and Circle members at an orphanage, faces blurred, with donated supplies.]

At Success Orphanage Home in Pwadzu, Wukari, around 23 children sleep in two bedrooms without mattresses. Some of them have come from neighbouring Adamawa and Benue States, and in the hot season, the crowding spreads skin disease. The borehole has been broken for months, so water is carried in from outside, and the teenagers need a tutor for maths and English.

Logos Circle / Wukari found this out in August, when it stopped meeting indoors. After the sessions in June and July, members had decided to "take our meetup to the community", and when they arrived at the home, they started by asking the matron what it was short of. She named three things: a working borehole, a tutor, and beds.

The Circle then found two corps members to teach the teenagers maths and English once school resumes, and is now raising money for bunk beds and mattresses, while looking at either repairing the borehole or running a tap line from a neighbouring source.

In a similar dynamic, two more Circles had taken their meetups to homes for children. In Keffi, 13 members went to the Ar-Rajah Centre for Widows and Orphans, where the matron told them she had cared for some of the children since they were babies. Around 77 children have been in the centre's care, and about 10 have no relatives at all. The secretary gave the Circle a list of what the centre needs, from chairs for its school and around ₦500,000 in registration fees to learning boards, food, clothing, and money to help widows start small businesses. The next steps are to find out what each item costs, pick one or two to take on, and go back.

Logos Circle / Port Harcourt sent five members to Gracelife Children's Home, where they spent time with the children and staff to find out what the home needs.

Between them, the three Circles brought rice, pasta, soap, clothes, toiletries, and treated mosquito nets. They also left with a list of needs written by the people who know them best, and in Wukari and Keffi, that list is now the Circles' next piece of work.

Source: Logos Circle / Wukari, report by Juliussalman, 30 August 2026. Logos Circle / Port Harcourt, report by Viopol, 15 September 2026. Logos Circle / Keffi, report by Paulp5000, 28 September 2026.

## Two Families Went Home — Benin City, Edo State, Nigeria (p. 16)

[Photo: hospital finance receipt dated Aug 31, 2026, item "Feeding", subtotal 120,719.00; patient details blurred.]

"The walls of a hospital are filled with different stories," begins the August report from Logos Circle / Benin City. Some of the people behind those walls have already been treated and are well enough to go home, but they can't leave until the bill is paid.

The Circle made helping those patients its winnable issue for the month. Six members went to the University of Benin Teaching Hospital on a Sunday afternoon, where the matron confirmed there were discharged patients unable to settle their bills. Nobody who could take a payment was in that day, so the Circle came back the next day and met the hospital's PR, who welcomed the visit.

The first case was a six-year-old who had been ill, been treated, and was ready to be discharged, but whose parents couldn't pay. The Circle contributed towards the bill, and the child's mother agreed to be interviewed. The second was a baby with a heart condition, also treated and ready to leave, whose mother had been left to care for her alone after her husband abandoned them. The Circle supported her as well. Afterwards, the members went through the wards handing out detergent and soap and spent time with the patients, which in their words "mattered more than we expected".

The report puts the outcome plainly: "Two families went home this month who would otherwise still be waiting." This proves that small, targeted action can be incredibly impactful for people in the community.

Next, the Circle wants to build a relationship with the hospital, so that future visits can be arranged in advance and a bill paid in one trip, as well as to find ways of raising money to support even more cases.

Source: Logos Circle / Benin City, report by paschal533, 7 September 2026.

## Action, Not Permission — Ibadan, Oyo State, Nigeria (p. 17)

[Photo: circle of gloved hands around a rubbish bag.]

When Logos Circle / Ibadan asked residents what was wrong in their area, poor waste disposal and dirty streets came up. Following their own playbook, the Circle made it its first winnable issue.

The original plan was a clean up in a park inside a higher institution, leaving waste baskets behind and handing out bags in the streets around it. The institution asked for a formal letter first, but although the Circle sent one on time, permission was refused.

Rather than let that hold them up, the 12 members took the work to the streets on 29 August. In Agbowo and Bodija, they handed out more than 250 waste-disposal bags to over 150 households, shops, and traders, talking to each of them about how they get rid of their rubbish. Then they put on gloves and masks and cleaned a street in Bodija.

Afterwards, the group sat down to talk about what comes next, whether monthly clean-ups on new streets or on the same one until it stays clean, a back-to-school project for younger pupils, or mapping the skills inside the Circle itself. The decision is for the next meeting. The report signs off with two lines: 'Tools, not permission. Action, not permission.'

Source: Logos Circle / Ibadan, report by Uchenna, 5 September 2026.

## Mapping the Cameras — United States (p. 18)

[Image: DeFlock nationwide map of ALPR cameras across the US. © William Freeman, MIT licence. Map data © OpenStreetMap contributors.]

Last issue, we called mapping issues one of the most impactful things a Circle can do in reference to Logos Circle / London's gapmap.uk project. To illustrate this point, here is what one map did to a surveillance company.

Flock Safety notoriously sells police departments cameras that read the number plates of passing cars. This has been criticised heavily by watchdogs and concerned citizens as another instance of mass surveillance, warrantless tracking, and a lack of data privacy safeguards. In response Will Freeman, a resident of Huntsville, Alabama, launched DeFlock, an open map built on OpenStreetMap where anyone can log a plate camera they have spotted. The code is open source, and 52 people sponsoring Freeman on GitHub cover the running costs. When Flock sent him a cease-and-desist over the name, the Electronic Frontier Foundation answered on his behalf.

Once the cameras were on a map, this gave people a clear data point to push back on, which led to them turning up at council meetings with the count for their own town.

On 10 September, the council of Kosciusko County, Indiana, voted 5 to 0 to stop county money going to plate cameras. The council had no power to cancel the contract, so on 22 September the county commissioners did it themselves, 3 to 0, after the county attorney concluded that "no valid contract was ever formed." The county took down 31 cameras and dropped $141,000 in payments due in 2027 and 2028. In Lynchburg, Virginia, the city ended its contract for 15 plate cameras and 55 gunshot detectors on 3 September.

The map now also tracks the towns that have dropped Flock: 153 by early September, up from 95 in July, proving that information is power.

Source: github.com/FoggedLens/deflock

---

# Section: Parallel Education

> A parallel society has to teach its own people where official education is out of reach, corrupt, or built to serve the status quo. This section covers the classes, training, and mentoring Circles run beside schools and universities.

## Three Weeks, Sixty Percent — Katsina, Nigeria (p. 19)

Maths and English are the subjects students in Katsina struggle with most, particularly in their secondary school exams. Over the summer, Logos Circle / Katsina hired four experienced teachers, two for each subject, for a three-week programme. The students sat a test before it began and another at the end, and on average their scores improved by around 60%.

Three weeks of teaching only helps the children who are in school. When the Circle met on 29 August to review the programme, the doctors, nurses, teachers, and youth advocates in the room kept coming back to the children who are out of school or close to dropping out because their families cannot pay.

For September, the Circle set itself a target it can check: a full year's tuition for at least five of those children, and a conversation with their parents about keeping girls and boys in school. Members have already put in their own money and are looking to raise more!

Source: Logos Circle / Katsina, report by Dr_jabani, 7 September 2026.

## More Than Doctors and Lawyers — Bauchi, Nigeria (p. 19)

Asked what they wanted to be, the students at Government Day Secondary School in Sabon Kaura gave the answers you might expect: doctors, lawyers, teachers, footballers, and soldiers. On 22 September, 12 members of Logos Circle / Bauchi went to the school, and seven of them, who work in healthcare, law, technology, academia, and social work, spoke to more than 100 students.

They started from the students' answers and built outwards. Those who had only mentioned doctors and nurses began asking about pharmacy, physiotherapy, and radiography. The speakers explained which subjects and class combinations lead to which university courses, and one session encouraged the students to learn a practical skill alongside their schooling.

Around six students stayed behind afterwards to ask how they could keep in touch, and were given the Circle steward's number. The deputy principal told the Circle that many of the students are capable and ambitious but lack proper guidance, and some of the teachers admitted they know little about newer careers themselves. Members also chipped in for a fully stocked first-aid box, which the school had known it needed but kept putting off.

Next time, the Circle wants more time and smaller groups organised by career interest, either at the same school or at a new one.

Source: Logos Circle / Bauchi, report by Galadima, 25 September 2026.

---

# Section: Parallel Culture

> Every parallel society has begun with a culture of its own, where people stop living by the official story and find each other through what they make. This section covers the films, photography, music, writing, and events the movement makes for itself.

## Test It Before You Leave — Rajasthan, India (p. 20)

[Photo: Dhun, near Jaipur, before and after regeneration. The green on the right is the site of the residency.]

From 23 to 31 October, Logos and Zu-Grama are bringing around 30 people to Dhun, a 500-acre regenerative living project near Jaipur, for Field Station / Rajasthan, an eight-night residency for builders and activists.

It is designed as the opposite of a weekend hackathon, where a team forms, builds quickly, presents, and goes home. At Field Station, residents live together, share meals made from local crops, and keep their evenings phone-free, while still getting more than four hours of uninterrupted build time a day. Builders are asked to bring something concrete, whether a project, a prototype, or a clearly scoped problem, and to shape it around a real issue in the communities near the site.

The challenges to build around are based on everyday problems. One asks for a better way of reporting local problems like water, waste, access, and maintenance, so they can be seen moving from reported to in progress to resolved. Another is about privacy-preserving mutual aid, helping residents and site staff coordinate transport, supply runs, and practical help.

The residency has four main tracks: a Civic Prize track working on problems identified by Logos Circles, a sovereignty and privacy track for people already building such tools, a d/acc track led by Zu-Grama, and a track for non-builders. As the joint organisers put it, "not everyone at Field Station writes code." Activists, organisers, artists, and writers will use the tools, test them, challenge them, and help judge the projects.

The week ends with a summit and demo day, where residents show what they built and what happened when people used it. The strongest projects from the Logos tracks can go on to milestone-based grant funding.

Source: Logos blog, "Field Station / Rajasthan: A Coliving Residency to Build the Parallel", 14 September 2026.

## From Report to Story (p. 21)

[Photo: Václav Havel, 1965. Jaroslav Krejčí, Wikimedia Commons, CC BY-SA 4.0.]

Stories are how humans have always passed on what they know. For most of human history, nothing was written down, and what a community knew survived only if it could be memorised and retold. Collective memory still works that way: a fact is hard to memorise, while a story can easily be rehashed in your own words.

In the simplest possible structure, a story has four parts: a character, a challenge, a choice, and an outcome. A story with at least those four parts works because each part pulls you into the next. Once you empathise with the character you want to know the challenge, then the choice, then the outcome. By the end you have felt what happened with them, which is why you can tell it again in your own words without having memorised anything. Václav Havel made the point with one greengrocer in Czechoslovakia who stopped putting the regime's sign in his window. Nobody remembers the statistics on dissent under communism, but everybody who has heard it remembers the greengrocer's window.

Stories also bring together the people who share them. A person in Lagos and a person in Berlin may never meet, but if each can tell the same stories they are on the same side. Academic research has shown that the anti-globalisation activists of the 2000s never agreed on a programme, yet they came to tell one story about their own struggle, which is what made them the same movement.

What this means for a Circle is that fixing the problem is only part of winning an issue. The road gets repaired or the bill gets paid and the people are better off, but the movement only grows from it when there is a story that others can see themselves in and pass on. What we are seeing from Circles today is mostly reports. Consider such a report, which simply declares what was done and presents the facts: the Circle met on Saturday, forty people came, the food drive collected two hundred packs. None of it is wrong, but nobody in it wants or decides anything, so there is nobody to follow and no emotional arc to involve people in.

When structured using a storyline, the same report could have run as follows. Mrs A has fed six people on one income since the factory closed in March. In July, she went door to door on her street with the Circle and found 39 households in the same position. She was the one who said a petition would take months, so the Circle chose a food drive. Two hundred packs went out on Saturday.

This has the same Saturday, the same Circle, and the same 200 food packs as the report. What changes is that you now follow one person through it. You know what Mrs A is up against, and you watch her and the Circle choose the drive over the petition.

All our Circles will likely never be in one room at the same time, and most of their members will never meet IRL. What they hold in common is the stories they can tell each other. A win that is only reported stays in the town where it happened. Told as a story, it travels, and the next Circle that hears it can identify with it, building Logos as a movement.

**Agent note — story template for Circle reports:** character → challenge → choice → outcome. Name one person, state what they're up against, show the decision (and the alternative rejected), then the result with numbers.

## The Shadow Phase (p. 22)

[Image: botanical plate "Graine . Germination" — a bean seed sprouting in stages.]

Civilisation is a system capable of reproducing its own ontology, on its own, from one generation to the next.

The greatest error of the old civilisation is to imagine birth as an event.

It thinks of history in dates. Manifestos, revolutions, founded states, signed declarations, opened institutions – its memory is made of moments that can be placed on a calendar. That is why it almost never notices what made those moments possible. For it, the beginning is whatever first became visible.

The history of humankind testifies otherwise. No civilisation began on the day now considered its birthday. Before the first state, there was already culture. Before the first law, there was already trust. Before the first temple, there was already a shared picture of the world. The great form first lives, for a long time, as a way of life – and only later becomes a historical fact.

In this book, civilisation is not a state, not an economy, and not a collection of institutions. The definition is simple: it is a system capable of reproducing its own ontology, on its own, between generations. Law, politics, education, economy, architecture – these are merely different mechanisms of this reproduction.

This is why history is almost always wrong about its own beginning. It records the moment when the new form became too large to keep ignoring. But visibility is not the beginning. It is, rather, the moment when one stage of maturation ends. A seed does not begin to live when the first shoot breaks the soil. Before that, a root has already formed, nutrients have already accumulated, processes have already taken place, hidden from any observer. The visible part of life is always later than its true beginning.

This pattern repeats too consistently to be a coincidence. Almost every civilisation passes through a phase that historians barely describe, because it leaves neither monuments, nor institutions, nor its own statehood yet. The new world, at this stage, already exists – but does not yet have a form the old civilisation is able to recognise. It lives not in architecture, but in how people treat one another. Not in symbols – in habits. Not in laws – in a new way of coordinating one's own life.

[QR code.] Source: Tur Tyhyi, *The Shadow Phase*, §0, English translation from Ukrainian, tur-tyhyi.github.io/the-shadow-phase. Licensed CC BY-NC-ND 4.0.

---

## Back matter (pp. 23–24)

[p. 23: photo of a road sign on a beach: "IF THERE IS NO WAY, CREATE ONE".]

**Crew Wanted**
For a hazardous journey. Bitter cold, long hours of complete darkness. Safe return doubtful. Honour and recognition in case of success.

Build the parallel.

- Start Building: https://logos.co/get-started
- Join the Movement: https://logos.co/movement
- Run a node: https://logos.co/node-programme

Logos.co – All Rights Reversed. Published by Logos Collective Association.
