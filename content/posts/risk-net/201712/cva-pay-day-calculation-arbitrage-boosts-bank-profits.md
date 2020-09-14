---
title: 'CVA pay day: calculation arbitrage boosts bank profits'
date: 2017-12-08T12:00:00+02:00
categories: ['risk-net']
tags: ['risk management']
datum: ['2017', '201712']
description: 'Lack of convergence allows some banks to benefit from an arbitrage between booking and pricing the adjustment'
---

{{< quote 4682b4 >}}_Lack of convergence allows some banks to benefit from an arbitrage between booking and pricing the adjustment_{{< /quote >}}

Banks have been adjusting derivatives prices to reflect counterparty credit risk for well over a decade, so it would be reasonable to assume that by now there should be broad agreement on the methodology. But dealers and auditors say vague accounting guidelines and inconsistent regulatory treatment have caused approaches to calculating credit valuation adjustment to vary significantly across banks and regions, creating a lack of alignment between what dealers price and what they account for.

While differences in methodology between the two are common, at least one large dealer has been systematically pricing a much higher CVA to the client and booking using the lower figure, and keeping the difference as a profit.

“Banks have been willingly ignoring this kind of risk so they could continue to be extremely aggressive on their CVA computation and pricing, and this way they make as much money as possible – what is even worse, some banks are paying a chunk of this CVA back to sales,” says one former trader at a European bank that took this approach.

Market observers say there is little reason to take this course other than to boost bank profits.

Start-ups have begun to spring up, looking to gather more detailed information on banks’ approaches to CVA, to allow clients to reverse-engineer the charges, but some corporates say this is a perfect example of the importance of shopping around.

“If a corporate is stupid enough not to put their deals out for competition then they can expect to be ripped off,” says one London-based corporate treasurer.

These differences in CVA pricing are driven by the loss-given default metric, which measures what a bank would expect to lose if the counterparty defaults and is one of the two key inputs to the CVA calculation.

There are two ways of looking at LGD: through a market-implied lens, which is calculated from the credit default swap (CDS) spread of a counterparty; and through a historical lens, which is based on actual recovery rates from default auctions.

The market standard is to use an LGD implied from CDS prices. This is partly due to International Financial Reporting Standard (IFRS) 13, requiring banks to report their derivatives at fair value, which will typically include a CVA charge. The standard asks banks to calculate CVA using market-implied data, such as CDS spreads, to the extent that they are available and relevant.

Using this method, banks assume a blanket LGD of 60% – put another way, if the counterparty defaults then the bank expects to only recover 40% of the amount owed.

Historical LGDs tend to be much lower, however. For example, Societe Generale’s Pillar III report, released in March, shows the “actual LGD excluding safety margin” for large corporates was 25%, and 36% for small- to medium-sized corporates.

This means banks pricing CVA using market-implied LGDs will tend to produce higher loss assumptions than those adopting the historical approach, which translates into higher charges for clients.

### Ideal scenario

In an ideal world, the CVA priced into a trade should match the adjustment accounted for – something both auditors and regulators have been pushing for over many years.

