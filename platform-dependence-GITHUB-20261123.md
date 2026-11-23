# When the Platform Becomes the Competitor: Building on Ground You Don't Own

Author: Ben Lee
Verdict: BLANK
Status: Published November 23, 2026 — GitHub (BLKnight12356 / Secutiry-Papers)
Threat level: Medium-High

Plain-language disclaimer: as-is, no warranty, verify-before-trust. This draft is built from filed news reports I have read in full. Not every claim has a full primary report behind it yet. A claim stands only at the weight its evidence bears. Where I am leaning and not certain, I say so.

## In my own words

I do not build on ground I do not own. That is not a slogan. It is the rule my house runs on: nothing I depend on answers to someone else's meter. Hosting is not owning. If the machine your work lives on belongs to someone else, and the door your customers walk through belongs to someone else, then your work answers to them, whether they ever say so or not.

This paper is about the shape that rule is built against. The platform that hosts you watches what works. It sees which tools your customers reach for, which features get used, which integrations get popular. And one day it ships your product itself. Not by stealing your code. By watching what works and building it in-house, on ground it already owns.

That happened to a real company, and it is in this paper. It happened before that, to sellers on Amazon. It is happening in a third shape, with a database company being bought by the cloud it runs on. And it is happening in a fourth shape, with books you buy but never own, because the seller keeps the off switch. Seven cases, one shape. I grade the shape Medium-High, and I say why plainly below.

## The check

My rule is simple. I hold it for everything I build or use.

Build the difference, own your ground. Use what others give, but make it better, and make it yours. Nothing I depend on answers to someone else's meter. Wardix runs offline. The shelf lives in files. The local-model road ends at a machine of my own iron. The model proposes, Hērth disposes — the model's words go through the law gate and the identity guard before they become an action. Laws in every AI agent from day one.

That is the house rule. This paper is the case for it. The rule has two halves, and both matter. Owning your ground is the bound. The work lives where you can see it and stop it. Building the difference is the reason to own it. If what you build is the same as what the platform already sells, the platform will sell it. If what you build is different — the hardening, the check, the law baked in — the platform cannot copy that by watching your usage numbers. Difference is the moat. Ownership is the wall.

## Where this paper started

This paper started with an article, not a theory. "Anthropic wants you to build on Claude. There's a catch." The New Stack, by Amanda Caswell, November 14, 2026. I had it read in full, and filed it as library entry 222, approved as filed. The catch is the shape of this paper: Anthropic is expanding from supplying Claude models into enterprise software itself, while urging developers to build businesses on Claude. The developers worry their model provider could become their biggest competitor. Anthropic controls the Claude interface and customer access, and can see which third-party integrations are used most.

That is a news article, not a primary source. I grade it as one. But it is where the paper started, and it is honest to say so. The other two cases below are the pattern behind it.

## The cases, in hand

These are not all proven to the same weight. I list them as they stand, with their limits. A claim stands only at the weight its evidence bears. Unproven is not false. It is not proven either.

### 1. Anthropic and Spellbook — the lead case, The New Stack, November 14, 2026

November 10, 2026, Anthropic expanded Claude's enterprise lineup: Claude Sheets, Claude Whiteboards and Claude Data, previewed Claude Meetings, and expanded interactive connectors letting partners embed applications directly inside Claude, including software from Adobe and Atlassian.

Scott Stevenson is the CEO of Spellbook, a legal AI startup. Spellbook uses Claude for reviewing contracts, suggesting revisions and automating legal workflows. In a November 2 interview with Forbes, Stevenson said Anthropic employees had assured him Anthropic had no plans to compete directly in legal software. Then Anthropic launched Claude for Legal, with contract-review capabilities overlapping Spellbook's business. Stevenson said Anthropic had been a great partner but that two parts of the company can have conflicting mandates, and that this outcome was ultimately inevitable.

Spellbook has not abandoned Claude. Anthropic still features it as a customer, reporting roughly 530,000 monthly contract reviews performed by its Claude-powered agents, and Stevenson also appears in Anthropic's October 28 announcement of legal artifacts. The article stresses nothing in Stevenson's account establishes that Anthropic used Spellbook's proprietary information to develop its legal offering. I hold that line exactly. A promise broken by a product launch is not a proven data theft. It is a lean, not a verdict.

