---
title: 'BNY Mellon, Deutsche Bank to extend FX API for Indonesia and India'
date: 2020-08-13T12:00:00+02:00
categories: ['risk-net']
tags: ['FX']
datum: ['2020', '202008']
description: 'Chatbots cut through delays in dealing with custodians'
---

{{< quote steelblue >}}_Chatbots cut through delays in dealing with custodians_{{< /quote >}}

Investing in foreign stocks and bonds can be more cumbersome than it first appears. Often, many of the workflows and processes go on behind the scenes between firms’ back-office operations, with multiple back-and-forth communications between counterparties’ custody teams.

The complexity of this process is exacerbated when dealing with investments in countries with currencies subject to controls imposed by their governments.

Some governments impose capital controls limiting the flow of funds into and out of a country to provide stability to the value of their currency. Examples of restricted currency countries include South Korea, China, Russia, Brazil, Malaysia, India, Indonesia, Thailand, Taiwan, and the Philippines. Investing in stocks and bonds in restricted currency countries requires investors to convert into the local currency linked to the assets.

Speaking separately to FX-Markets.com sister website WatersTechnology.com, both [BNY Mellon](https://www.waterstechnology.com/organisations/bny-mellon) and [Deutsche Bank](https://www.waterstechnology.com/organisations/deutsche-bank) explain that securities processing in restricted currency countries is mainly manual, and often managed using spreadsheets. The banks are aiming to bring a touch of automation to the process.

Gordon Alexander, head of client access and flow execution for Asia Pacific at Deutsche Bank, says helping international investors conduct FX conversions to buy a security can sometimes take as long as 36 hours to complete, as it involves satisfying various rules and approvals. Throw in the additional back-and-forth communication between operations, global custodians, and sub-custodians, and different time zones, and you have the perfect recipe for a long and drawn-out process.

To ease this process, BNY Mellon and Deutsche Bank developed an API-enabled FX workflow that eliminates several manual processes. In July, they applied the solution to custody of FX transactions in Korean won, successfully reducing the pre-trade lifecycle from hours to seconds.

Now that the solution is live in South Korea, the banks are working towards introducing it in Indonesia and India by early next year.

Darren Boulos, head of FX for Asia Pacific at BNY Mellon, says South Korea was the proof-of-concept market for the joint solution, as it is probably one of the more straightforward currency markets the bank operates in. “For Indonesia and India, there are other nuances such as withholding and other taxes that have to be added to the procedure, which complicates the process,” he says. ”They’re the next markets that we’re tackling. They are very large markets for our clients, and it’s important for us to try to achieve the same result of bringing the approval process down to seconds.”

To replicate the solution for Indonesia and India, BNY and DB are working to ensure that the currency leg of a transaction can be executed with the required tax calculations, regulations, and documentation.

Alexander says that because of the different nuances of each market, the workflow around a trade can prove more complicated than the FX conversion itself. “For different security markets, there are different types of rules that the custodian is required to follow in order for the FX to be executed. So the main work involved is not actually extending the APIs with new currencies—it’s really creating the rules and the scenarios for each market,” he says.

### Starting point

For BNY, the challenge of dealing in restricted currency markets comes from the manual processes used to perform the necessary validations and approvals before executing a trade. “Prior to entering into a foreign exchange transaction in those markets, you have to communicate account balances, make sure trade details are correct, and that any income and corporate action components are approved and have settled,” Boulos says.

The manual process of dealing with sub-custodians in restricted markets—where managing approvals for restricted currencies are predominantly spreadsheet-based—was a heavy operational burden. “There are a number of spreadsheets in any given currency, and it takes a significant amount of time to get an approval—as much as 12 to 18 hours to run the process from end to end,” he says.

While it doesn’t take long to execute the FX trade itself, getting the rate information back to the end investor can take longer due to the friction caused by various steps in the process, whereas this new process now has an API response time of between 10 and 15 seconds, Deutsche Bank’s Alexander says.

“The real-time approvals, individual requests are sent via a messaging channel and processed through the API. We’ve really reduced the number of delays because essentially they’ve been engineered out,” he says. “It’s a way of removing from the process the number of interactions or touchpoints you have between global custodian operations, sub-custodian operations, sub-custodian operations to [the] sub-custodian trader to confirm rates to global custodian operations, and trading for them to basically do the execution then come back to the end investor. That’s a lot of handshakes in that process.”

### From APIs to bots

The API-enabled solution leverages chatbots developed by BNY Mellon and Deutsche Bank—named Selina and Debbie, respectively—that have been integrated with collaboration services provider Symphony’s platform. BNY and Deutsche Bank first integrated their chatbot—both built on the Symphony platform—in 2018 to facilitate the flow of information for clients trading securities on the Hong Kong Stock Exchange (HKEx). The chatbot-to-chatbot communication solution replaces previously manual responses to status updates on securities trades.

For this specific case, the two set out to streamline and automate the securities lifecycle relating to the FX processes. Alexander says it was also to create a best practice for the industry for handling restricted market FX.

Separately, BNY is looking to also expand the product offering to its sub-custodians in other markets where it operates throughout the region, and in other parts of the world. Since launching the solution for Korean won, the firms have received interest from counterparties and other sub-custodians elsewhere, Boulos says.

BNY is looking at using APIs as an additional connectivity mechanism as not all clients have chatbots and access to Symphony. “The infrastructure could be built out using APIs, through other bots, and on other platforms to develop the solution,” he says.

This article originally appeared on [WatersTechnology.com](https://www.waterstechnology.com/operations/7664921/bny-mellon-deutsche-bank-to-extend-fx-api-for-indonesia-and-india).