But regulators also require capital to be held against CVA and calculate it slightly differently than accountants. For instance, a recent regulatory technical standard issued by the European Banking Authority (EBA) proposes allowing banks to adjust their LGD used for capital calculation on the basis of [seniority of the derivatives netting set](https://www.risk.net/derivatives/5307581/banks-say-europes-cva-proxy-spread-plans-lack-flexibility).

If a derivatives asset is ranked higher in the insolvency waterfall than the senior unsecured debt waterfall, for example, this means holders of derivatives claims will be paid before bondholders. This means banks can adjust the LGD lower than the market standard of 60%.

“In some cases – in fact with corporates – we have swaps that are completely senior, in the sense if there is a waterfall in the default of the counterparty we will be paid first before any debt, so that can actually make quite a bit of a difference in the pricing,” says Ian Harris, head of CVA trading at Credit Suisse in London.

“We can actually write that into the docs if we are either ahead or behind, so we can point to that and say ‘well, we shouldn’t be marking our recovery so low or so high’,” he adds.

The CVA trader at a second European bank says the LGDs could go as low as 10% in some cases.

“If you take the example of project financing, it could be very large because the more senior you are, the lesser LGD will be… so if you are very senior, the first to get the recovery, then the LGD could go as low as 10% or 15%,” says the trader. “If you are not very senior in the ranking, so you come second or third, then perhaps instead of 60% it is going to go to 50% or 40% – it really depends on the project you are working on.”

### Historical data

But Europe’s Capital Requirements Regulation (CRR) also allows banks to adjust their LGDs to reflect historical observations in capital calculations. For instance, it could take into account the average recovery rate seen in credit event auctions after the default of certain types of counterparty.

“We have experienced a few defaults, so we have gained some experience on what the LGD is. All banks are in the same situation. All banks have done backtesting on the true default they have experienced over time and the LGDs are lower than 60% on average; they are closer to one-third or 40%, but certainly not 60%,” says the head of the CVA desk at a third European bank.

In most cases, European dealers use a similar methodology for regulatory capital and accounting CVA calculations – as the teams are different, their objectives differ. This means some banks apply the historical CVA approach designed for regulatory capital to accounting calculations. The CVA head at the third European dealer confirms they take this approach.

A senior auditor at a big-four consulting firm says auditors may frown on the use of historical data for accounting purposes.

“They [dealers] rely on the CRR because they say that is an approved model, so we can use it for accounting. That is not necessarily consistent literally with IFRS,” he says. “The regulation drives the business. It is not a very clever idea; people are getting confused because the regulation and IFRS policies are different for each market participant.”

However, he says there is currently no clear view on what the right approach is.

“You can say the best estimate will be historical data because it is much more accurate than market data or you can go the other way, saying the market is always right and to hell with your historical data. And that is to some extent circular and nobody really has a clear view on this,” he says.

Some banks though are known to deliberately price using the higher market-implied LGD and book internally using the lower historical LGD. At least one European bank is known to systematically take this approach, with the difference paid into the bonus pool, according to the former trader at the bank.

“[They] convinced their auditors to use [the historical approach],” says the former trader. “They were sure comparable banks were doing comparable methods, which gave them some kind of comfort, but I don’t think it makes much sense and definitely is not by the book if you read the IFRS.”

Jon Gregory, a London-based independent derivatives valuation adjustment (XVA) expert, says the only thing this approach does is to artificially inflate CVA to boost profits.

“If you think LGD is 20% and the EBA says it’s perfectly acceptable to define it as being 20%, why not price at 20%? I don’t see any reason why you would price at 60% in that situation. Of course, you could say you want to make more money, but if you want to make more money you should charge more. You don’t need to artificially price with a 60% LGD,” says Gregory.

Supporters of the approach say pricing is a purely business-driven decision and banks can make whatever assumptions they want. The trader at the second European bank says they price using market-implied because that is what the true risk is based on. “Pricing, as far as I am concerned, is always there to reflect the true risk you are putting in your books,” he adds.

The trader at the second European bank also argues clients should not be too badly affected, because the CVA component of the price is small [relative to the cost of capital](https://www.risk.net/derivatives/2449096/accounting-kva-under-ifrs-13). “This is really not impacting the price of the client. The main driver of the price is the capital charge,” the trader says.

### Question of influence

Corporates never really know what a bank’s internal CVA price is, but say they would not be surprised if this activity was going on. The London-based corporate treasurer says there is an incentive to overcharge their clients because they generally pay CVA up front, with profits recognised immediately.

“If a bank has an internal CVA that is lower than the market, it is expected they would still charge the market price or just below, as this would be one of the main drivers to win the trade. And then, internally, they would try to reserve as little as possible and put as much as possible as profit,” says the London-based corporate treasurer.

“Since I believe most banks still allow, for bonus purposes, the profit over the entire life of the trade on day one, then the traders themselves would be heavily incentivised to try to push middle office to reserve as little as possible,” he adds.

Because of the range of CVA being charged, hedging advisers are increasingly asking for detailed information on how banks calculate their CVA to try to reverse-engineer what banks will charge. As a result, start-ups that advise firms on how XVAs are calculated are on the rise, say dealers.

“There are a lot of start-ups or small institutions trying to sell a service [this year] to the corporates where they are advising them on how to compute all these XVA adjustments,” says the CVA trader at the second European bank.

“We have had large corporates asking us about how we price [and] what assumptions we are taking. They are quite specific, asking about discounting or what kind of curve we are using, what kind of proxies, probability of default inputs and LGDs [we are using],” he adds.

But even then, the theory does not always marry up with the reality: “Unfortunately, prices are still all over the place. We aim to approximate where banks will come back at, but we are often surprised with the answers we get,” says François Jarrosson, a director in the hedging and derivatives team at Rothschild in London.

### CVA’s shaky foundation

While banks generally price the credit valuation adjustment (CVA) of a swap based on credit default swaps (CDS), the lack of data for illiquid names has come under fire from some academics who describe the method as more art than science.

“You need to make guesses about the default probabilities of all the counterparties, the correlation of the defaults of the counterparties and the recovery rates. It’s anybody’s guess really. We don’t really know these parameters,” says Rama Cont, chair in mathematical finance at Imperial College London. “Financial institutions use these parameters in their calculations as if they are precise estimates – they are not.”

Cont argues it is difficult to backtest the numbers produced by these models.

“You can backtest a lot of things, but you cannot backtest CVA. There is no market validation because it is basically an estimate of expected loss upon default. But if you are calculating it today, it’s because the counterparty has not defaulted yet,” he says.

“Even for firms that defaulted, you cannot go back and ask ‘was my CVA estimate for Lehman correct?’ – that’s the problem. If something cannot be backtested, even with hindsight, how do you validate that?” adds Cont.

Others agree that validation of the inputs is tricky, because in order to do that the counterparty must default, which rarely happens.

“For me, CVA is the least real [among derivatives adjustments], especially for investment-grade credits, because it only materialises in a default,” says Jon Gregory, an independent derivatives valuation adjustment expert based in London. “The funding valuation adjustment and capital valuation adjustment are not like that. Every day in the bank I get charged funding, I get charged capital – I know the cost of it.”

As an alternative to passing the cost of counterparty credit risk on to clients in the form of a CVA, Cont suggests managing it using buffers and limits, as a central counterparty (CCP) would.

“There’s a difference between measuring risk and managing it. CVA is measuring risk – you just do your calculations of expected loss with lots of uncontrollable assumptions. Let’s even assume they are correct – so what? Now you calculate this up front, you charge that,” says Imperial’s Cont.

“Are you managing default risk? No, not really. You are just measuring it and then you put some money into the account, but it’s perhaps 1% of what you might really lose. Risk management starts with identifying risk scenarios you are exposed to, then provisioning enough resources to cover actual losses with a high confidence level, not just expected loss,” says Cont.

This strategy was implemented successfully by CCPs even during the crisis, Cont points out.

“Look at LCH. When Lehman defaulted, it was a clearing member of LCH. It had to liquidate $60 billion of swaps, but didn’t lose a dollar. They had managed it well. They had computed margin requirements and in a way that covered all the losses. Luckily for them, they were not provisioning for Lehman’s default using a CVA approach.”

