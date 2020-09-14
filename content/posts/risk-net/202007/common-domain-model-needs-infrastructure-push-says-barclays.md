---
title: 'Common domain model needs infrastructure push, says Barclays'
date: 2020-07-14T12:00:00+02:00
categories: ['risk-net']
tags: ['2020', '202007', 'derivatives', 'ISDA', 'CDM']
description: 'Bank wants market infrastructures to drive adoption of Isda CDM'
---

{{< quote 4682b4 >}}_Bank wants market infrastructures to drive adoption of Isda CDM_{{< /quote >}}

Exchanges and clearing houses should take a lead role in delivering the International Swaps and Derivatives Association’s data standardisation project to the market, according to a new [paper](https://arxiv.org/pdf/2007.06507.pdf) from Barclays.

Isda’s common domain model (CDM) has seen [patchy take-up](https://www.risk.net/risk-management/6512226/patchy-response-to-isdas-back-office-of-the-future) among banks and financial market infrastructures (FMI) since it was conceived in 2017. Some banks are said to be having trouble making a case internally for a project that promises to produce savings of up to $3 billion a year on post-trade processes, but generates no revenue.

“Significant change can happen faster if an FMI helps drive adoption,” says Lee Braine, director of research and engineering at Barclays. “Early front-burner use cases are more likely to include a new product integration or service offered by an FMI. So the business case challenge is not to persuade all the broker-dealers to migrate off existing functioning internal systems. It is merely to add new services, and that’s an easier sell.”

Many banks and clearing houses have their own customised platforms for derivatives, which are unable to communicate with external systems. Isda hopes to eliminate those costs and inefficiencies with the CDM. In the paper, Barclays highlights eight options the industry could consider to tackle inconsistent data and processes, as well as duplicated data, in the post-trade lifecycle.

All the options include the notion of an authoritative data store (ADS), which houses the common processes defined by the CDM and acts as a single logical reference point. FMIs would play a key role in managing ADSs, with individual banks also free to construct internal ADSs for their businesses. More advanced scenarios envisage a role for distributed ledger technology (DLT), which could unlock the biggest payoffs from CDM adoption.

Braine says all the options in the paper should help the industry lessen the need for trade reconciliations. But because decommissioning and replatforming legacy systems within banks might take several years, the authors hope FMIs will introduce the CDM into the trade lifecycle ecosystem earlier, as new products and services come online.

Ian Sloyan, Isda’s head of market infrastructure and technology, says the group is working with several clearing and settlement houses to integrate the CDM with their different messaging standards and formats. These include the Australian Stock Exchange (ASX), Chicago Mercantile Exchange, Depository Trust & Clearing Corporation (DTCC) and LCH. “Those discussions are primarily focused on how a trade goes to clearing, but that’s just one specific example,” he says.

Three FMIs say they are aiming to facilitate the CDM.

Richard Barton, head of product management at AcadiaSoft, says that, through an adaptor, the margin utility’s Agreement Manager service will support [Isda Create](https://www.isda.org/2019/01/29/acadiasoft-partners-with-isda-to-streamline-integration-with-isda-create/) based on the CDM format later this year. [Isda Create](https://www.isda.org/2019/01/29/acadiasoft-partners-with-isda-to-streamline-integration-with-isda-create/) is used for negotiating and executing Isda documentation for non-cleared derivatives, while Agreement Manager stores the legal and operational collateral agreement information.

Val Wotton, head of product development and strategy, repository and derivatives services at the DTCC, which is looking to leverage DLT through its [Trade Information Warehouse](https://www.waterstechnology.com/technology/4527161/dtcc-develops-tool-to-support-dlt-governance), says his firm “would absolutely consider how the CDM could be leveraged.”

Allan McGregor, senior rates manager at the ASX, which [plans to use](https://www.waterstechnology.com/technology/4830891/asx-on-track-for-chess-replacement-testing) DLT in equities clearing and settlement, also pledges his support, but adds: “It’s early stages, and co-ordinated industry change is challenging in the current environment.”

Those industry challenges are substantial. Despite claims that the CDM could deliver real cost savings in post-trade processing – a 2018 [paper](https://www2.deloitte.com/content/dam/Deloitte/us/Documents/financial-services/future-of-post-trade.pdf) by Deloitte found the CDM and emerging technologies such as DLT could reap cost efficiencies of up to 80% – some banks are reluctant to commit to paying for a CDM.

One bank’s head of digital says he has been asking internally about how much it might cost to put the CDM in place at a bank like his that currently has inconsistent data models. “I’m slowly getting clarity, and I don’t know as yet,” he says. “It will be significant, especially for the entirety of the firm. You’re talking about all the unstructured data, structured data, corporate data and front-office data.”

A senior executive at another investment bank talks of the “vast amount of money” it would take to reconfigure post-trade plumbing, and argues savings might not be felt for decades. He says: “The cost of moving off your existing expensive legacy to this new stuff, the business case is like 20 years’ payback … you can’t quite justify the economics.”

Others, meanwhile, argue that for CDM to become truly embedded in bank systems it must start further upstream, in front-office platforms.

“Surely the key data sources are front-office and primary trading systems, supported by additional sources to enrich data,” says Julian Eyre, managing director at advisory firm Eyre. “My view is that, tactically, the data needs to be transformed to CDM as it leaves these legacy primary trading systems, and then the data lives on through the trade lifecycle in the correct, standards-based process model.”

He says existing trading system vendors could be disrupted by such an outcome. New vendors might emerge who are “CDM-native, where the data originates from front office in CDM format, with standardised lifecycle events. These data flow through the post-trade infrastructure, both ‘in bank’ and ‘out of bank’. Brokers dealer are part of the post-trade framework and would then be native consumers of CDM events on a real­-time API basis.”

### Reconciliation needed

In its paper, Barclays emphasises that if banks find it tricky to embrace CDM fully, they could instead access the model at an FMI. Reconciliation may still be required, however, between the broker-dealer’s internal data model (IDM) and a CDM business events log. Still, Braine contends, this “minimal integration” would permit some processing that would otherwise have been implemented within every broker-dealer to instead be done just once at the FMI – thereby increasing consistency and potentially reducing cost.

Barclays will scope out two prototypes from the paper using an interest rate swap, to assess the technical lift required by the parties involved. That will include how banks might construct data stores, incorporate translation layers, operate an ADS and transform CDM events into an IDM.

Braine and Aishwarya Nair, lead developer at Barclays, are heading the research and development for the technical solutions.

The study will simulate payment flows between an FMI and a broker-dealer and examine how data will be synchronised and how transmission errors might be dealt with. The bank will showcase its efforts in Q4.

Sticking to its guns, however, the scenarios Barclays will develop are those that it continues to view as most viable for broker-dealers to maximise their integration with the CDM.

In a first, centralised, scenario, Barclays posits a broker-dealer fully integrating with a central ADS and adopting the CDM internally. Its second scenario mirrors the first, but in a decentralised setting using DLT; hosting a node, broker-dealers would integrate with a common ADS supplied by an FMI, as well as adopt the CDM internally.

“The question – where the answer isn’t obvious yet – is what are the differences in non-functional aspects such as synchronisation latency, recoverability and ‘restoreability’?” says Braine. “It is worth bearing in mind that a centralised model would probably involve each broker-dealer building its own custom component to receive and store CDM business events, whereas a decentralised model could allow each broker-dealer to install a common component to perform that functionality as part of an overall DLT solution.”

However, Braine recognises potential challenges to getting on board with new technology. “If the solution involved broker-dealers merely consuming data via interfaces, then it would typically be easier to get adoption,” he says. “However, if you need to install DLT components behind banks’ firewalls, then there is additional work to get those components approved, supported and embedded.”

### Java hit

Barclays has begun scoping out the centralised technical solution using Java, while the decentralised model would also employ Java but on R3’s Corda, an open-sourced DLT backed by a consortium of banks. As Corda uses Java Virtual Machine, coding in Java was the practical option for both solutions, says Braine, because it is easier to evaluate and compare technical performance and network topologies.

It is not the first time Barclays has [made the case](https://www.waterstechnology.com/data-management/4618781/barclays-the-future-of-post-trade-is-a-common-utility-platform) for leveraging FMIs to drive the CDM, and Braine says he hopes that over time, it could lead to the development of cross-asset class repositories, enabled by CDM.

To date, Isda’s CDM provides data standards for interest rate and credit derivatives. Its most recent version, 2.0, was published in March 2019. Isda hopes to expand coverage to all wholesale financial products and asset classes, including bonds, repo and securities finance, and also argues the CDM would facilitate better [regulatory reporting](https://www.risk.net/derivatives/6775411/isda-backs-regulatory-push-on-derivatives-data-project).

But in making the first push to develop real-world examples of how exactly the CDM might enjoy widespread industry adoption, Barclays insists FMIs must carry the project forward.

“For emerging standards such as CDM, it will undoubtedly help to have FMI projects that can be showcased as potential real-life solutions for the industry. Once you have that, broker-dealers can then start constructing business cases, evaluating adoption scenarios, planning timelines, and so on,” Braine says.

That could be considered a “stealth method”, where a CDM option comes for free as part of a new FMI service, believes Braine, and to make it more appetising the FMI could provide interfacing options ranging from traditional Financial products Markup Language messages to CDM business events.

