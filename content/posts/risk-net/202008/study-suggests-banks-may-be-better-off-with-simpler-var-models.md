---
title: 'Study suggests banks may be better off with simpler VAR models'
date: 2020-08-05T12:00:00+02:00
categories: ['risk-net']
tags: ['risk management', 'market risk', 'VAR']
datum: ['2020', '202008']
description: 'Non-parametric VAR models perform well in calm markets, but miss the mark in volatile periods'
---

{{< quote 4682b4 >}}_Non-parametric VAR models perform well in calm markets, but miss the mark in volatile periods_{{< /quote >}}

Non-parametric models that do not rely on normal distributions are [all the rage](https://www.risk.net/risk-management/7532751/to-model-the-real-world-quants-turn-to-synthetic-data) in finance these days – especially among quants experimenting with big data and machine learning techniques. But research published in the [Journal of Risk Model Validation](https://www.risk.net/journal-of-risk-model-validation/7553981/old-fashioned-parametric-models-are-still-the-best-a-comparison-of-value-at-risk-approaches-in-several-volatility-states) suggests banks might want to stick with old-fashioned parametric models for calculating value-at-risk.

University of Warsaw economists Mateusz Buczyński and Marcin Chlebus tested VAR calculations for equity indexes from six countries using a variety of parametric and non-parametric models. There are material differences in their reliability during calm and volatile periods – and in their cost of use.

A generalised autoregressive conditional heteroscedasticity ([Garch](https://www.risk.net/type/technical-paper/topics/generalized-autoregressive-conditional-heteroscedasticity-garch)) model using a standardised Student t distribution racked up the fewest VAR exceptions in the tests. [Garch](https://www.risk.net/type/technical-paper/topics/generalized-autoregressive-conditional-heteroscedasticity-garch) models are a widely used industry standard parametric model for calculating VAR and volatility in general.

Non-parametric conditional autoregressive VAR (CAViaR) models had the most breaches. An adaptive CAViaR model produced so many breaches – 10–12 at a 99% confidence level, and 20–24 at a 97.5% confidence level – that it “earned a red light” in one of the tests, the researchers write.

They also tested the cost of using the models by measuring the size of losses when VAR breaches occur, as well as the opportunity cost of using a more conservative model. On this measure, parametric models came out worse.

The Garch model using a standardised Student t distribution was the most costly, due to its conservativeness. The least costly model was a semi-parametric filtered historical simulation based on a skewed normal distribution. The CAViaR models performed poorly in terms of both cost and accuracy.

Despite the higher economic cost of using parametric models, the researchers argue banks may still prefer them because they generate fewer breaches, which in turn results in lower market risk capital multipliers. The VAR-based capital charge for market risk is calculated by multiplying a bank’s projected average daily loss estimate by three. But if a bank sees more than four VAR breaches over a rolling 250-day period, [the multiplier climbs](https://www.risk.net/our-take/6455876/last-orders-at-the-var) to a maximum of four for every additional breach.

The VAR models were tested against equity index data from six countries, including the UK, US and Japan. The researchers used four overlapping time periods covering different volatility regimes. Each test used four consecutive years of data to build the model, with the fifth year used to conduct an out-of-sample test.

The 2003–07 period had low volatility for both the building and testing phases. The data from 2004–09 had a calm building period followed by an out-of-sample test in a volatile year. The study also used data from 2007–2011 to test performance during the financial crisis, while the final set of models was built using volatile market data from 2008–2011, and then tested in the relative calm of 2012.

Overall, most models produced comparable numbers of VAR exceptions, and there was no real difference performance from one country to another. A few of the tests failed to produce statistically acceptable results, especially during the fourth data period, when a model built using volatile market data was tested against a calmer year.

However, the reliability of the models differed markedly depending on the environment in which they were tested.

“Many of the models that performed well in the calm periods are not able to estimate accurately in highly volatile periods,” the authors write.

“Parametric models are able to estimate forecasts that would give a low number of exceedances even in the case of high volatility. Semi-parametric or non-parametric models are able to forecast accurately – even more accurately than parametric models – when there are no uncommon events” – but they underperform during more volatile periods.

The authors suggest that combining the results of several models will produce more accurate VAR estimates. This comes with a high price tag, however – an ensemble model can be two to three times more expensive than the priciest component.

Banks may consider paying this higher cost for “near-perfect forecasting of volatile periods” and fewer VAR breaches. The authors note that the performance improvements with an ensemble model are larger in proportion than the cost increases, which could make them appealing to banks.

