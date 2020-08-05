---
title: 'Stanford’s Duffie shakes up SOFR credit race with AXI index'
date: 2020-08-03T12:00:00+02:00
categories: ['risk-net']
tags: ['2020', '202008', 'derivatives', 'SOFR', 'credit spread', 'LIBOR']
description: 'Academics propose new credit index that ditches Libor tenors for a single funding spread'
---

{{< quote 4682b4 >}}_Academics propose new credit index that ditches Libor tenors for a single funding spread_{{< /quote >}}

US lenders in search of a credit-sensitive interest rate benchmark may soon be spoilt for choice.

A trio of academics led by Stanford University’s Darrell Duffie have developed a new credit spread index that can be layered on top of the secured overnight financing rate, the US Federal Reserve’s preferred US dollar Libor replacement.

The ‘across the curve credit spread index’ – known as AXI – is competing with the Ice Bank Yield Index (BYI) and Ameribor for the backing of the Credit Sensitivity Group, which was [convened in February](https://www.newyorkfed.org/newsevents/events/markets/2020/0225-2020) to recommend ways to make [SOFR more palatable for lenders](https://www.risk.net/risk-management/7561711/credit-problem-sofr-faces-uphill-struggle-in-loan-market). The CSG’s members consist of banks, regulators and outside experts, including Duffie.

In contrast to other benchmark alternatives, AXI ditches term settings in favour of a single spread that measures the weighted average cost of wholesale unsecured debt funding for US banks in maturities from overnight to five years. The methodology can also incorporate corporate credit spreads to reflect a client’s cost of funding.

While other indexes seek to closely mimic Libor, AXI’s developers proclaim its differences as an advantage.

“The whole reason we’re in this problem is that Libor is no longer representative,” says Duffie, who is professor of finance at Stanford University’s Graduate School of Business.

“There are almost no transactions with which to fix Libor, so if we want it to be representative, we would want to stay away from Libor and look at the actual funding banks are getting. That’s what this index does – it moves to wherever the actual fundings are. If they turn out to be short term, then it weights the short-term rates. If they turn out to be long term, it weights to the long term.”

Duffie developed AXI with Antje Berndt and Yichao Zhu at the Australian National University. His involvement gives the project a measure of credibility in regulatory and banking circles. As chair of the Financial Stability Board’s market practitioners group, Duffie led the first major effort to reform Libor in 2013. One industry source describes the emergence of AXI as “a game-changer”. Others agree the index could have legs.

“The paper lays out a rationale that could potentially work. We’ll need to dig into the details some more,” says Mark Brell, executive vice-president of global trade services at Texas-based Frost Bank and a CSG member. “There’s probably three or four dogs in this hunt right now. It will be interesting to see what the final decision of the credit sensitivity working group is.”

Besides BYI and Ameribor, IHS Markit is also said to be [developing a credit spread add-on](https://www.risk.net/derivatives/7543416/markit-plans-sofr-credit-spread-add-on-using-cds-data) for SOFR using credit default swap data.

### Ditching the tenors

SOFR’s lack of credit sensitivity has long been a source of concern for lenders. In a 2019 letter to regulators, a group of [10 US regional banks](https://www.risk.net/comment/7527776/how-regional-banks-could-shape-us-libor-replacement) warned that lending could become unprofitable during periods of economic stress, when the cost of funding tends to deviate from risk-free rates.

The CSG was established to look into these concerns. The group is now assessing a range of credit-sensitive indexes that can be layered on top of SOFR.

At first glance, AXI bears some similarity to one of those alternatives – Ice’s BYI. Both indexes are based on short-term primary bank funding transactions and secondary market bond data from the Trace reporting system. That’s where the commonalities end. While BYI buckets transactions according to their maturities to produce one-, three- and six-month settings, AXI generates a combined rate that is automatically skewed towards the most active market segments.

The methodology weights individual bond transactions by volumes and recent issuance metrics. For example, if primary issuance of one-to-two-year maturities outstrips issuance of four-to-five-year securities in the preceding year, a $2 million trade in a security with an 18-month remaining tenor would carry more weight in the index than a similar-sized trade with four years outstanding.

A separate short-term component based on money market maturities is incorporated in the rate and could be bolstered subject to the availability of more robust data.

Duffie argues this approach delivers a spread that adapts to evolving market trends and is more representative of a bank’s true cost of funding. “Changes in regulation and market structure have caused the banks over the years to switch their maturity structure back and forth across time,” Duffie says. “If you were to fix on a specific maturity, your approach would become obsolete after market structure changed again.”

Regulatory changes introduced after the 2008 financial crisis require banks to hold more stable, longer-term funding, resulting in fewer short-term transactions of the type used to generate Libor-like rates. The Federal Reserve estimates there are just six or seven transactions underpinning one-month and three-month US dollar Libor on most days, while six-month settings may reference just two transactions. Trace volume in the longer-term transactions used in the AXI methodology ranges from $8 billion to around $30 billion per month.

The inclusion of longer-term bond yields means AXI typically trades at a higher level than Libor or BYI. This may make it unpalatable for non-US banks, which tend to be more intensive users of short-term dollar funding and may want a spread that primarily focuses on money market issuance. “It’s designed for US banks, so if foreign banks are not funding the way that US banks are, then this would be less representative for foreign banks,” says Duffie.

AXI’s skew towards the largest bank issuers may also make it a poor fit for smaller lenders if their funding spreads are not sufficiently correlated. Some of these banks have expressed a preference for Ameribor – though Duffie notes most banks currently reference Libor, which reflects the funding costs of only the largest global dealers.

### Derivatives potential

Removing maturity buckets and ditching term settings means AXI can reference a larger pool of transactions. According to Duffie, this is critical for the development of robust derivatives markets, which would allow banks and end-users to hedge the credit component alongside their SOFR exposure.

For potential users, it’s a vital selling point.

“I am completely in agreement that if there is a credit-sensitive index – whether it’s called AXI or whatever else it might be, there does need to be a deep, liquid underlying derivatives market for banks and our customers to hedge the underlying index or hedge the underlying risk,” says Frost Bank’s Brell.

Duffie concedes there is more work to be done on the index. To make it suitable for commercial use, a benchmark administrator would need to more data inputs, particularly in short-term markets. The short-term funding component of the current version of AXI relies on data from Ice Benchmark Administration, which is split into maturity buckets and must be approximated. More comprehensive money market data could be sourced from the Depository Trust & Clearing Corporation or the Federal Reserve.

The bond data taken from Trace may also need to be embellished for commercial production. While the reporting system publishes intraday transaction data, individual trade sizes are capped at $5 million. Full reports incorporating large trades are published with a several-month delay. This “uncapped” data was used for testing purposes, meaning the rate was only calculated up to late 2019. A live benchmark would require real-time activity and may have to ditch the largest transactions. Duffie’s analysis shows this would make little difference in the rate, but inclusion of larger trades would bolster the rate’s representativeness and ward off potential manipulation.

Input data need not be limited to US bank debt. In additional analysis, corporate debt was added to the mix. “It’s not a question only of the bank funding costs, but of the costs of funding to the corporate borrowers as well. If that’s the case, and since they’re almost the same, why not deepen the pool of transactions?” says Duffie. “If you include corporate borrowings it hardly changes at all. And yet you get five times the volume of transactions, so that that would definitely make it very robust.”

This may dissuade corporate borrowers from opportunistically drawing down SOFR-linked credit lines, which may appear cheap next to their own ballooning credit spreads in stress periods. Data from Refinitiv show $238 billion was tapped from credit facilities during the Covid-19 crisis, compared to just $38 billion during the global financial crisis in 2008 and 2009.