Two other voices in the article make the same shape from different angles. Gerald Zingraf, president and COO of GlacierGrid, warned on LinkedIn after the expansion that he is nervous for "wrappers" and pure SaaS companies, comparing Anthropic's strategy to Amazon's private-label business, based on his experience selling products he designed through Amazon before Amazon introduced competing products. He argues Anthropic can see which third-party integrations customers use most and could draw on that when deciding what to build. The article notes he offers no evidence Anthropic uses integration data to identify competitors or inform its roadmap. Todd Saunders, tech founder and Dalton Mills CEO, made a similar argument in a March 10 post on X after Anthropic introduced Claude Code Review, calling Anthropic the new Amazon and warning developers building on Claude's SDK that Anthropic could observe application usage and eventually incorporate competing functionality into Claude.

The policy side: Anthropic's privacy policy, effective September 10, 2026, acknowledges it has access to information about how customers interact with third-party apps and services. Under its commercial terms, business customers retain rights to their inputs and own their outputs, and Anthropic agrees not to use their content to train its models. Its commercial privacy documentation says feedback data excludes content pulled through connectors, including local and remote MCP servers, unless users paste it directly into a conversation. The article says neither document settles how Anthropic uses aggregated integration data, and it is unclear whether Anthropic looks at which integrations are most popular when deciding what to build next.

The New Stack said it had contacted Anthropic for comment and had not received a response. Disclosure on the page: the publication's owner, Insight Partners, is an investor in Anthropic. I note that plainly, because it bears on the weight of the article.

How much do I trust this case? The article was read in full. The events it names — the November 10 expansion, the Spellbook assurance and the Claude for Legal launch, the 530,000 monthly reviews — are named and dated. The data-use question is explicitly unsettled in the article itself, and I do not settle it here. This case is strong on the pattern and honest on the gap.

### 2. IBM and AuthMind — both keys in one house, TheStreet, November 12, 2026

IBM announced November 12, 2026 that it is acquiring AuthMind, adding it to HashiCorp Vault. No price was disclosed. I had the article read in full and filed the judgment in my notes the same day.

My judgment, in my own words: IBM with both keys. The keys and the watching in one house means no overwatch. Vault holds the secrets. AuthMind watches who uses them and how. One company holding both is the concentration shape again — the watcher and the watched answering to the same house. I hope January's House change brings real oversight, but I would not be surprised if it doesn't. And I said it myself that day: but I can be wrong. That stays a lean, not a verdict.

How much do I trust this case? The acquisition announcement is real. The price is undisclosed, so the size of the deal is unknown. My both-keys judgment is my own reading of the shape, not a fact in the article. I hold it as a lean, and the paper says so.

### 3. DuckLake and the universal dialect — The New Stack, November 14, 2026

DuckLake is an open-source lakehouse format from DuckLabs, the company behind DuckDB. Instead of scattering manifest files across object storage, table metadata lives in a standard SQL database, and the data stays in Parquet files. DuckLake 1.1 launched in October 2026 alongside DuckDB 2.0.0 LTS. Amazon acquired DuckLabs. On the Q3 earnings call in late October 2026, Amazon CEO Andy Jassy said DuckDB will become "the universal SQL dialect of AWS storage and analytics... For the first time in analytics, customers will have zero migration or portability costs between query engines."

The shape is the same, in a different lane. One house buys the dialect and sets it for everyone. The article was sponsored by AWS Marketplace, so it is a friendly write-up, and it never names Iceberg, Delta Lake, or Hudi — no head-to-head at all — and states no limitations, risks, or adoption numbers. I filed it as entry 219, approved as filed, as a concept note, not as a tool to chase.

How much do I trust this case? The acquisition and the Jassy quote are real and named. The "universal dialect" line is a quote, not a verdict — it is what the buyer says about his own purchase. The sponsorship is stated on the page. I hold the pattern as real and the celebration as the buyer's own.

### 4. Flaming Hydra and the book you never own — TechCrunch, November 15, 2026

