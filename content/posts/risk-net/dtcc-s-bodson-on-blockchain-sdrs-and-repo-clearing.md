---
title: 'DTCC’s Bodson on blockchain, SDRs and repo clearing'
date: 2017-11-15T12:00:00+02:00
categories: ['risk-net']
tags: ['2017', '201711', 'risk management']
description: 'Risk30: swap data reporting will move to a distributed ledger platform in early 2018'
---

{{< quote 4682b4 >}}_Risk30: swap data reporting will move to a distributed ledger platform in early 2018_{{< /quote >}}

This is the eighth of 10 interviews marking Risk’s 30th anniversary. An introduction to the series – and links to the other articles – is available [here](https://www.risk.net/our-take/5353481/the-future-of-risk-in-10-interviews-volatility-liquidity-and-tech).

The world’s largest financial market utility is located in a nondescript office building in Jersey City, overlooking Manhattan from the banks of the Hudson River. Inside, a grand experiment is taking shape.

The Depository Trust and Clearing Corporation is developing a [distributed ledger technology](https://www.risk.net/topics/distributed-ledger-technology-dlt) platform to handle post-trade processing of over-the-counter derivatives. In the first instance, the technology will be used to re-engineer the DTCC’s Trade Information Warehouse (TIW), which maintains records on more than $11 trillion of cleared and bilateral credit derivatives transactions.

“We’re building it, and need to test it, but so far the development has gone very well,” says Mike Bodson, president and chief executive of DTCC. The plan is to launch a DLT ‘node’ to automatically update the TIW in early 2018. Market participants will then have the option of establishing their own nodes to connect to the DTCC’s distributed ledger. “You need to configure the systems you already have and convert them to make use of one database,” says Bodson. “It’s a journey. The transition won’t be overnight.”

It’s a transition the DTCC needed to make. As the sole central counterparty (CCP) for US cash equities and government bond trades, and the go-to swap data repository (SDR) for OTC derivatives, the company processes more than 100 million financial transactions a day – which represents only a third of its capacity. But the DTCC’s ageing systems were becoming the butt of jokes in financial industry circles. It has 55 million lines of code on its mainframe written in a programming language called Cobol, which is so old that developers familiar with it are hard to find. Bodson recognised a systems overhaul was long overdue.

“We’re at a confluence of multiple technologies coming to fruition at the same time, which presents some interesting opportunities for the future,” he says. “The future is out there and we’re not sure exactly what it is, but by the time it gets into sharp focus then it’s probably too late. We need to get ahead of the curve.”

DTCC’s strategy has been to work with established and start-up technology companies to develop new systems. The TIW project is being led by IBM, with Axoni providing the DLT infrastructure and smart contract applications, and R3 acting as an adviser.

The TIW is a vital piece of Wall Street’s plumbing. It grew out of the DTCC’s Deriv/Serv platform, launched in 2003 to address regulatory concerns about the backlog of confirmations in the credit default swap market. “The first push was to get confirmations of CDS transactions. Previously, there were month-old transactions, which participants would exchange money on and not know if it was the right amount,” says Bodson. “On the quarterly rolls, everybody would have tens, if not hundreds, of millions of dollars of unreconciled money, and you would spend the next three months bringing it back down to a small amount. Then, the same thing would happen all over a again.”

Within a couple of years of Deriv/Serv’s launch, around 80% of CDS trade volume was being confirmed electronically. The TIW was rolled out in 2006 as a central repository for outstanding CDS contracts and later enhanced to automatically net and settle quarterly payments.

The TIW proved its value when Lehman Brothers declared bankruptcy. Regulators were spooked by rumours that payouts on CDSs referencing Lehman could be as high as $400 billion. “People were looking at the gross notional values rather than thinking about the netted amount,” says Bodson. “We knew the actual number was closer to $6 billion.”

DTCC, which maintained records of 85% of all CDSs outstanding at the time, contacted the Securities and Exchange Commission (SEC) and the Federal Reserve to inform them of the market’s net exposure to Lehman contracts. “By publicising the number, it took a lot of the anxiety out of the system. People were going crazy wondering where all this money was going to come from,” says Bodson. “If it wasn’t for the TIW, all those swaps would have had bilateral payments back and forth. But because it was centralised, once the trigger event happened, everything was processed through the central system.”

### Instantaneous recordkeeping

The DLT project will bring the TIW into a digital age of instantaneous and error-free recordkeeping, where market participants can have access to a single version of the truth in real-time.

DLT is not the only new technology DTCC is experimenting with. The company has already moved some of its non-core systems to the cloud to cut costs and its mission-critical platforms may ultimately follow suit. “We are very interested in the cloud and we have non-critical systems in there right now, such as risk reporting, trade dissemination for SDRs and some human resources,” says Bodson. “We’re actively looking at moving some core systems to it, and not just for financial reasons – sometimes, when you need capacity, it’s very easy to get a server up and running so someone can do extra work on the spot.”

DTCC is also using artificial intelligence programs to monitor its systems for cyber attacks, and is taking inspiration from companies such as Netflix – which uses a program called Chaos Monkey to attack its own cloud system – to improve resiliency.

“Resiliency issues are interesting. We’re working with cloud vendors to get some transparency on that. Look at what Netflix is doing – it has a program crashing its live system to ensure it is immediately back up and running. This helps it improve its resiliency.”

But the conversation circles back to DLT, which DTCC hopes to deploy in its core clearing businesses in the not-too-distant future. DTCC has faced pressure from regulators to shore up its liquidity backstops, and the recent push for [buy-side clearing of repo trades](https://www.risk.net/derivatives/5322096/goldman-and-federated-first-to-clear-mmf-repo-trades), where notional amounts are exchanged at the front and back end of each trade, has upped the ante on that front.

### Repo clearing solution

Bodson believes DLT could offer a solution. The company is working with Digital Asset Holdings to develop a distributed ledger system for repo clearing, which would allow for same-day netting of overnight repo trades. That in turn might cut down the size of the capped contingent liquidity facility (CCLF) the DTCC requires from its members, which is currently set at $74 billion.

The high-stakes project has run into some hurdles, however. The first phase was completed on February 27 but the second phase, meant to be completed by June, is still pending. “We’re still playing with it,” says Bodson. “Digital Asset rolled out its software development kit, which is its code, and we’re looking at it and how we can work together. We want to see whether we can use it for more than just repo, so it’s potentially a longer-term project and on a bigger scale, so we’re not rushing into it just yet.”

The CCLF is designed to meet the Principles for financial market infrastructures developed by the Committee on Payments and Market Infrastructures and the International Organization of Securities Commissions in 2012. The calibration of the liquidity facility is currently being reviewed by the SEC and a final [decision](https://www.risk.net/derivatives/5333406/sec-delays-final-decision-on-dtcc-liquidity-facility) is set to be made on November 15.

Some smaller members of the DTCC’s Fixed Income Clearing Corporation have [opposed](https://www.risk.net/derivatives/5292066/dtccs-74-billion-liquidity-charge-riles-members)the CCLF proposal and threatened to quit the CCP if it is implemented. Bodson defends the proposal. “Everyone has a different operating model, and we’re sensitive to the concerns raised by the smaller non-bank broker-dealers,” he says. “At the same time, how do you portion out liquidity requirements? To simply give someone a pass because it’s more expensive for you as a result of your business model, that is also unfair on everyone else who is on the other side of the trade. It’s a price to pay to gain access.”

Bodson reiterates that new innovations such as DLT can lower the price of entry. The irony of course is that the original developers of DLTs such as the blockchain that underpins bitcoin wanted to establish a shared transaction record and do away with gatekeepers such as the DTCC. Bodson argues that idea has its own flaws.

“First of all, that’s incredibly inefficient – keeping every trade done on Wall Street on every bank’s systems is not a good use of power. Second, do you trust the information shared by your competitors?” he asks. “People have rethought this now and maybe realised it won’t be so distributed after all – maybe it will be distributed in the sense some information will be, but not all.”

### Responsibility

A distributed system that allows everyone access to the same information also raises questions about who is ultimately responsible when problems occur, or when there are disagreements about the finer details of a transaction, or the information that goes into a smart contract. As a result, Bodson says a central body such as the DTCC will still have a role to play in the age of DLT.

“Someone needs to be the master of the ecosystem – whether that is us or someone else,” he says. “It will be a central body of some sort that has to play gatekeeper.”

This is a role the DTCC has been playing since it was formed as the Depository Trust Company in 1973 to centralise the process of exchanging financial paper. Maintaining transactions records on a central mainframe and netting offsetting payments delivered major efficiency gains, but it was not without risk. “I’m sure someone would have said, ‘you’re nuts, what happens if the power goes out, or if the tape gets lost?’ It was a no-brainer looking back on it, but at the time it was a pretty bold step.”

The same may be said about the move to DLT in a few decades time.

