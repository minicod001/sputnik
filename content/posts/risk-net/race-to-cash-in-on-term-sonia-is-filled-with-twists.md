---
title: 'Race to cash in on term Sonia is filled with twists'
date: 2020-08-18T12:00:00+02:00
categories: ['risk-net']
tags: ['2020', '202008', 'derivatives']
description: 'Pending merger and FCA’s effort to create synthetic Libor rates could sway outcome'
---

{{< quote steelblue >}}_Pending merger and FCA’s effort to create synthetic Libor rates could sway outcome_{{< /quote >}}

The race is on to become the dominant – and perhaps singular – provider of a forward-looking term version of the sterling overnight index average, which will replace Libor in the UK market.

Three vendors are already out of the starting gates. FTSE Russell, Ice Benchmark Administration (IBA) and Refinitiv began publishing prototypes of their term Sonia reference rates in July, using fairly similar methodologies. A fourth contestant, IHS Markit, is expected to [enter the field](https://www.risk.net/derivatives/7103366/race-to-create-term-risk-free-rates-hots-up) in the coming weeks, with a radically different approach.

All four are competing for a share of a relatively small market. And there may only be room for one of them. “The most important thing is that our interest rate benchmarks are liquid and having more than one rate isn’t going to be helpful for transition,” says a treasurer at one European corporate.

The spoils for the victor may still be considerable – if not immediately obvious. The UK’s Financial Conduct Authority estimates that 90% of the UK loan market will stick with a compounded-in-arrears version of Sonia, which will be published by the regulator itself. That leaves just 10% of the market for term rate vendors to fight over. But the revenue from licensing the rate may be secondary.

“Term Sonia is not a gold mine, but if it supports your futures contract then it could be a gold mine,” says a benchmarks expert.

On the face of it, there’s little to separate the contenders. Any disparity in the currently published rates is in the hundredths of a basis point. That’s hardly surprising, given all three are based on the same primary data: committed Sonia overnight indexed swap (OIS) quotes from interdealer central limit order books (Clobs).

Beneath the bonnet, more differences emerge. Data is sliced and diced in a variety of ways, while collection windows range from 10 minutes at FTSE Russell to two hours at IBA. Varying waterfalls of back-up data may cause the rates to diverge materially in times of stress. When firm Clob quotes become scarce, IBA and FTSE Russell turn to futures markets, while Refinitiv reaches to indicative swap quotes from Tradeweb to produce the rate.

Markit’s methodology is distinctive. It uses Sonia swaps transaction data sourced from its MarkitSERV processing platform, coupled with futures trades at two yet-to-be-named exchanges, to construct its forward curve.

The race is already filled with intrigue. Some see IBA as a shoe-in, especially given the UK’s [proposed fix for so-called tough legacy contracts](https://www.risk.net/derivatives/7652276/uks-tough-legacy-fix-spells-trouble-for-us-libor-transition): a formula-based ‘synthetic’ Libor that will be built using a forward-looking term Sonia rate. As Libor’s administrator, IBA may have some sway in selecting the term risk-free rate (RFR) input – giving it a strong leg-up on the competition.

The move by FTSE Russell’s parent – London Stock Exchange Group – to acquire Refinitiv adds another element of suspense. The $27 billion all-share takeover is subject to an anti-trust investigation by the European Commission, which is due to conclude on October 27. If the deal closes, LSEG would gain control of Refinitiv’s majority stake in Tradeweb – paving the way for the creation of a single term rate that includes futures data from its CurveGlobal venture and dealer-to-client OIS swap quotes from Tradeweb in its waterfall.

“They’ve got quite complementary data so it might make sense to combine them,” says one industry consultant, referring to FTSE Russell and Refinitiv’s term Sonia rates, adding: “I can’t see LSEG wanting two rates, particularly if there’s limited usage.”

Among the competing vendors, opinions differ on how things will pan out. Stelios Tselikas, chief operating officer at IBA, expects a dominant rate to emerge after a jostle for liquidity in the early stages. “It is possible that over time liquidity will grow out of a single rate and the market will coalesce around that,” he says. “But at the beginning and for the near future, you may have more than one rate that people are using.”

Others see a more competitive environment, with different rates finding their niches and becoming the standard option for particular products. There may even be scope for wider usage of term rates beyond the loan market – for example, in rates structured products such as caps and floors that are incompatible with compounded rates.

“I think there will be multiple term rates as regulators don’t want the concentration risk,” says Scott Harman, a managing director in fixed income product management at FTSE Russell. “If the utility grew significantly and one rate became prominent, it seems like that would be counterintuitive to the objectives.”

### Method in the madness

The term rates being published by FTSE Russell, IBA and Refinitiv follow a [blueprint](https://www.bankofengland.co.uk/-/media/boe/files/markets/benchmarks/consultation-on-term-sonia-reference-rates) drawn up by the sterling RFR working group, which identified Sonia OIS quotes streamed on Clobs as the preferred inputs for forward-looking benchmarks.

All three take data from Tradition and TP Icap, while IBA adds BGC to the mix.

The methodologies for calculating a term rate using this level one data are fairly similar. The vendors harvest price quotes from the interdealer Clobs during a collection window and then slice this data into smaller segments to create dozens of synthetic order books. A series of volume-weighted mid-prices for trades above a standard market size is calculated based on a snapshot of bids and offers for each segment. Outliers are removed and an average of the remaining mid-prices is published as the final rate.

Each segment must contain a sufficient number of eligible quotes to produce a mid-price. IBA sets the minimum size for eligible quotes at £250 million ($327 million), while Refinitiv keeps this figure under wraps to prevent gaming. If the number of segments that produce a mid-price falls below a specified threshold – ranging from six out of 24 at IBA to 36 out of 40 at Refinitiv – the methodologies provide for the rate to be calculated using a second layer of so-called level two data.

This is where the differences become more pronounced. In the absence of Clob quotes, IBA’s waterfall hitches the rate to Sonia futures listed at Ice Futures Europe. Refinitiv would calculate its rate using dealer-to-client Sonia swap quotes at Tradeweb, in which it owns a majority stake.

Dealer-to-client quotes on Tradeweb are subject to last look, and questions have been raised over whether their use is consistent with the benchmark principles of the International Organization of Securities Commissions. IBA seemed to settle that debate in May when it added similar data from Tradeweb for Libor-referencing interest rate swaps as a back-up for the Ice Swap Rate, which makes its decision to exclude dealer-to-client quotes from the waterfall for its Sonia term rate all the more confounding.

The Ice Swap Rate suffered [widespread outages](https://www.risk.net/derivatives/7509006/swaps-benchmark-vanishes-as-traders-flee-firm-price-venues) during the market turbulence in March – when it relied exclusively on Clob data – as dealers pulled firm quotes from screens. Since adding Tradeweb’s data, the rate has consistently published across all four tenors and 13 maturities.

Dealer-to-client quotes from Tradeweb proved to be a solid back-up for calculating term Sonia rates [during the March turmoil](https://www.risk.net/derivatives/7532026/sonia-term-rate-contenders-tested-by-market-mayhem), according to Refinitiv. “At one point, the S&P 500 had its fifth worst day ever and even at that level of volatility we still had institutional pricing information available,” says Jacob Rank-Broadley, the company’s director for regulatory and market structure propositions.

IBA says it is sticking with futures back-ups for its term Sonia rate, at least for the time being. These form two separate levels of the waterfall. Level two – currently in development – would apply the methodology for Clob quotes to futures order books. A third level extrapolates term rates from futures settlement prices.

“We’ve implemented a detailed and robust waterfall methodology, where we’re trying to use the best available data for each level to produce a representative and reliable rate in all markets,” says Tselikas. “There are two main parts to this: one is that you want to write a rate that is representative and the other is that you want to be able to produce a rate in every circumstance.”

The main criticism of relying on futures markets is that they are far less liquid than swaps. In the first quarter of 2020, Sonia futures traded £1.7 trillion notional across three exchanges, compared to £6 trillion of volume in swaps.

Rank-Broadley does not rule out adding futures to Refinitiv’s waterfall at some point, though he sees little value in doing so based on current liquidity.

“Given that level two [of the waterfall] has been persistent during volatile periods, and there has been a very low level of liquidity in Sonia futures to date, we were not in a position to justify that it added significant value,” he says. “At this stage we’ve decided to exclude futures. We will likely revisit that in due course, but it’s dependent on having sufficient liquidity and we prefer OIS data, so it would always become a third level in our waterfall.”

The Clob-based methodologies remain a work in progress and significant changes could still be made, particularly around data sources and back-up waterfalls. “What we’re talking about is benchmarking a nascent market, so we have to be flexible in our thinking and we fully expect the methodology to evolve,” says FTSE Russell’s Harman.

FTSE Russell’s waterfall is expected to include futures data from LSEG-owned CurveGlobal. Harman says Clob quotes and futures data are just the starting point for what the company hopes will be a much richer data pool underpinning the benchmark. “The more credible data you put in, the more precise the rate you'll get, so we’re not wedded to just OIS quotes. We’re looking at futures data as well, and if there is other data available in the market that would strengthen what we’re doing, of course we would review it. It speaks to the evolution of the methodology that I'm sure will be ongoing for a number of years,” says Harman.

Those looking for something truly different might consider Markit’s rate, which uses Sonia swaps transaction data sourced from its MarkitSERV processing platform as its main input. The methodology is a little convoluted. As most OIS trades are forward starting – typically beginning on the Bank of England’s Monetary Policy Committee meeting dates – Markit uses futures settlement prices to construct a base curve. Swap prices are then layered over the curve, with forward-starting instruments compounded up to the relevant business days.

In reality, the methodology is unlikely to be the main factor in the choice of term Sonia rate. Pricing, availability and regulatory backing are likely to be more decisive – and many of those details are still to be ironed out.

“There are differences, but ultimately the market will judge term Sonia by the data and what it costs,” says Navin Rauniar, partner for Libor transition at consultancy TCS. “Clients are primarily concerned with when they will be able to use term Sonia, whether the regulator will let them use it and exactly what they can use it for.”

### Twists in the tale

Corporate and regulatory actions could have a big bearing on the outcome. LSEG is awaiting approval from EU competition authorities to complete its acquisition of Refinitiv, potentially setting the stage for its Sonia term rate to be combined with FTSE Russell’s.

If the deal falls through, some see a possible tie-up between IBA and Refinitiv to strengthen the former’s Sonia waterfall with Tradeweb data. In addition to using Tradeweb’s data as a back-up for the Ice Swap Rate methodology, IBA is also working with the trading venue to develop a new US Treasury benchmark for mortgages and other interest rate products.

Then there’s the timing. Term Sonia rates may not be available for use until early 2021, to allow for a six-month testing period. A lot will happen before then. The FCA is expected to make the [first formal announcement about Libor’s cessation](https://www.risk.net/derivatives/7566041/libor-death-notice-could-be-served-this-year-fca) at the end of this year. The regulator will also gain new powers in the UK’s 2020 Financial Services Bill to create a synthetic Libor for use in ‘tough legacy’ contracts, which cannot be re-hitched to replacement rates. The FCA plans to issue a policy statement on the use of its new powers before the end of the year, after consulting with the market.

The FCA has indicated the synthetic rates will likely be built using forward-looking term RFRs as the primary inputs, with a fixed spread layered on top to reflect the bank credit risk inherent in Libor. Speaking at an industry event on July 12, Edwin Schooling Latter, the FCA’s director of wholesale markets policy, said the creation of a synthetic Libor depended on a number of factors, including the availability of inputs “on appropriate terms to the Libor administrator”. That suggests IBA will have some say over the selection of forward-looking term rates used to build synthetic Libor rates.

“Once a cessation decision is made and the FCA has a say on how synthetic Libor is going to go, I think it’s going to become pretty clear what the rate is going to be,” says the benchmarks specialist.

If the FCA decides to run an open contest, some say it will face an impossible task choosing between three almost identical Clob methodologies. This could play to IHS Markit’s advantage.

Critically, while IHS Markit’s methodology uses swaps and futures prices at the top of its waterfall, it defaults to a compounded-in-arrears version of Sonia if quote data becomes scarce – an approach that aligns with the FCA’s preference for the vast majority of the market.

“Markit has the greatest chance of being defensible just because it’s different. You can probably make good reasons for choosing it, which you can’t do with the others,” says a European rates trader at one large bank. “It makes it the most interesting of the four on the table, but it still isn’t underpinned by an awful lot of transactions.”

There will be plenty of twists and turns in the coming months, but the race itself could be over before the market gets a proper look at the final rates.

