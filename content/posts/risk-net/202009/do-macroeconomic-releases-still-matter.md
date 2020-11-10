---
title: 'Do macroeconomic releases still matter?'
date: 2020-09-29T12:00:00+02:00
categories: ['risk-net']
tags: ['FX']
datum: ['2020', '202009']
description: 'Tradefeedr’s Alexei Jiltsov explores how FX and other asset classes react to macroeconomic reports'
---

{{< quote steelblue >}}_Tradefeedr’s Alexei Jiltsov explores how FX and other asset classes react to macroeconomic reports_{{< /quote >}}

Price discovery is the process of setting a new price level that reflects new information for supply and demand. While the process is continuous, macroeconomic releases stand out as they provide the official estimate of the state of the economy.

What matters most is not the headline number itself, but the difference between published data and market expectations. A large gap usually implies a lot of new information, which is often followed by volatile price action to establish a new price level.

A number of other aspects are also important. First, not all releases are important all of the time. For example, the Covid-19 crisis shifted the attention to the job market recovery, or lack thereof, and to the demand side of the economy. Second, macroeconomic releases do not represent the ultimate truth but rather an estimate of where the economy is at.

Therefore, imprecise, lagged and in-line-with-consensus releases are typically ignored – or should be – by the market, while reliable, timely and out-of-consensus releases should result in fast market reactions.

While this may sound obvious, the definition of precise, timely and out-of-consensus depends on what the market already knows, something that is often hard to estimate. We try to address this question by studying how market reactions to macro releases change over time, and we speculate on the potential drivers. We characterise the reaction both in terms of volatility and directional moves.

Our analysis presents some estimates of the sensitivity of foreign exchange and other assets to major economic releases. The topic is well researched in academic literature, so the focus is on market trends rather than methodology.

The event sensitivity is very important for event risk management, so the following analysis should be relevant for portfolio managers and traders estimating potential loss if the payroll number does not go their way; execution traders making a decision on whether to execute before or after a macroeconomic release; algo users incorporating volatility forecast while solving for optimal execution horizon; and liquidity managers evaluating whether spreads increasing before and immediately after a macroeconomic release are justified and which liquidity provider is best at offering liquidity in difficult conditions.

### Volatility post events 

