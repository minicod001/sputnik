---
title: 'FX algos and the weight of industry expectations'
date: 2020-08-25T12:00:00+02:00
categories: ['risk-net']
tags: ['FX']
datum: ['2020', '202008']
description: 'Algo usage may reach saturation point unless operators try something new, writes Matt Clarke of XTX Markets'
---

{{< quote steelblue >}}_Algo usage may reach saturation point unless operators try something new, writes Matt Clarke of XTX Markets_{{< /quote >}}

Oaktree Capital’s Howard Marks wrote a wonderful memo on how investors should adjust their forecasts by considering what’s already priced in. He calls this “second-level thinking”. If you believe a company’s prospects are good but the market thinks they’re great then you should expect its stock price to fall, he advises. This is not an intuitive reaction for most of us.

Foreign exchange algos are currently a bit like that. There’s no question the outlook is extremely promising for this business, but an awful lot is priced in. Sustaining current growth levels may require a different approach to what worked in the past. We may find ourselves at an inflection point where the algo market and what clients require from such products is about to change.

Social media platforms offer an instructive analogy. From a low base, it was possible to grow rapidly in the early years simply by adding new users. As these platforms gradually reached pretty much all of the audience who were suitable for the product, year-on-year user growth numbers started to flatline. Hardcore distribution of product works at first but inevitably it stops being effective.

After they ran out of new users to onboard, these platforms broadly followed two strategies. First, they tried to make the existing product better. If you’ve run out of users to add, you can still increase each user’s engagement. Second, they began acquiring and adding new products. This allowed users to do additional activities on the same platform: branching out into image sharing, food delivery, messaging, and so on.

We may not be far off reaching client saturation in FX algos. If growth is to be maintained, it is likely to come from two areas: first, making the existing product better so it wins more of the available business per user; and second, extending the instruments offered via algos.

### Algo economics

For a standalone business you presumably need a minimum of 10 people: two sales-traders in each region (to provide cover for when one may be sick or on holiday); two developers; a quant; and someone in compliance. In reality, the headcount will likely be larger.

Back-of-the-envelope calculations of estimated volume and yield suggest a relatively modest NTI for a product that commands so much attention. Even allowing for adjacent swaps revenue and ignoring infrastructure costs, which are not trivial in the case of primary market data, the NTI per head feels light by investment bank standards.

So, why the widespread optimism? This business is growing. The growth in FX algos can be seen as part of the wider shift in transferring more execution risk from the sell side to the buy side in fixed income, currency and commodity (Ficc) products. Almost every data point suggests algo volumes are growing at double-digit percentages annually. A relatively small business that compounds at 20% each year soon becomes a meaningful one.

Marquee clients are genuinely enthusiastic about these products, too. That helps. A popular algorithm might encourage an asset manager to prioritise documentation that opens up other areas of Ficc business.

Nonetheless, the current wave of optimism and investment must largely be based on a belief that the recent growth rate will continue for the next five to 10 years. But will it?

### The bear growth case

