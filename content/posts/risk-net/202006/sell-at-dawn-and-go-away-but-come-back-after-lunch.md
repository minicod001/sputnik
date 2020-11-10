---
title: 'Sell at dawn and go away – but come back after lunch'
date: 2020-06-15T12:00:00+02:00
categories: ['risk-net']
tags: ['FX']
datum: ['2020', '202006']
description: 'Historic and well-known intraday seasonal patterns can deliver return-to-risk ratios in excess of 1. Tradefeedr’s Alexei Jiltsov explores whether execution desks should employ these factors'
---

{{< quote steelblue >}}_Historic and well-known intraday seasonal patterns can deliver return-to-risk ratios in excess of 1. Tradefeedr’s Alexei Jiltsov explores whether execution desks should employ these factors_{{< /quote >}}

The variables that help forecast the future direction of asset prices are a hot commodity. Every time predictability is discovered, it is eventually either arbitraged away or labelled as a risk factor. The former is commonly known as alpha, while the latter is often referred to as alternative – or smart – beta. The efficient market theory refers to the discovery of predictability as anomalies.

By definition, predictability is any repeatable pattern in prices. Some well-known patterns are not even based on complex mathematical models, but represent simple calendar-based rules. For example, think of the classic “sell in May and go away” mantra – a tendency of the stock market to underperform over summer months.

Empirical facts are normally explained by a “theory” – usually in an ex post fashion. For example, in this case the holiday season is considered to be the reason behind the market sell-off in May.

As the quest for predictability continues, the number of false discoveries grows at an ever-increasing speed. One solution would be to come up with a theory first, and then look for empirical evidence consistent with it. However, that’s easier said than done.

Another option is to revisit previously discovered anomalies. If they still hold true, chances are there is a structural reason for them to exist.

Our approach in this article is to dust off a set of simple anomalies all based on time of day. We will then present empirical evidence and discuss whether an efficient execution desk should adopt such anomalies.

### A predictable time-of-day pattern

First, let’s consider a well-known time-of-day pattern in foreign exchange returns. The idea behind it is simple: currencies tend to go down in local trading hours and up outside of them. For example, EUR/USD would depreciate during early London trading hours and appreciate after the New York open.

The original pattern has been documented over the overlapping time zones, since there is a window where both London and New York are open at the same time. We simplify this approach and split each day into two periods: mornings and afternoons. This is because we would like to express this pattern in terms of trading strategies and do not want a period with no-position.

The average intraday dynamics are shown in figure 1a and 1b, with the red area representing morning hours and the green area representing afternoon areas – both in local time. The pattern of EUR/USD and AUD/USD are remarkably similar, with a sharp sell-off during morning hours, followed by a recovery in the afternoon.

334025ed-df38-426a-80df-68690ed1e12a

60ff06e6-faa7-49a5-b5df-872b6f728c73

This pattern was described in academic literature by Ranaldo (2009), although it was originally borrowed from an early paper by Cornet et al (1995). The behaviour was then linked to order flow dynamics by Breeden and Ranaldo (2011), who found local currencies are net-sold in the morning and bought in the afternoon.

What could be the theory behind this behaviour? At first glance, it would look like local traders prefer to sell their own currency and foreign traders buy it in return, which begs the question: do the former know something negative about their currency or is it just a case of ‘the grass is always greener on the other side’ syndrome? Some studies suggest it is importers who drive the demand for foreign currency in the morning, thus driving the net selling of the local currency during that time of day.

While the precise nature of this behaviour is hard to uncover, it is important to highlight the pattern that emerges from it. Unlike well-argued FX carry trade strategies, which direct capital from low to high rates and are exposed to the global economic cycle, there is no obvious macro reason for the intraday pattern to exist.

Let’s now consider how stable these dynamics are over time. If we aggregate the price dynamics over mornings and afternoons, the difference becomes quite striking, as shown in figure 2a and 2b.

81120d57-ffba-43b0-9500-30c6117fd034

