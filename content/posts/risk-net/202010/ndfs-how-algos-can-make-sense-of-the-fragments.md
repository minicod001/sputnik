---
title: 'NDFs: how algos can make sense of the fragments'
date: 2020-10-19T12:00:00+02:00
categories: ['risk-net']
tags: ['FX']
datum: ['2020', '202010']
description: 'The scattering of liquidity in non-deliverable forwards calls for new execution tools, argue HSBC execs'
---

{{< quote steelblue >}}_The scattering of liquidity in non-deliverable forwards calls for new execution tools, argue HSBC execs_{{< /quote >}}

The market for non-deliverable forwards is becoming more complex and fragmented, much like spot FX. Trading activity in NDFs is now split across multiple venues, leading participants to seek new ways to optimise execution.

Less than a year ago, a single exchange provided firm prices both on and off swap execution facilities. The liquidity was easy to navigate, with credit being the sole differentiator between dealers. Today, there are multiple pools of liquidity offering a combination of both firm and last-look prices.

This shift has led large dealers to develop complex algorithmic strategies to optimise execution and better manage risk. In illiquid products such as NDFs, algorithmic execution helps minimise transaction costs over the long run by capturing a larger spread on passive orders than in more liquid products such as G10 spot. With interbank top-of-book spreads on NDFs in excess of 2 basis points on average, there is significant opportunity for spread capture compared with G10 spot, where spreads are under 1bp.

A critical component of execution algorithms is the depth and quality of the liquidity pools. To minimise price slippage, an algorithmic strategy needs unique and uncorrelated – or ‘orthogonal’ – liquidity. When liquidity is not curated for orthogonality, end-users are exposed to wider aggregated spreads, high market impact, increased liquidity mirage and low fill rates.

Following the peak of the coronavirus pandemic in March 2020, interbank spreads and volatility in NDFs increased by more than 200% (see figure 1). Volatility and spreads have since returned to normal, but the NDF market continues to fragment and liquidity dwindle. This has led to greater demand for algorithms from clients who are seeking to minimise their market footprint, capture spread and optimise execution.

{{< embedded "917275a7-82da-40df-bc93-92b0a092def3" >}}

Depending on the risk appetite, clients can deploy a range of algorithmic strategies. An ‘Implementation Shortfall’ strategy allows clients to minimise slippage from the arrival price for their order while managing volatility risk. Alternatively, a ‘Liquidity Seeking’ algorithm deploys a more passive strategy, aiming to maximise spread capture while adapting to market conditions and minimising market impact. This strategy is for clients who are looking to take increased execution risk with the goal of using spread capture as a primary means of outperforming the arrival price.

William Greene is head of quantitative FX trading, Farzana Nanji is head of eFX sales for Europe, the Middle East and Africa, and Alexander Barzykin is a quantitative analyst for FX e-risk, all at HSBC.

{{< quote grey >}}
### About this data
Data is provided by HSBC via NDFlex, the bank’s NDF execution algorithmic suite, launched in June 2020.
{{< /quote >}}

