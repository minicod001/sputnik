---
title: 'Avoiding market impact – it takes two'
date: 2020-07-13T12:00:00+02:00
categories: ['risk-net']
tags: ['FX']
datum: ['2020', '202007']
description: 'Dealer hedging practices have a big part to play in quiet execution, but so does client behaviour, writes UBS's Ciara Quinlan'
---

{{< quote steelblue >}}_Dealer hedging practices have a big part to play in quiet execution, but so does client behaviour, writes UBS's Ciara Quinlan_{{< /quote >}}

Electronic foreign exchange markets have undergone an extensive transformation over the past decade, raising many questions about what are the most efficient trading practices and technology. Throughout this transformation, the job of trading spot FX has become increasingly complex as the market has fragmented. Participants can choose from a large number of liquidity providers (LPs), which they can connect to directly or via one of the many multi-dealer venues.

The majority of market participants connect to multiple LPs, aggregating their prices in order to compress their bid/offer spreads. This can often involve splitting their original order into smaller ones and sending them to multiple LPs simultaneously, a process often referred to as ‘sweeping’. Furthermore, market participants can choose to trade either on a disclosed or anonymous basis, meaning the client’s name might either be revealed or unknown to the LP at the time of the trade.

In the early years of electronic FX markets, a common execution approach was to aggregate as many LPs and electronic communications networks as possible in order to reduce aggregate spreads and increase competition – and, by doing so, minimise execution costs. Instead, however, an increasing number of LPs meant that many market participants experienced the ‘winner's curse’ syndrome, where the liquidity pool intensifies and, contrary to initial expectations, spreads widen and execution costs increase.

The winner's curse is a concept originally established in auction theory, where the winning bid has a systematic bias to overprice the value of the auctioned good. Similarly, in an FX setting the winning LP potentially misprices the asset and subsequently fails to derive an economic profit from the trade.

To optimise execution costs, market participants started using more sophisticated analytics tools, such as transaction cost analysis software, to guide their order routing using historic fill ratios and a consideration of the opportunity cost of order rejects. As a result, in the past couple of years the focus has shifted towards analysing market impact.

### Internal affairs

Market impact, or the effect an order or trade has on subsequent price movements, can occur for multiple reasons. The most obvious is likely the trade itself being executed and observed in real-time directly on a market trade feed that publishes order prices and/or executed trade prices. A less obvious cause, but one that can be just as harmful, occurs when a client trade executed with an LP leads them to actively hedge on a lit market or skew their pricing. Even small orders can have market impact.

A standard approach to analysing market impact is to generate mark-to-market charts which track the evolution of the market price over a certain period around the time of the trade (see figure 1).

57397a05-49d8-4da9-bb6e-36241453ceaf

The market impact caused by LPs may differ widely depending on how they hedge client trades or manage risk, and in our view internalisation of client trades is one of the most effective ways to reduce market impact.

Internalisation refers to the process whereby an LP can offset its risk by skewing or showing an axe based on existing inventory positions, as opposed to accessing an external market to hedge risk. This offset does not usually occur instantaneously, and during this period, which typically lasts for minutes, the LP will be exposed to market risk. If a trade is internalised by the LP, then by definition it does not interact with a lit market and so should minimise market impact. A market participant can begin to differentiate its LPs by considering their ability to internalise, typically driven by how broad and diverse their client base is.

A market participant can assess its own market impact by analysing its mark-to-market plots. When the market consistently moves against the LP after a trade, it not only becomes more expensive for the client to trade the remainder of a larger amount, but the initial trade is less economically profitable for the LP. The more pronounced the market impact, the less time there is for an LP to internalise a trade without incurring losses. Over time, this cost to the LPs will typically result in a widening of spreads offered to the clients.

When a client trades with multiple LPs within a short period of time, if one of them causes market impact, this will appear as a client market impact to the other LPs. In this way, one LP in a client’s liquidity pool causing market impact can, over time, cause the other LPs to widen their spreads to that client.

For this reason, the focus of the analysis needed to maximise competition while limiting adverse selection and minimising execution costs has shifted from the optimal number of LPs to the optimal selection of LPs.

Often, combining a small number of LPs with low market impact and high internalisation ratios can lead to a stable equilibrium where competition is maximised. However, adding even a single LP with pronounced market impact on average could negatively change the dynamics of the liquidity pool. As each LP's optimal strategy changes, the potential internalisation horizon shortens and the urgency to exit positions increases. This leads to higher costs for LPs, which could eventually be reflected in wider spreads for the client. Careful selection of LPs and monitoring of market impact is therefore critical to achieving optimal execution over the long run for FX participants.

Ciara Quinlan is global head of principal electronic trading at UBS

