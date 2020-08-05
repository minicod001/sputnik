---
title: 'OK, computer? Hurdles remain for machine learning in credit risk'
date: 2018-07-03T12:00:00+02:00
categories: ['risk-net']
tags: ['2018', '201807', 'risk management']
description: 'Concerns over cost, applicability and oversight give pause to banks’ use of ML techniques in credit risk'
---

{{< quote 4682b4 >}}_Concerns over cost, applicability and oversight give pause to banks’ use of ML techniques in credit risk_{{< /quote >}}

A technology that enables banks to make instant lending decisions. A technology that weighs up credit risk based on large amounts of available data and with little need for human intervention. A technology that, crucially, can learn for itself.

Banks are understandably keen to harness the perceived benefits of machine learning for credit risk. But as many firms are discovering, the technology is hard to master, requiring investment to develop and maintain methodologies. It is also attracting the attention of financial regulators who have begun to introduce curbs on its use.

“To some, the fact that machine learning models are automated is appealing. People think that because the results come from complex computer algorithms, they don’t have to do a lot of thinking and also they can trust them more,” says Vijay Nair, head of statistical learning and advanced computing at Wells Fargo. “But in reality, the opposite is true. These are black boxes. Without additional tools and knowledge about how to work with the algorithms and results, you don’t really know what is going on underneath. Problems can arise if you use them blindly.”

Machine learning, a subset of artificial intelligence, is a process that enables software to interpret data for itself. By giving a computer a sample set of data and a desired output, the machine develops its own model. This model is then applied to wider, real-life uses.

For credit risk, such uses could include an early-warning indicator of a retail customer that might become delinquent on a loan, or creating a dynamic measurement of a customer’s risk profile to better understand when to charge off a debt.