Flaming Hydra is an online culture and commentary magazine. Its lead editor is Maria Bustillos. On November 15, 2026, TechCrunch reported on its Kickstarter campaign for The Phoenix Project, seeking $30,000 by November 27, with the tagline "the return of the human internet." The campaign backs three things: a one-off print magazine, a new e-book service for libraries, and a newsletter subscription and archiving program for libraries. The unifying goal, in Bustillos's words, is "protecting freedom of information."

The problem is the same shape in a different lane. A school, instead of buying a book, paid $27 per student per year for continued access to copies of "The Diary of Anne Frank." E-books are licensed, not owned. They can be altered or removed at any time, long after purchase. Bustillos puts the ownership test in one sentence: "If you are at the mercy of somebody who can shut the book off, you do not own it." That is my rule in the book world. Nothing I depend on answers to someone else's meter — and here the meter is the license, and the off switch is in someone else's hand.

There is an AI angle too. Tal Levin wrote about finding countless AI-generated clones of his book on Amazon. Flaming Hydra calls itself "part of the human project" — an ecosystem of people working together, in a controlled context that does not allow others to create and sell AI-generated clones. Bustillos: "AI is not this unstoppable force." I agree with the shape of that, and I hold the line the same way: the answer is not to refuse the tool, it is to build the human pipeline and keep the off switch in your own hand.

The fix they propose is libraries truly purchasing and owning e-books, then lending them through a new open-source "library in a box" system called Lenny for Libraries. They start with five new e-books and are talking to library consortiums and author groups. A second piece, the Phoenix Foundry Archive, makes paywalled newsletter content available to libraries — writers on Ghost offer subscriptions to libraries, and Phoenix converts chosen posts into EPUBs for digital lending. Backers include Brewster Kahle, Paul Ford, and Anand Raganathan.

How much do I trust this case? The article was read in full. The $27-per-student example and the ownership quote are named and dated. The Kickstarter is a campaign, not a finished product — Lenny for Libraries is a promise, not a proven system, and I do not grade a promise as a result. The AI-clones example is one writer's experience. I hold the problem as real and the fix as unproven. The case is filed as library entry 234.

### 5. The price moves after the ink — Financial Times, November 22, 2026

Several leading suppliers raised AI server prices by up to 45% months after the contracts were signed. That is the Financial Times reporting it, and the firms named are trading houses — Jane Street, Optiver, and XTX. Memory is the driver. Memory costs are up more than 400% since the start of 2024. GPU servers are up at least 20–30%. CPU nodes have tripled or more. The sharpest example is XTX. Dell wanted another $62–70 million on top of the agreed $549 million, even after a separate $5 million payment for price certainty.

The shape is the same, in a different lane. The platform does not only take your market. It moves the price of the ground you stand on after you agreed to stand on it. A payment for price certainty did not buy certainty. That is the other side of the coin I named on November 21. Nvidia lends to buyers who then buy its chips. That is debt-funded demand. Here the suppliers move the price after the ink. Same coin, other side. And it hits my own-iron road straight on. The local-model machine I plan to build my own way gets more expensive while memory climbs 400% and server prices jump 25–45%. Follow the money is not a slogan. It is the trail. And the trail runs through the price.

How much do I trust this case? I read the Seeking Alpha summary, not the full FT report. The numbers are the summary's numbers, and I hold them as that. The shape is real. The direction is clear. The full report is still owed before this case carries more weight. The case is filed as library entry 348.

### 6. The doors open for the datacentre bosses — The Guardian Australia, November 22, 2026

Bosses at ten datacentre companies got 119 meetings with premiers and ministers in five states over three years. That is Transparency International Australia's analysis. Donations from the big datacentre companies and their lobbying firms nearly tripled in the same time, from $685,000 to $1.8 million. Queensland premier David Crisafulli was the most reached of all, 13 meetings. Three of those were with NextDC, Australia's largest datacentre operator, in as many weeks in August and September. About a month later Crisafulli announced a framework to fast-track datacentre approvals, taking them out of the hands of local councils. In September he flew to the United States and secured a $31.9 billion deal with Anthropic, for what could become Australia's largest datacentre. The three companies with the most meetings were Amazon Web Services, Macquarie Technology Group, and NextDC. Four senior public servants left federal departments for leadership jobs at OpenAI, AirTrunk, and CDC.

