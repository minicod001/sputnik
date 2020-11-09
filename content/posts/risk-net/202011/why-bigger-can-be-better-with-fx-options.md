---
title: 'Why bigger can be better with FX options'
date: 2020-11-04T12:00:00+02:00
categories: ['risk-net']
tags: ['FX']
datum: ['2020', '202011']
description: 'Large notionals often trade at significantly tighter spreads than smaller ones. Simon Nursey at Digital Vega explains why'
---

{{< quote steelblue >}}_Large notionals often trade at significantly tighter spreads than smaller ones. Simon Nursey at Digital Vega explains why_{{< /quote >}}

When we examine aggregated bid-offer spreads for foreign exchange options for different notional sizes on the Digital Vega Medusa multi-bank aggregator, we see something rather peculiar – bid/offer spreads for very large notionals are significantly tighter than those for smaller notional options.

Common sense dictates that larger sizes should demand a liquidity premium to cover the increased cost of covering the risk. So, what could explain this effect?

### Dealer intervention and auto-pricing

Trades over a certain threshold typically go to dealer intervention, known as DI, for a quick check or refinement before going out to the customer. Prices for requests under a certain threshold, however, are returned immediately without human checking. These auto-priced spreads will often be slightly more conservative to account for any delay in updating the volatility surface.

Interestingly, DI thresholds vary quite widely by liquidity provider, currency pair and customer. Even for euro/US dollar, we see thresholds of between $50 million and $250 million (see figure 1).

{{< embedded "006b527f-b8e6-44b8-991e-d9e42f6f92c3" >}}

### Skew, not spread

Spread isn’t everything when it comes to winning a trade. When we rank quotes by spread and look at which quote wins, we see that in only half the cases does the tightest price win the trade. Price skew is at least as important as the bid/offer spread.

And the importance of price skew is even more important for larger trades where traders are obliged to quote according to their book, rather than a market-neutral rate. They may also have a greater temptation to ‘read’ the customers’ direction. For trades over $200 million, we can see that only 40% of the time does the tightest quoted spread win the trade – indeed, barely more than the second-best spread (see figure 2).

{{< embedded "d64a5da0-ff6a-4ddd-8b38-275c3e9fbd4c" >}}

### Flow information

Large trades also have a much higher ‘flow value’ than smaller trades. That means they are valuable to dealers not just for the spread crossed, but also for the information they provide about customer flow and the subsequent trades they stimulate.

Although this is true of all markets, this is particularly acute for the FX options market, where liquidity is thinly spread over a much larger number of currency pairs, expiries, strikes resulting in much longer holding times.

Flow value is difficult to measure, but we can get a sense by looking at the impact on the market of trades in the time immediately following execution. In contrast to the millisecond response times of spot, options market impact times are measured in hours – between one and six. And we see a striking difference in the size of impact from the liquidity of the pair (see figure 3).

Knowledge about a trade is therefore very valuable, and preventing information leakage is key to execution.

{{< embedded "fadfe170-75d2-444e-bbe2-d2a1ba5106fe" >}}

Lastly, it is worth noting that clients trading larger sizes tend to maintain a larger stable of banks and manage their panels more systematically to stimulate competition without turning the flow toxic.

In conclusion, options users should avoid splitting trades by size – and if you do, only do it over much longer periods to reduce market impact. Limit who sees your request in order to maintain its flow value and do look beyond bid/offer spread to take advantage of skew and create diversity in your pricing panel.

Simon Nursey is head of Asia-Pacific at Digital Vega, and previously an FX options trading head at Standard Chartered and BNP Paribas.

Digital Vega is a multi-bank aggregator with a customer base covering asset managers, hedge funds, private banks and regional banks, with liquidity provided by 19 major FX banks.