The simplest way to explore market reaction to an event is to consider post-event volatility, something we briefly touched upon [in April](https://www.fx-markets.com/tech-and-data/7520141/algo-choice-how-to-implement-a-market-impactvolatility-trade-off). Intuitively, if an event introduces lots of new information, the price action will likely be very volatile.

For each macro release, we calculate asset volatility in the five-minute window following the announcement. We annualised the volatility figures, so they are comparable to a base volatility level.

The results are shown in figure 1.

b2b01b91-2ada-403a-84d5-bb5209da02d2

The data for FX goes back to 2006, which allows us to capture a significant number of historical scenarios. EUR/USD volatility post non-farm payrolls (NFP) releases fluctuates between 50% and 150%, which is around 20 times the base volatility, which ranges between 5% and 10%. Notably, there is a downtrend in recent years.

The picture is very similar for USD/JPY, where market reaction is becoming increasingly muted. While a post-event volatility of 25% is still reasonably high, it is about four times smaller compared to the levels observed before 2015.

This pattern is broadly confirmed by gold and S&P 500 futures.

But because NFP releases are specifically about the job market, it’s also important to look at other indicators before making a conclusion. Figure 2 looks at the reaction to core retail sales (CRS) data, an indicator that covers the demand side of the economy.

a6847dad-8444-4c34-99bb-3d080a100913

Here, the FX picture is quite similar, with both EUR/USD and USD/JPY reactions at multi-year lows. On the other hand, the reaction of gold is at an average level, while equities have recently started to respond to the data again.

The evidence from these two indicators confirms a generic trend: markets are less agitated about macro releases than they used to be. To explain this, we first need to know what the forecasts were and whether they are becoming more precise.

### Better at forecasting?

In order to understand whether new information was added to the market, we need to analyse the consensus forecasts and compare them with the realisations.

Figure 3 shows the realised number for NFP and CRS. For visualisation purposes, we dropped the Covid-19 period from March onwards, as NFP figures would disappear off the chart.

The consensus forecast is way smoother than its realisation, which is a natural behaviour. There are two factors at play here. First, consensus is averaged across individual forecasts, so it’s less volatile. Second, economic forecasters tend to stay as close as possible to the average, as they don’t want to risk being the only ones who are economy

6a571a7d-5350-41cd-b8f4-e802e98f3a16

The next question is whether developments in machine learning and big data over the past 10 years have made markets better at forecasting macroeconomic releases. Looking at the pricing error over time shown in figure 3, the answer is a resounding no – the quality of forecasts is not improving.

The reason for this is relatively straightforward. Both releases contain a substantial amount of irreducible noise, which is impossible to forecast. NFP and CRS are based on surveys sent to businesses, and some return them on time while others don’t. This means macro releases are noisy and can generate surprises, so the theory that market participants have figured out the next NFP or CRS numbers and stopped reacting to it is incorrect.

### Expected and unexpected 

When economic data is released, the market has a chance to process the information and react accordingly. It is commonly accepted that the market only responds to new information, which can be approximated as the difference between the newly released data and the consensus forecast.

We will use this dichotomy to classify each economic release as either ‘higher than expected’, if the reported number is greater than the consensus forecast, or ‘lower than expected’, in the opposite scenario.

We will focus on a small selection of releases that the market considers important as they are timely and relatively precise:

- NFP and initial jobless claims, as indicators of the state of the labour market;

- core CPI, as an indicator of inflation expectations;

- CRS and ISM manufacturing, as indicators of the real economy; and

- consumer confidence, expressed by the Conference Board (CB).

Figure 4 presents the results as the price evolution around trade time (event study format). First, we classified each release as either higher or lower than expected. Second, we averaged the price paths in each category then calculated the average price path and the volatility around it to assess the statistical ssignificance

01cb325e-0281-4217-a9a5-ec169d98cde1"

The results for EUR/USD can be summarised as follows:

- A higher-than-expected NFP release results, on average, in a -20 basis point move (0.2%) in EUR/USD over the course of the next minute.

- The reaction to other events is much more subdued, ranging from about 10bp on average for CRS to under 5bp for ISM manufacturing, initial jobless claims and CB consumer confidence.

- The reaction comes extremely quickly in the majority of events, with most of the move occurring within the first minute. Out of six macro releases considered, only two (NFP and CRS) result in a permanent impact, whereby the price levels are sustained after two hours. For the remaining four, the two curves either intersect or become statistically indistinguishable two hours after the events. This seems to suggest that a strategy of ‘fading the first move’ has some logic outside the main macro events.

702ba709-da3f-46a5-841b-7e8bcfd3bed1

Since EUR/USD is a relative price in two currencies and can sometimes be hard to interpret, we create a benchmark for the same reaction using the most straightforward asset: equity futures. Figure 5 shows that good news for the economy is good news for equity futures.

Moreover, it highlights the same conclusion from the previous example, with most events resulting on average in transitory market reactions.

### FX reaction fatigue

As noted earlier, the FX reaction to macroeconomic events seems to be at its lowest level for almost a decade. From our analysis, we know this is not because macroeconomic events have become more predictable. However, imprecise economic data may have a significant impact – and with large amounts of data available to track economic performance, official data is not worth adjusting for too aggressively.

Take the co-existence of the ADP payroll and NFP, for example. ADP should not be presented as a forecast for NFP, as some in the market hope. Both reports represent noisy measures of some unobservable economic state, and hence it is up the market to respond to them.

Another example may be the current Covid-19 environment and initial jobless claims. While this is a decent indicator, other measures, such as restaurant occupancy, can provide alternative ways to take the economy’s temperature. And as alternative indicators become more widespread, the reaction to official numbers can decrease (see Denev and Amen for more examples of alternative data utilisation).

Moreover, so-called now-casting is becoming widespread. This is essentially a technique for aggregating irregular time series with the goal of having an up-to-date estimate for the variable of interest, usually GDP growth for central banks. As those models become more widely available, market participants are forced to look at new releases in this context. Put simply, is a 0.1% positive surprise on CRS really that important if the average revision size is typically of the same size?

In conclusion, to answer the question posed by this article’s headline, macroeconomic releases do still matter. But we expect the market to react in a less aggressive manner to them if they remain in their current format.

### References

- Torben G. Andersen, Tim Bollerslev, Francis X. Diebold and Clara Vega, May 2005, Real-time price discovery in stock, bond and foreign exchange markets, NBER Working Paper No. 11312.

- Torben G. Andersen, Tim Bollerslev, Francis X. Diebold and Paul Labys, March 2001, Modeling and forecasting realized volatility, NBER Working Paper No. 8160.

- Kim Christensen, Roel C. A. Oomen and Mark Podolskij, Fact or friction: jumps at ultra high frequency, Journal of Financial Economics (2014), vol. 114 (3).

- Alexander Denev and Saeed Amen, 2020, The book of alternative data: a guide for investors, traders and risk managers

- GDPNow: A Model for GDP “Nowcasting”, www.frbatlanta.org/research/ publications/wp/2014/07.aspx

