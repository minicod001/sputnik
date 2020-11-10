---
title: 'Market regimes: how to spot them and how to trade them'
date: 2020-08-11T12:00:00+02:00
categories: ['risk-net']
tags: ['FX']
datum: ['2020', '202008']
description: 'Analysing how currency pairs behave in different market regimes can improve execution, writes Tradefeedr’s Alexei Jiltsov'
---

{{< quote steelblue >}}_Analysing how currency pairs behave in different market regimes can improve execution, writes Tradefeedr’s Alexei Jiltsov_{{< /quote >}}

It is widely acknowledged that financial markets switch from one ‘regime’ to another all the time, and while the total number of possible regimes is unknown, it is still a handy mental model for market participants.

And if it’s true that history doesn’t repeat itself but often rhymes, then it can be useful to understand to which regime the current market environment broadly corresponds. A popular theme in the post-financial crisis world, for instance, was the ongoing switch between risk-on and risk-off regimes.

If we assume the risk appetite regime is the only concern, then risk indexes, which aggregate a number of volatility, credit and liquidity metrics into a single metric, might be the first choice for the job. It is no surprise that most sell-side companies still offer them as a service after they first appeared in the 1990s. These indexes translate volatility, credit risk and liquidity indicators into simple, discrete states such as risk-on and risk-off.

This approach has a number of drawbacks, however. First, maintaining a constant number of variables in the mix can be difficult, as new ones appear regularly while others that were once the focus of the market become irrelevant. Second, tradable variables of interest – such as foreign exchange, equities and bonds – can change their behaviour under different regimes.

It would be more useful if the market regime could describe both the market risk attitude and the likely reaction of the assets we are interested in. This could imply that a good regime model for equities might not be directly applicable to FX – and vice versa – if it fails to capture the intricacies of the asset of interest. The alternative approach of Kritzman et al (2012), who use fundamental data such as inflation to identify regimes, should also be noted, but it would require careful calibration of market reaction in different growth and inflation regimes.

### Classical FX reaction to other asset classes

To explain how market regime analysis can be useful, we begin from a standard study of FX reactions to moves in equities and bonds. We split daily equity returns (S&P 500) and bond yield changes (US 10-year Treasuries) into five quantiles based on the size of the move, then calculate the average FX return in each quantile for EUR/USD, GBP/USD, USD/JPY and AUD/USD. The results are shown in figure 1.

e6f1f327-2c0b-408a-a967-3acc37ff0726

When S&P 500 returns are high, AUD/USD outperforms – and vice versa – while other currencies are less sensitive. The yen is countercyclical, which is why the currency is sometimes thought of as a safe haven, meaning it acts as a hedge by outperforming when the S&P 500 is down. The reaction to US bonds is well known, with USD/JPY being more sensitive than any other currency pair.

One aspect of figure 1 that stands out is the changing slope of the curves. The currency reaction tends to accelerate in the ‘corner regimes’ (0 and 4) when equities are either rallying or selling off heavily. If the currency reaction to equity regimes was uniform, the slope would be reasonably constant. In behavioural terms, the equity market has to cross some thresholds in order for it to matter for other assets. Bonds express similar, though less pronounced, behaviour.

To explore the time variation of FX reaction to equities we use rolling correlations, with the results presented in figure 2.

e9e84cf7-e20e-4570-af69-5d1f92c571eb

It is clear that currencies change their nature over time. For example, the euro went from being a risk currency around the time of the Greek financial crisis to a safe haven from 2016 onwards.

A set of variables that would determine the nature of the euro can probably be found within eurozone bond spreads, for example by looking at the spread between Italian and German bonds. The yen lost its safe-haven status only briefly in anticipation of aggressive monetary expansion proposed by the country’s prime minister in 2012. Overall, a variable correlation beyond standard statistical noise implies a different reaction to the same equity regimes.

### Modelling market regimes 

For market regimes to be usable they need to be reasonably persistent, and hence forecastable. Usually, markets don’t switch from being risk-on to risk-off in a single day, aside from in the aftermath of some central bank announcements – and even then, markets take time to absorb the news.

Moreover, regimes are not explicitly observable, but they can be deduced from the dynamics of other assets. We can also allow regimes to be determined by ‘fundamental variables’ such as inflation and growth.

A natural candidate to model non-observable regimes is the Hidden Markov Model (HMM), which is commonly used in speech recognition systems and is reasonably well established in finance. The idea behind HMM is shown in figures 3a and 3b.

3348bd62-e86e-48d6-b940-e97d09383da7

897e4ce8-1f80-4386-adc0-ad9f16f1f4a5

Figure 3a shows that the market is thought to evolve over time, with each unobservable state (grey circles) representing one of the market regimes. The possible regime transitions are described in figure 3b, whereby every grey circle from the previous image can be one of the four regimes illustrated here.

We can observe the market realisation (coral circles) for each time period. The mathematical problem is to deduce the content of the grey circles from the observation of the asset returns.

The HMM method with a fixed number of states maps naturally onto the human mental model. On the one hand, it presents a small number of regimes, making classification easy. On the other hand, the model is ‘fuzzy’ in the sense that it produces the probability estimate for each state rather than the exact forecast, so this confidence information can be used for a trading model.

### Analysing the results 

In this section we demonstrate a simple HMM model to identify market macro regimes. We take typical variables that are normally used to define a market regime, namely equity returns (S&P 500), equity volatility (Vix), the TED spread (the difference between three-month Libor and a three-month Treasury yield), the US 10-year Treasury yield change, the credit spread of the yield of corporate bonds rated BBB over US Treasury bond yields; and the returns on EUR/USD and JPY/USD.