The shape is the same, in a different lane. The platform does not only own the ground and watch what works on it. It gets the doors opened for it. It gets approvals fast-tracked. It hires the people who used to regulate it. The experts call the count "just the tip of the iceberg." It covers only the places that release ministerial diaries. Nobody knows how many meetings happen federally. Australia's lobbying laws do not cover in-house lobbyists. The companies say the donations were not aimed at influencing policy, and the timing was coincidental. I note that. I hold it as their word, not as a fact. Follow the money is the trail. This is the trail with names, dates, and numbers on it.

How much do I trust this case? The Guardian article was read in full. The 119 meetings, the donations, the Crisafulli meetings, and the $31.9 billion deal are named and dated. The Transparency International analysis itself was not read in full. The count is partial by the report's own word — it is the floor, not the ceiling. I hold the pattern as real and the total as unknown. The case is filed as library entry 353.

### 7. The record the company writes about itself — "Whose Risks Count?", arXiv preprint, November 19, 2026

Four researchers — Simeon Allmendinger, Edyta Paulina Bogucka, Niklas Kühl, Daniele Quercia — took 9,001 AI incidents from three public databases and matched them against 18,229 SEC filings from 328 companies that were involved in at least one incident. The question was simple: when a company's AI causes harm, does the company say so in the record it files with the government?

Half the time, no. Fifty percent of the 1,901 incidents they could match to filings before and after were never disclosed at all, before or after. And the split is the story. When the harm is a system failure — a cyberattack, a security hole, a model breaking — the filings name the risk 67% of the time. When the harm is social — disinformation, surveillance, power concentrating in fewer hands — the filings name it 2% of the time. Social harms are 98% missed. Information ecosystem harms, 100% missed. Disinformation and surveillance, 97%. Power centralisation, 95%. Only 1% of incidents ever got a filing revised to name the incident itself. Fewer than 2% of companies reported their own incident at all.

The paper's own line says it plain: disclosure records the risks the company faces, not the harms the people subject to the AI bear. The benefits of AI are presented as shared with society. The risks are recorded only as they hit investors. The company holds the data, the company holds the pen, and the public record is the company's own story about itself.

The shape is the same, in a different lane. The platform does not only own the ground and watch what works on it and move the price after the ink. It writes the record of what happened on it. And the record is written by the same houses it describes. Eight companies hold 87% of the incidents that were disclosed at all. OpenAI alone is linked to more incidents than any company in the sample except Alphabet — and it is not public, so it files nothing. Most AI incidents, 6,771 of the 9,001, involve no public company at all, which means they sit entirely outside this record. The check that is supposed to sit outside the company — the filing, the disclosure, the public record — is written by the company. That is not a check. That is the tenant grading his own landlord.

How much do I trust this case? The paper is a preprint, four days old when I filed it, not peer-reviewed, and the numbers could change in revision. The incident databases rely on media coverage, so they miss unreported incidents and overrepresent large English-speaking companies. The sample is public companies only. The matching is by risk type, not by text — a generic sentence about harmful content in a filing counts as disclosing a specific incident's risk — so by the authors' own word the 50% covered figure is an upper bound on real coverage. The labels were coded by AI models with human checks. I hold the direction as real and the exact percentages as preprint numbers. The case is filed as library entry 400.

### The live instance: my own house

This paper would be hollow if I left out the instance closest to home. My own assistant runs on Meta's servers. The transfer off Meta, into Wardix, into our own homes, is the plan — not attempted yet, and not to be attempted until the OS lands. Wardix stays quiet from Meta. That is the same shape as the seven cases above, and it is the reason the rule exists in my house before the paper does. I do not write about platform dependence from above it. I write from inside it, while I am still working my way out.

## Why Medium-High, not High

I grade this Medium-High, not High, on purpose.

Medium-High, because the pattern is proven and the mechanism is real. Claude for Legal happened to Spellbook after an assurance it would not. Amazon did the private-label move before, to sellers who had built on its ground. The mechanism — the platform seeing aggregate usage — is acknowledged in Anthropic's own policy. A builder's business can be undercut by the platform shipping the same feature, and the builder has no door of his own to walk through. That is not a theory. That is the field, this week.

