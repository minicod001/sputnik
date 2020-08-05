---
title: 'The unintended impact of collateral on financial stability'
date: 2020-07-31T12:00:00+02:00
categories: ['risk-net']
tags: ['2020', '202007', 'derivatives', 'colateral', 'initial margin', 'contagion risk']
description: 'Initial margin requirements for OTC derivatives can increase risk of contagion, writes economist'
---

{{< quote 4682b4 >}}_Initial margin requirements for OTC derivatives can increase risk of contagion, writes economist_{{< /quote >}}

To mitigate financial stability risks, policy-makers and regulators should be able to measure and analyse contagion – that is, the spread of losses and defaults through the financial system. I have been working on this problem with Paul Glasserman at Columbia Business School and Peyton Young at the London School of Economics. We recently [developed a network model](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3569781) to study the impact of margin requirements and stay rules in bankruptcy and resolution regimes in over-the-counter derivatives on contagion. In this article, I will discuss some of our results on the impact of collateral on contagion. These show that collateral in the form of initial margin may increase risks to financial stability.

To avoid a build-up of large exposures, OTC derivatives are subjected to strict margin requirements. Most standardised OTC derivatives contracts now trade through central counterparties (CCPs), which require clearing member participants to post collateral in the form of initial margin (IM). The part of the market that continues to trade bilaterally is now also subject to IM requirements.

Counterparties to centrally cleared and bilateral trades must also exchange variation margin (VM), reflecting daily mark-to-market changes of a derivatives portfolio.

IM provides a layer of counterparty credit risk protection beyond VM. It is calculated based on extreme potential future portfolio value changes to cover one party’s tail exposure to the other upon its default. In centrally cleared trades, CCPs receive IM from their members, but do not post IM to them.

The amount of margin collected is significant. According to the International Swaps and Derivatives Association, the total amount of IM posted against interest rate and credit default swaps reached $342.8 billion at the end of the first quarter of 2020 – an increase of more than 25% compared with the last quarter of 2019 due to the increased market volatility following the Covid-19 pandemic.

While IM mitigates counterparty credit risk, it can lead to an ex-post inefficient allocation of a firm’s assets. A firm may find itself unable to make a current payment obligation on one contract while having posted collateral to protect extreme potential future payments on other contracts. This is one of the main shortcomings of initial margin, and explains why collecting more margin can in some cases increase risks to financial stability.

Suppose that contagion is measured by the number of defaults. Figure 1 presents a stylised example of a network model in the financial system.

The nodes represent firms in the network. The arrows indicate the directions of nominal and current payment obligations. Not all payment obligations involve derivatives. The labels on the arrows indicate the payment amounts due.

Assume the total cash or liquid assets initially available to firm A is 4 and that the other firms initially have zero cash or liquid assets.

The label in the square bracket shows IM posted to derivatives counterparties. In this stylised example, the IM amount exceeds firm A’s payment obligations at a given point in time. In OTC derivatives markets, IM is often calculated using value-at-risk type models that capture extreme portfolio value changes over a given time horizon, called the margin period of risk. As a result, IM levels may exceed nominal payment obligations between firms at different points in time, depending on the composition of the derivatives portfolios and netting rules and agreements between counterparties.

I consider three stylised scenarios and in part investigate the trade-off between committing collateral to specific counterparties versus pooling collateral and holding additional cash. This trade-off is analogous to the comparison between collateral requirements and capital requirements.

In the first scenario, all liquid assets available to A are posted as IM to derivatives counterparty C1 [mAC1 = 4]. B1 is either a non-derivatives counterparty or a derivatives counterparty to which A is not required to post IM (for instance, because the size of A’s derivatives portfolio with B1 is below regulatory thresholds for posting IM).

In the second scenario, A does not post any IM. Instead, it pools its available collateral and holds it as a cash-like buffer CA on its balance sheet [CA = 4].

In the third scenario, all of A’s eligible assets are committed as IM to B1 [mAB1 = 4], which has a similar payment obligation to another firm, B2. A does not post IM to C1 in this scenario.

FIG

In the first and third scenarios, A defaults as it does not have sufficient liquid assets to meet its payment obligations to B1 and C1. In these two scenarios, this spreads more defaults in the network. The collateralised counterparty seizes half of A’s IM to cover missed payments. The uncollateralised counterparty defaults. There are three defaults in the first scenario [D = {A, B1, B2}] and to two defaults in the third scenario, [D = {A, C1}].

In the second scenario, where collateral is pooled, rather than being committed to individual counterparties, there are no defaults.

In the above example, IM exceeds current payment obligations. This might be often the case in OTC derivatives markets, since IM captures extreme potential future exposures. Indeed, the [research paper](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3569781) shows that the existence of excess collateral can increase risks to financial stability. By definition and design, IM can lead to a build-up of excess collateral in the financial system.

In the absence of excess collateral, the result can change. For instance, if we change the available assets of A from 4 units of cash to 2, and IM from 4 to 2 in the first and third scenarios, it can be seen that pooling collateral – ie, the second scenario – will produce the maximum number of defaults, [D = {A, B1, B2, C1}]. The first and second scenarios will produce the same number of defaults when IM is equivalent to A’s current payment obligations.

In the absence of excess collateral, depending on how collateral is allocated to counterparties, committing collateral to counterparties – as opposed to pooling collateral – can increase or decrease contagion.

Regulators and policy-makers tend to believe that, in comparison with capital requirements, margin requirements provide better protection against counterparty credit risk.

In their [final policy framework](https://www.bis.org/bcbs/publ/d317.pdf) on margin requirements for non-cleared derivatives, the Basel Committee on Banking Supervision and the International Organization of Securities Commissions write: “Margin can be seen as offering enhanced protection [compared with capital] against counterparty credit risk, provided that it is effectively implemented. In order for margin to act as an effective risk mitigant, it must be: (i) accessible when needed; and (ii) provided in a form that can be liquidated rapidly and at a predictable price, even in a time of financial stress.”

The results of our research show that even where it is accessible and liquid, collateral in the form of initial margin is not guaranteed to improve financial stability. In fact, committing collateral to counterparties in excess of current payment obligations can increase risks to financial stability.

Samim Ghamami is the senior economist and managing director at the Financial Services Forum, an adjunct professor of finance at New York University, a senior researcher at UC Berkeley, and an adjunct professor of economics at Columbia University. He also serves on the advisory board of the Mathematics in Finance Program at the NYU’s Courant Institute.

An article on the financial stability implications of bankruptcy stay rules for OTC derivatives will be published shortly by Risk.net.