This selection may not be perfect. For example, the TED spread will eventually lose its significance as part of the transition out of Libor. We select HMM with four hidden regimes and use a standard estimation procedure – the Baum and Welch algorithm – to estimate the parameters of the model and the most likely hidden regimes.

For each day, we identify one of the four regimes in which the market finds itself. It should be noted that while the model specifies four regimes it provides no details of their characteristics. Market behaviour in the regimes is estimated when the model is fitted to the data, so once the model is estimated, further analysis is required to understand what each market regime actually represents.

0bcb8564-6b2d-40ac-9907-001f75d942f1

The results of our analysis are the following:

- Regime 0 (red). This represents the market rallying with very low volatility. This would normally be identified as ‘risk-on’.

- Regime 1 (green). This represent the sharp market selloff with very high volatility. This would normally be called ‘risk-off’.

- Regime 2 (blue). This represents a mild selloff or the turning point. Volatility is still elevated and the market turns south.

- Regime 3 (gold). This represents the market recovery after the selloff. Volatility is still elevated, but the market has turned.

It should be noted that the description proposed here is very equity-centric and is not always accurate. The S&P 500 is not always going up in a red or gold regime and it is not always going down in a blue or green regime. From figure 4, it is clear that the recent market recovery represents a gold regime, which has now turned blue in the last few trading sessions.

The coloured maps do not necessarily provide action signals, however. For this, we need to know what to expect from each asset or asset class in each regime. This is shown in figure 5.

a7da9546-f177-414a-91c9-fea39fc8d877

Our specification of HMM assumes that asset returns come from a normal distribution in each regime. So only the mean, variances and correlations between assets differ between regimes. For ease of interpretation, we express all the returns on an annualised basis. The results are as follows:

- The S&P 500 is expected to increase at the annualised rate of 18% in red regimes and 9% in gold regimes. On the flip side, it is expected to fall at an annualised rate of 10% in blue regimes and 35% in green regimes.

- The Vix is dropping from a green regime to a red regime.

- The yen is expected to go up at an annualised rate of 14% in both a green and blue regime. This means it would be a good hedge for the S&P 500 in a blue regime but not in a green one.

- The euro is expected to rise the most in a blue regime. In fact, EUR/USD is rising – or at least not falling – in all regimes. This is a consequence of EUR/USD being up, on average, over the selected time period (we start the sample in 2002 when EUR/USD is around 0.9), as well as the small variation of EUR/USD across regimes – probably due to the absence of eurozone-specific risk factors in our model (see the correlation discussion above). This is something which can easily be corrected if the eurozone is the focus area.

Lastly, in order to complete the presentation of an HMM model, we need to describe the dynamics of the hidden regimes. Figure 6 presents the transition matrix for regimes and the long-term expected frequency of each regime.

4b96bcdf-7929-42bf-9c5e-2a9a738a7df3

Figure 6 (left panel) shows that the probability of staying in the same regime the following day ranges between 98.5% (regime 1) and 97% (regime 2). In other words, on a daily basis the regimes are quite persistent. This tallies well with the above-mentioned intuition that markets do not change from risk-on to risk-off and back on a daily basis. As the system is ergodic (meaning no state can disappear or become zero probability), it's interesting to see how frequently we should expect each state to occur over a long period. The right panel of figure 6 gives the answer. Regime 0 (market rally) is expected to occur slightly more than 40% of the time. Even the relatively extreme market regime (regime 1) identified in green occurs about 8% of the time. The simulation from this model would give a decent number of strong selloffs, and potentially quite a realistic assessment of risk.

A Markov chain is a machine learning procedure that estimates hidden regimes from observable variables such as asset returns. While classification of market regimes can be achieved using any clustering technique, such as the k-means method, HMM has an advantage in being a generative model. This means that once it is estimated, new data can easily be simulated.

The model summarises information from observed moves in different markets into state variables that are easy to communicate. As we estimate the model on a daily basis, the most likely use cases would be as follows:

- Execution. If we expect risky assets to have a negative trend in an estimated regime, we can buy them more slowly and sell them more quickly. Estimated regimes can be superimposed on tick data to estimate typical intraday dynamics in each regime. This is similar to what was described in two [previous](https://www.fx-markets.com/tech-and-data/7653826/wmr-fix-and-the-curse-of-predictability) [articles](https://www.fx-markets.com/comment/7550656/sell-at-dawn-and-go-away-but-come-back-after-lunch).

- Risk management. Because this is a generative model, this data-gathering procedure can be used to evaluate portfolio risk.

- Tactical asset allocation. This is the most common use of a regime-switching model in finance literature (see Ang and Timmermann, 2011) and comes from the relatively simple idea that an optimal portfolio can differ significantly in distinct regimes.

### References

- Andrew Ang, Allan Timmermann, 2011 Regime changes and financial markets Working Paper 17182, National Bureau of Economic Research, June

- Mark Kritzman, Sebastien Page, David Turkington, 2012 Regime Shifts: Implications for Dynamic Strategies Financial Analysts Journal, Vol. 68, No. 3

- James Hamilton, 1989 A New Approach to the Economic Analysis of Non-stationary Time Series and the Business Cycle Econometrica, 57, 357–384.

- Manmohan Kumar, Avinash Persaud, 2002 Pure contagion and investors’ shifting risk appetite: analytical issues and empirical evidence International Finance, Vol. 5, No. 3, 401–436.

- Miroslav Misina, 2003 What does the risk-appetite index measure? Bank of Canada Working Paper 2003–23, August.