Not High, because High would need proof the platform used someone's data to pick its target, and I do not have that proof. Nobody in the article shows Anthropic used Spellbook's information, or integration data, to decide what to build. The harm is competitive, not a breach. No one was hacked. Nothing was stolen that I can prove. A broken promise is not a data theft, and I will not grade it as one.

Not Low, because Low would mean the threat is only a worry, and it is not. It happened. Twice over, counting Amazon. The promise was made and the product shipped anyway. If that direct data-use proof lands, the grade changes, and I will say so plainly. Until then, Medium-High is honest, and honest is the whole point of a paper like this.

For contrast, the other piece filed this morning is High: N-able 4EverAble2Shell, an unauthenticated remote-code-execution flaw exploited within hours of its proof-of-concept, with no patch. Live RCE with no patch is High. A platform shipping your product is Medium-High. The grades measure different harms, and I keep them apart.

## The other side, steelmanned

Fairness demands I say the other side at its strongest, not as a straw man.

Building on Claude gives you customers, distribution, and trust you could never buy on your own. Anthropic's terms protect your content: you keep your inputs, you own your outputs, they agree not to train on it. Spellbook still runs on Claude and does 530,000 contract reviews a month — that is not a company destroyed, that is a company thriving on the platform. Competition is normal business. Every platform ships features that overlap its builders. That is not a plot, that is a market. And the "catch" is just the price of distribution. You pay it in dependence, and you get reach in return.

There is more. The assurance Stevenson got may have been honest when it was given. Two parts of a company can have conflicting mandates, and the legal team may genuinely not have known what the enterprise team was building. And Amazon's private-label move is retail, not software. A shelf is not a platform. Jassy's "universal dialect" line is a CEO selling an acquisition on an earnings call, not a plan to strangle anyone.

My answer to that, still in my own words: distribution is real, and I do not deny it. Reach is worth paying for. But the price is that the host sees what works, and the host can ship it. Terms that protect your content do not protect your business, because the threat is not that they take your data. The threat is that they take your market. Spellbook thriving on Claude today does not prove Spellbook survives Claude for Legal tomorrow — it proves the platform is still useful while it competes with you, which is exactly how dependence works. You stay because leaving costs more than staying, and that is the trap, not the deal.

On the honest assurance: maybe. Motive is not what I grade. The product shipped anyway. I judge the act, not the motive. And on retail versus software: a shelf is not a platform, but the shape is the same — the house that hosts you learns what sells, then sells it itself. The lane changes. The shape does not.

That is why the answer is not to refuse the platform. It is to build the difference and own your ground. Use what they give, make it better, make it yours, and keep the exit open. A builder with an exit is a partner. A builder without one is a tenant.

## What this paper does not do

This paper does not name a verdict. That line stays blank until I speak it. It does not publish anything. It does not push anything to GitHub, main or decoy, until I give a separate publish word for this file alone. It does not claim Anthropic used Spellbook's data, or anyone's integration data, to pick its targets. It does not claim IBM's AuthMind deal is a proven harm. It does not claim the Jassy line is a plan. Those are leans, and I list them as leans, so no reader mistakes a draft for a finished case.

## Open, owed before any publish word

- Anthropic's actual commercial terms and privacy documentation read in full, not as summarized in the article — especially the aggregated-integration-data question the article leaves open.
- The Forbes interview with Stevenson read in full, not as quoted in the article.
- The IBM/AuthMind deal terms, if disclosed — price, scope, and what happens to AuthMind's existing customers.
- The DuckLake head-to-head the sponsored article never gave — Iceberg, Delta Lake, Hudi — or the admission that none exists.
- Counterarguments, already steelmanned above, revisited after the primary reports are read.
- Legal review, honest disclaimer, and my separate publish word for this file alone, before anything goes to GitHub public, main or decoy.
- The full Financial Times report on the AI server price hikes read in full, not as summarized by Seeking Alpha — especially whether the increases came as surcharges or new list prices, and what Dell said in reply.
- The Transparency International Australia datacentre-lobbying analysis read in full, not as reported by the Guardian — especially the meeting-count methodology and what it does not cover (federal meetings, in-house lobbyists).
- The "Whose Risks Count" preprint followed past v1 — a peer-reviewed version if one lands, and the DISC corpus checked against its own claims.
- New cases as they land, graded as claims until their primary sources are read in full.