Oxymoronic as it sounds, let’s consider the bear growth case. The general consensus among operators and clients is that algos had a good crisis. [Volume records were broken](https://www.fx-markets.com/trading/7510491/in-choppy-fx-markets-algos-buck-expectations). Reminiscent of the ‘USD smile’ theory, which holds that the dollar rises when the US economy is both extremely weak and extremely strong, it seems that in both low and high volatility regimes, clients are opting to use algos.

Yet logic and simple arithmetic dictate that it will be tricky for algo businesses to continue growing at double digits for a full five to 10 years. There simply aren’t enough suitable clients left to pitch that can give large parent orders and are willing to accept market risk.

So let’s look at the minimum by which we can expect the algo market share to grow. There are three conventional areas from which algos could attract additional volume: large tickets traded on electronic risk-transfer; orders worked on voice; and white-labelling to other banks.

All these areas are likely to contribute extra volume to algos over the next five years. However, each area is finite and it would be naive to expect algos to replace any of them fully. Many clients will have a preference for the immediacy and low variance of risk transfers, even if an algorithm could produce a better result on average. Equally, certain clients feel reassured by high-touch voice execution and will pay for the service.

Nonetheless it is quite possible to imagine continued volume growth for algos of, say, 50% from today’s levels. Simply due to shifting client preferences for each method of execution.

Correspondingly, you’d expect to see a decline in voice trading as a percentage of overall volumes, for example. Given the higher margin associated with voice orders this is a somewhat defensive play, but it’s unavoidable in a competitive market: if firm A doesn’t offer algorithms to the client, the reality is that firm B will.

Some also argue that FX is evolving into something akin to the equities model, where broker agency algos are the dominant way in which clients trade. Those more familiar with both markets, though, will find this argument far less convincing. There are huge differences in market structure – particularly in regulation – that offer a compelling explanation of why FX is predominantly a bilateral risk transfer market and global equities are not.

Consider, for instance, trade reporting rules for orders in Europe, which are in force for equities transactions but not for FX. It is a lot easier to risk-manage your way out of a EUR/SEK ticket if the rest of the market doesn’t know you’ve been given the risk. The idea that FX algo volumes will inevitably grow simply due to a ‘catch-up’ effect is a fragile and superficial assumption.

### The bull growth case: beating the benchmark

To consider the bull growth case, it’s important to look at which spaces algos can expand into.

Clients often use their own in-house execution algos, ranging from the simplest aggregator sweeps to more sophisticated slow algorithms. Systematic funds are an excellent example. Many of them use their own algos to gradually hedge onto a carefully curated pool of bilateral liquidity providers (LPs).

Can broker algorithms outperform clients’ internal algorithms? If so, there is scope for a substantial increase in average daily volume. There is an internal cost to building and maintaining internal execution algorithms and most clients would rather focus on their core investing activities or reducing execution costs in less liquid asset classes. Provided there’s robust evidence that the performance (net of fees) of external algorithms can beat that of internal algorithms, it seems plausible that an immense additional source of volume could be unlocked.

This is a non-trivial challenge, as these curated pools receive extremely tight spreads – far tighter than a major LP could likely access for themselves. If a client receives an aggregate risk transfer spread of 0.2 basis points in a $10 million EUR/USD trade, it requires some serious intellectual gymnastics to see how an algorithm that charges users $25 per million can beat that. However, for larger parent orders, it may prove possible for a highly skilled provider to improve upon current execution results.

Beating internal algos is a tough benchmark. However, for any provider that can do so, the reward in terms of new volume would be significant. This raises all sorts of design questions. Should finite investment dollars be directed at back-end performance improvements or more visible client widget screens? Should operators optimise for performance on average or sacrifice a little on average in order to remove occasional extreme results? Reasonable people could disagree on these points.

### Product and influence expansion

Several providers already offer non-deliverable forward (NDF) algorithms. The NDF market is rapidly becoming more electronic and a thriving central limit order book (Clob) now exists for Asian pairs. If there is strong demand from clients for USD/BRL algos for example, perhaps this will help give dealers the impetus to transition more Latin American NDF hedging – and not just pricing – onto electronic channels, as we saw with the Asian NDFs.

d48bd050-0de9-476f-a299-5d40fb30603d

FX swaps are likely to come later. A fit-for-purpose electronic Clob is more of a nascent concept here, though rapid progress is being made on that front. Again, if the algo team puts their weight behind the project, that’s one more reason for institutions to invest in the infrastructure required for electronic hedging of swaps. There is added complexity in the credit component for longer-dated tenors, but determining a credit-adjusted commission for each client seems entirely possible.

Algo operators will benefit from the rising tide of more products becoming liquid on electronic Clobs. In turn, they could gain more power over the evolution of FX market structure. This would come at the expense of voice traders within the same firm, who would traditionally have decided whether to support market structure changes and who may have had an incentive to resist these trends.

This also applies to ongoing feedback on spot Clob and electronic communications network (ECN) microstructure – tick sizes, prints, last look policies, market data, and so on. It seems likely that algo teams will have greater input into these market-wide decisions over time. This makes sense, because these nuances are crucial for their execution products.

Also relevant is the cost of excessive fragmentation in client connectivity vendors. It may sound trivial, but having to connect to more than 30 vendors imposes a cost on LPs and, as in all businesses, operational costs are ultimately passed on in the price offered to clients.

This is especially acute in the case of fee compression. Paying a platform $5 million from a commission of $35 million is rather different to the same $5 million when you only receive $15 million. If an operator can reduce brokerage and/or connectivity fees, then presumably the same algo can be provided to end-users at a lower price and the product should become more attractive.

These kinds of challenge are less glamorous, and, frankly, harder, more technical and more frustrating than things entirely within one’s own control, such as adding new features. Traditionally they have been dealt with by the main trading desk. In my view, however, they will become crucial for long-term growth and algo desks will enjoy an increasingly important role in shaping market structure.

### Analytics revolution

There’s already a well-established model of third-party analytics for algorithms. But what has been missing until recently was widespread implementation of peer universe analytics, in which algo performance is compared across providers. This is something new, and big.

For a buy-side firm to do this on their own is a tall order. To get an idea of an algorithm’s average implementation shortfall – that is, price slippage to arrival mid – a firm needs roughly 100 executions just to achieve accuracy of plus or minus $100 per million. (I’ve assumed a 30-minute execution window with annualised FX volatility of approximately 10% and a confidence level of 95%.)

Now, imagine you have 10 algorithms to evaluate. That’s 1,000 runs required even before we factor in different currency pairs, sizes and conditions. Very few, if any, clients would have enough orders to do this.

The solution is for independent platforms to facilitate the secure sharing of high-level insights among clients without revealing the sensitive details of individual orders. When you have more than 50 major clients all opting into the same peer universe, suddenly it is possible to reach a meaningful sample size. The extra data make it faster and more accurate to identify top-performing algos against a chosen benchmark. Rather than relying on a poorly performing algorithm for months while building up the data, the whole group learns collectively and quickly.

A client can plug in their size and pair, for instance, and review how each algo has performed in aggregate across thousands of similar orders, helping the trader choose whichever one performs best in line with her objectives.

6d68d1b7-3a25-4d5f-a87d-967a83ea4d90

This development is tremendously positive for algo providers. The ability to more accurately benchmark performance will give clients the confidence to use the good algorithms for a larger share of business. This will generate more data, which in turn will will help operators refine their algorithms. And so the virtuous cycle will continue.

Individual algorithms may win or lose from this transparency. As the costs of adverse selection – for example, leaving bids on a Clob that are filled just before the price moves lower – is increasingly captured, it seems likely that volume will flow away from passive orders towards alternatives such as ‘implementation shortfall’ or ‘liquidity seeking’ orders. However, the effect on overall algo volumes will undoubtedly be stimulative. Transparency begets confidence.

302bab42-c40d-43b3-9eb0-b25f2c7f132d

Boosting client confidence in algos, improving the quality of feedback for product development, and growing overall algo volumes are all likely outcomes of an increase in use of peer universe benchmarking. This is mainly work for the various analytics companies but there’s also effort required from algo operators.

At the simplest level there may be some technical or legal work associated with the onboarding of various analytics firms. Moreover, building these peer universe products requires skill. There are all sorts of details that matter. How should one account for the effect of user actions ­– suspend, speed up, and so on – on the algo’s performance? How exactly should the results be presented and interpreted? There is a lot of room for input from algo providers, as well as clients, in order to ensure the analytics are produced rigorously and presented usefully.

### Five-year view

The decisions are not easy. If you have previously invested in building your own transaction cost analysis (TCA) product and are understandably proud of it, should you continue to invest each year? Or do you take a pragmatic view that independent TCA is the dominant methodology and commit to that?

It could go wrong. Imagine that in five years’ time the industry has added another 50 algos, that algo widgets and niche use-case features have multiplied, 10 new vendors have sprung up to fragment client connectivity further, and every client who might conceivably use an algo has already been pitched numerous times. Meanwhile, there’s still no thriving interbank Clob ecosystem for swaps or Latin American NDFs, and peer universe products are not widely adopted.

I’m more optimistic. There is enormous management enthusiasm and raw energy behind the algo business. There are many talented people working in this area of the industry. Each of the necessary developments is possible, provided these areas are prioritised.

One happy final thought is that this is a business where incentives are pretty perfectly aligned. Everything that’s good for the operators of algo businesses – peer universe, better execution performance, cleaner market structure, more electronification – is good for clients, too.

Matt Clarke is head of distribution and liquidity management for Europe, the Middle East and Africa at XTX Markets in London

The views expressed in this article are the author’s personal views and should not be attributed to any other person, including that of their employer.

