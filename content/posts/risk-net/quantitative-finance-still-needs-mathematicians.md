---
title: 'Quantitative finance still needs mathematicians'
date: 2017-11-17T12:00:00+02:00
categories: ['risk-net']
tags: ['2017', '201711', 'risk management']
description: 'Quants develop model that fixes a longstanding problem with pricing American options'
---

> _Quants develop model that fixes a longstanding problem with pricing American options_

Calibration of models to American options has never been an easy task, mainly because, unlike European options, the buyer can choose to exercise the option early.

This means the value of the option is dependent on a number of factors that evolve over time, such as volatility, whether the option gets exercised at any given time, and dividend payments – creating a number of possible paths the option value could take.

An easy shortcut many dealers follow is to assume American options are the same as European options and approximate the prices.

Another typical – and more rigorous – solution is solving of partial differential equations (PDE). However, dealers usually would have to price thousands of options in any given portfolio, so this could easily become a time-consuming task, given every option would need to be numerically revalued as spot, volatility and other factors evolve.

“People have been trying to parallelise that problem, use GPUs and try and solve many American options at once,” says one quant at a large US bank “It’s definitely something everyone would like to do better and faster. One problem is that everyone is making a trade-off. You might choose faster calibration or you might choose a more accurate solution.”

In this month’s technical, [Local volatilityfrom American options](https://www.risk.net/derivatives/5359156/local-volatility-from-american-options), Stefano De Marco, an assistant professor in applied mathematics at Ecole Polytechnique in Paris, and Pierre Henry-Labordère, a member of the global markets quantitative research team at Societe Generale, also in Paris, propose a technique to calibrating the commonly used local volatility function to American option prices, without the use of cumbersome numerical techniques.

Option pricing models need to be calibrated to real market prices. This can be done using the local volatility function.

The quants achieve a mapping between American option prices and this local volatilityfunction by proposing their own version of something called an early premium formula, which parametrically represents the value of the American option as the value of a European option plus a correction or a premium for the early exercise option.

The quants use this to come up with an explicit formula that approximates the solution of the PDE instead of trying to solve the PDE numerically. Because there is an explicit formula, the local volatility model could be calibrated almost in real-time.

Others familiar with the technique agree there are clear benefits in terms of speed.

“It’s a closed form expression way to price American options using an approximation, which is better than any other approximation that is available already, [and opens up] this possibility of improving the trade-off between speed and accuracy,” says the quant at the US bank. “And almost all listed options for almost all stocks are American-style, so… you need to be doing this calibration and this could make that process faster and more efficient.”

The quant’s team is currently testing out the method for potential use.

The authors of the paper argue their technique can also be applied easily, through a few simple additions to existing pricing codes within a bank’s system. “They already have codes and analytics for calibrating local volatility to European options, what they will have to write are just a few lines in their codes… to compute this correction, and then the calibration system they have which is based on minimising the difference between market prices and model prices will just work the same,” says De Marco.

### Heat kernel expansion

One thing that allows the quants to come up with the approximation is the use of a technique called the heat kernel expansion used in physics.

Market participants might argue the days of applying complicated mathematics and physics concepts to quantitative finance are long gone, and it’s time to usher in a new era of [fintech and quant programmers](https://www.risk.net/our-take/5293171/analyse-this-the-future-for-quants). They are probably not wrong.

Henry-Labordère and De Marco’s paper might have taken the old-school approach of solving a practical problem using advanced mathematics, but as with any discipline, diversity in the way people approach a problem is what helps solve the particularly complex ones.

For that reason, the industry needs traditional mathematicians as much as they need programmers and data scientists.