In a [survey](https://www.iif.com/publication/regulatory-report/machine-learning-credit-risk) of 60 financial firms, the vast majority of which were banks, by the Institute of International Finance in May, 88% of respondents were either currently using machine learning in credit risk, planning to deploy it within the next year or running pilot projects of the technology.

### Retail, commercial, corporate

Within credit risk, machine learning usage in retail and commercial areas of business is more advanced than in corporate credit risk, which lacks the data and necessary use cases. Data is the lifeblood of machine learning techniques and in the commercial and retail credit space there is plenty of data for algorithms to digest and analyse.

That’s not to say those areas don’t have their own drawbacks. Regulations in developed markets have limited the implementation of machine learning techniques in retail lending, to a degree.

In the US, a bank that rejects an individual for credit needs to provide adverse action and reason codes to explain why the decision was made, explains Derek Waldron, a partner at consulting firm McKinsey. In Europe, new data laws known as [GDPR](https://www.risk.net/regulation/5692056/regulators-need-to-adopt-ai-for-monitoring-experts-say) allow an individual to challenge a credit decision that was made by an automated process or algorithm. Consequently, banks are hesitant to automate underwriting with black boxes they don’t fully understand, Waldron says.

When making credit lending decisions, the onus is on banks to [explain](http://www.risk.net/risk-management/5334681/banks-tout-machine-learning-amid-regulatory-scepticism) how they reached their conclusion, says Suhail Shergill, director of data science and model innovation at Scotiabank. That’s not always easy when using machine learning techniques, he says. A bank can’t simply point a consumer to a complex model to [explain](http://www.risk.net/risk-management/5334681/banks-tout-machine-learning-amid-regulatory-scepticism) why their request for a loan has been rejected.

“If the model is driving credit extension decisions, the risk teams have a responsibility to make sure a credit is extended in compliance with the lending laws,” Shergill says. “As you start getting into this territory, it starts becoming harder because you have a greater due diligence to perform. If I am building a sophisticated model, I need to be able to justify it and explain its results.”

That’s not to say those areas of credit risk will never be able to employ machine learning-based models. Experts say hybrid approaches, which blend machine learning techniques with traditional models and human expertise, are a preferred option for areas of credit risk with more regulatory oversight. Here, machine learning techniques augment traditional credit scorecards.

“A number of banks are using machine learning to help identify new insights to incorporate into their existing statistical modelling approaches,” Waldron says. “For example, machine learning can identify new predictive features and transformations as well as segments that should be carved out and treated separately. We are essentially using machine learning as a method to capture insight, which can then help improve the way we design and build traditional scorecards.”

Shergill agrees that developers will need to build in human input to machine learning processes, to provide an element of judgement that machines are not equipped to give.

“I do think there still is going to be a human in the loop. The frontier of what is automated will certainly continue to advance, but that just means that the frontier of what people are doing – what the humans in the loop are responsible for and the judgement they are providing – will also continue to evolve.”

Not all banks have to be as cautious in meeting strict regulatory requirements, though. Smaller, regional banks in jurisdictions with looser lending regulations, particularly in Asia and Latin America, are exploring the boundaries of machine learning in their retail credit risk decision making, says Waldron.

Gaurav Chawla, director of credit analytics at consultancy Parker Fitzgerald, points out that some of these areas don’t have the established lending practices that exist in Europe and the US. These immature markets are more susceptible to corruption in the lending process, he says. The introduction of an automated, machine learning-based model that would remove human bias would be a welcome safeguard.

“If you think of machine learning or any sophisticated model, that is a step ahead compared to the existing process, which is to only lend to someone who you are connected to,” he says.

In corporate lending, where there is a limited number of large companies, datasets are less widely populated, which makes it harder for machine learning techniques to be applied. Observers also question the need for [advanced models](https://www.risk.net/risk-management/5320396/this-tangled-web-banks-seek-to-contain-systemic-model-risk) in the space because of the nature of existing data. Credit ratings, for example, are well established among corporates, says Chawla.

“In the large corporate space there is already consensus. The data quality is very high,” he says. “You won’t change your opinion or decision with any sophisticated model. AT&T is already AT&T. How much more material do you want to run on top of it?”

### A trip to the forest

Application of [machine learning techniques](https://www.risk.net/definition/machine-learning)in credit risk has coalesced around two methods: random forest and gradient boosting. Random forest uses a large number of simple decision tree classifiers and then combines them to improve predictive power. Boosting also uses decision trees, but is a more sequential methodology where corrections are incrementally added in an attempt to improve the predictions of the model, Waldron says.

The techniques, which are two of the more popular machine learning methodologies, offer greater transparency than other machine learning methods and share similarities with banks’ current credit risk models, Shergill says.

“When you look at traditional risk models and say, ‘what is the way that is most similar but allows us to build more sophisticated models?’, the natural extension comes out to be boosted models and random forest. Such models can integrate relatively easily with existing decision systems, and can be easily explained when implemented with some simplifications,” Shergill says.

Some firms have also explored more advanced machine learning techniques such as neural networks, which can be taught to learn in a more automated way than the simple variable reduction offered through methods using decision trees like boosting or random forest.

However, increased sophistication also makes the model harder to understand, complicating its cost/benefit analysis, says Spencer Robinson, head of strategy at machine learning start-up Kabbage. More complexity means higher costs to manage the model, he says. The result could mean that a slightly more accurate model isn’t worth implementing.

“I have yet to see the performance of the neural net model so drastically outweigh the performance of random forest that it merits the extra cost it would take for me to essentially manage that neural net in a production environment,” he says. “I think those costs will come down over time. As you start to embed more complex feature generation, you start to think about bringing in the deep-learning concept into it.”

### Explain yourself

While some areas of credit risk modelling, such as portfolio management or collections, are more suitable for the opacity and automation that advanced machine learning-based models offer, other areas are less suitable. In underwriting and stress testing, for example, regulatory requirements for the [transparency](http://www.risk.net/risk-management/5355856/banks-apply-machine-learning-to-ccar-models) of risk models are stricter, making machine learning harder to justify.

Banks have begun to combat this lack of transparency by making efforts to open up their black boxes for inspection. But measures offering better transparency of machine learning-based models have met with varying degrees of success, Nair says.

Inhibiting the process is a lack of direction from supervisors, who have offered loose guidance on how financial firms should explain or justify their machine learning models, Nair says. So far, no established techniques have received an official seal of approval from regulators; neither have any techniques been formally rejected. Instead, regulators have taken the approach of inviting banks to explain their modelling methods. Authorities may then challenge the methods and then decide if they are appropriate.

This “hands-off” attitude from regulators has caused some banks to temper their focus on machine learning in credit risk, says a risk manager at a large European bank. While the bank has invested some money in looking at machine learning applications in credit risk, he says, it’s not a core focus and there is not a major drive internally to replace the existing model infrastructure.

“The regulatory angle is more a hindrance than a help. It’s not clear that you are going to get anything through,” the risk manager says. “We are not yet at the point where there is an obvious advantage for somebody using these [machine learning] credit-scoring methods in a business sense. If that becomes more apparent, then I think the focus will shift.”

### Inadvertent discrimination

In winning over regulators to the merits of machine learning, banks will first have to tackle certain innate weaknesses in the techniques. One common flaw is the susceptibility of machine learning models to bias, albeit unintentional. A quant at a European bank says machine learning-based models, regardless of what business segment they are operating in, can be prone to inadvertent discrimination. This occurs in areas where data is sparse, the quant says, skewing the average to influence outcomes more than the actual diversity of the group.

Inadvertent discrimination is an issue that all machine learning models face, the quant says, but is particularly magnified in credit risk where its manifestation can be seen as social or structural bias against certain types of firms or people. There is no simple workaround either, he adds, as the model is simply working with the data provided. It is the model developers’ responsibility to balance the bias and variance of the model, the quant says, in what is known as the bias-variance trade-off.

“You try to create a model that is not making a decision based on every little variable that it sees,” he says. “When it builds those averages, it tends to have a bias. It is a balancing act that the model designer always has to do in all machine learning models. The biased side of it introduces this risk that the model is biasing some participants who are being evaluated.”

Properly calibrating machine learning models and ensuring they are getting the right data is critical. A model risk manager at a European bank says his firm had to scrap a wholesale credit model it was developing because it was not sensitive to extreme macroeconomic shocks. The model was a random forest that fit historical data well but couldn’t handle extreme moves outside of its historical experience, the manager says.

The model will eventually be refined and revisited in the future, he says, and could prove useful for defined usage cases.

Wells Fargo’s Nair says machine learning-based models need to do a better job of accounting for macroeconomic variables. This issue is particularly troublesome when it comes to applying machine learning techniques to stress testing, he says.

“Machine learning algorithms are tailor-made for large datasets – both observations and predictors. But if we throw in lots of account-level predictors, they tend to suck up predictive power from macroeconomic variables with which they are correlated,” Nair says. “Then, if you do stress testing by changing the values of key economic variables to extreme conditions, you may not see the changes in prediction you might expect.”

The quant at the European bank believes there will be a natural progression towards the adoption of machine learning techniques in credit risk. However, he believes banks will not make initial investments in trying to replace the algorithms that are their bread and butter. Even if the machine learning techniques could produce more accurate results than the status quo, he says, the overall impact to the entire system of switching models could be too disruptive.

Instead, the quant says, banks will likely focus on areas where their traditional rules-based models, which are built around a static rule set and therefore less dynamic than machine learning models, have been unsuccessful. But that logic is setting up machine learning models to potentially fail, he adds.

“A rules-based model is not going to work in areas where there is not enough data,” the quant says. “So they are going to try and apply the machine learning models that have some ability to address sparse data. So here you have machine learning models naturally being pushed into the areas where they are likely to have higher bias.”

The risk manager at the large European bank remains sceptical over how quickly adoption of machine learning techniques in credit risk will occur. He says the ultimate driver of machine learning implementation in banks’ credit risk departments will be the threat of non-bank lenders. While banks are always interested in finding better ways to manage risk, it’s not typically where the big investment money goes, he says.

Fear of being squeezed out of their business, on the other hand, is a much stronger motivator to innovate, he adds.

“It’s ultimately going to come from banks’ business models being undermined by more agile competition,” he says. “If we see more fintechs succeeding in building banking platforms and banking offers that people take up in the retail space, then that will require banks to go down similar routes.”

Editing by Alex Krohn

