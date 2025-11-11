---
title: 'Bias Blog #2: Harms in Machine Learning'
date: 2025-1-30
permalink: /posts/2025/10/blog-post-8/
tags:
  - Generative AI
  - AI
  - Artificial Intelligence
  - Marginalized Communities
  - Case Study
  - Ethics
---

Some thoughts on Generative AI.

Case Study  
[Understanding Potential Sources of Harm throughout the Machine Learning Life Cycle.](https://mit-serc.pubpub.org/pub/potential-sources-of-harm-throughout-the-machine-learning-life-cycle/release/2)

---
The article touches on potential harms that may arise across the entire machine learning pipeline and emphasizes that undesirable consequences are not solely caused by biased data. Instead, the article notes that human decisions and processes spanning data collection, model development and deployment are the causes for the harm caused. Seven distinct sources of harm are then identified: historical bias, representation bias, measurement bias, aggregation bias, learning bias, evaluation bias, and deployment bias. 

So what are these harms, what do they mean, and how are they seen in real life? It can be tricky to understand the difference between the types of bias, but it is crucial to understand the role they play in the creation and deployment of technology. I’ve provided some real-life examples and defined each bias more specifically below. 

The article talks about historical bias as a bias that occurs even when data is perfectly measured and sampled and it arises because of the way the world is or was. The data reflects the world accurately, which includes the bias that exists within it. Even while the data may be accurate and measured, the bias can still be harmful. I have see an example of historical bias in an article I read recently. An article by the BBC notes a bias in Amazon’s AI hiring tool. The hiring tool was trained with accurate data, but the data showed that women were not hired as often as men in the tech field. The tool then continued to reflect this discriminatory bias. Looking at the data and determining whether there is a bias is important and can help resolve the model of historical bias, before it occurs. 

As for representation bias, the article explains it as a bias that arises when the development sample underrepresents a portion of the population. From this, many issues can arise. An example of this is when facial recognition technology does not have enough data of a certain population. Ultimately, representation bias can have very harmful effects. For example, a man could be wrongfully arrested if a police department used biased facial recognition technology.

Measurement bias appears in the “choosing, collecting, or computing features and labels to use in a prediction problem.” The bias comes to light in a feature or label that measures an idea is not observable or encoded. The article notes “creditworthiness” as an example as a measurement of a construct idea. Where this becomes problematic is when there is a poor reflection of the construct. An example of this is when there a schools that receive less funding that have students that might do worse on a standardized test due to this lack of funding. Students may not have the same access to resources as wealthier schools and students. This is a measurement bias because it does not accurately measure or take into account all factors at play. 

Aggregation bias is somewhat similar to measurement bias, in the way that it has to do with the compilation of data and the lack there of. Aggregation bias is using a one-size-fits-all model to address different groups. Different examples should be used for different groups, when applicable. Aggregation comes with a base assumption that all inputs will achieve the same output, which is simply untrue and often not the case. An example of this might occur when tracking the health and physical activity of participants in a study. If a one-size-fits-all model was used and differences such as age and medical conditions were not taken into account, aggregation bias may be at play. 

Learning bias is when the choices given to participants amplify performance disparities. There is little objectivity when this bias is at work. When prioritizing one objective over another creates damage, then there is a learning bias at play. Reducing learning bias meaning optimizing algorithms and prioritizing. An example of this is when using training data, using only data including female teachers. The model would then conclude that all teachers are female which is not a true representation of the real world. 

Evaluation bias is “when the benchmark data used for a particular task does not represent the use population.” Evaluation bias might be seen in an autonomous vehicle where a new sensor system is deployed. The dataset used to train the machine may include images of a sunny day, but when this is the only data used, the machine may have problems when the weather is not sunny. Sunny days are never guaranteed and if the vehicle cannot perform well if a pedestriation wears dark clothing at night or when it is storming, this can be very dangerous for the driver, pedestrians, other drivers, and more. 

The article defines deployment bias as when there is a not a connection between the problem a model is meant to solve and the way it’s actually used. If a system is built, evaluated, and deployed as if it were autonomous when its actually moderated by humans and institutions, then deployment bias is occuring. A real life of example of deployment bias might be when a medical triage system is being used. A medical triage system is meant to help nurses prioritize patients in an emergency room (ER). When the ER is understaffed, nurses may use the system as the sole determinator for triage order. This can have have a costly impact when a patient who was incorrectly scored has a delay in their treatment. 

So after understanding more about what each of these harms are, how can they be detected and mitigated? 

When it comes historical bias, the key is identifying the historical context and structural oppression that is associated with the data being used. To understand the context of which the data being used is imperative and once understanding, it is on the creator to then correct it. Use data that is well-represented and inclusive. For representation bias, I think an important solution would be to increase the use of targeted data. This works similarly to the solution for historical bias. Using targeted data means that the model will be more well-represented and inclusive. Where there is gaps in data, it is important to close those gaps. If a specific part of the population is left out, it is important to find data that includes them. I think it is the programmers responsibility to reduce measurement bias by creating reliability checks or performing qualitative studies to evaluate the measurement variables. These checks and studies should ensure that the measurements are consistent across different groups. 

When it comes to aggregation bias, the solution is to perform intersectional analysis. This analysis would help identify relevant subgroups that may not be obvious and would identify a divide in the distribution, if there were one. Learning bias needs to be reduced by using a variety of loss function, which would weight errors in minority groups. A variety of loss function would also help to analyze the trade-offs between the objectives and prioritize models where humans are able to interpret. If humans were able to interpret the models, then it would overall be easier to understand both how and why certain performance disparities are amplified. Utilizing a variety of metrics for evaluation would alleviate evaluation bias. Commuting confidence intervals could also be beneficial to understand the metrics and would ensure that a single measurement is not being relied on to show strength. Lastly, I think a solution to deployment bias might be conducting an observatiinal study to focus on the human’s decision making behavior and determine whether they can include specific information and appropriately train the model with it. 

Understanding what each bias is and their respective solutions still does not fully account for the creation process. I think a checklist for people that might be starting a new project could be incredibly helpful. If I were to draft a checklist for others to use in order to prevent different types of bias, this is what it would look like. I’ve included questions that I think are important to consider when looking at each bias. 
For historical bias: What is the historical context? Is the historical context playing a role in the output? What is the systemic inequalities that might be relevant to the topic? What is being done to address both the historical context and systemic inequalities at play? 

For representation bias: Has the target population been thoroughly developed? What is the development sample? Is anyone missing in this population? If so who and how can they be included? Is this an accurate representation of the actual use population? 

For measurement bias: Is every feature and label, is there a measurement that accurately reflecting the underlying roles? Does the method used for measuring have features and labels that vary across groups and subgroups? 

For aggregation bias: is there an accurate analysis of the data used? Is there data collected for important underlying groups? Is a one-size-fits-all apropriate in this case? Are there different groups that need to be measured differently? What are underlying roles and do they need to be measured differently? 

For learning bias: Have the specific objectives been analyzed? What might amplify disparities? Is there a way to combat this? What are possible trade-offs? Is there a way to ensure that underrepresented information is preserved? 

For evaluation bias: Is diverse and representative data used to evaluate the use population? What are underrepresented aspects? Are they relevant to the use case? If so, are they are evaluated? If they are not evaluated, can be done to include them? Are the reporting metrics accurate? Do the metrics appropriately reflect the costs of the affected population? 

For deployment bias: Is there a match between the the intended problem and ow will it be used in the world? Are the users educated on the limits of the model? Does the user interface allow for appropriate use and easy navigation? 

This article made me think about the way that data sets exist and are used in correlation with machine learning models and the training of such. It also raised a lot of questions for me, some of which were left unanswered and some of which made me think about what’s going in the world. 

In what high-stakes fields should the ethical priority lie? Are there fields, such as in healthcare or law, where it is more important to be ethical? Are there fields where it is not as much of a priority to ensure that machine learning models are ethical? I think that no matter the field it is important to be as ethical as possible, however when someone’s life is on the line such as in law or healthcare, it is more important to keep that a center focus. If that means sacrificing ethics in other fields, is it worth it? I’m not so sure, but it is something to think about. 
In an organization or company, whose job is it to identify and mitigate the biases that may be at play? I think that is crucial to identify and mitigate these biases, but who is responsible for that? I think it is on everyone involved in the process: the scientists, product managers, legal counsel, the executives. But is anyone meant to be more responsible than another? 

Lastly, what processes are necessary to ensure that users are able to continuously use the model as times evolve and things change? Does it mean an evaluation every year? How can we ensure that these machines continue to work in the way intended, even while times are changing and the future is uncertain? Is there a way to make predictions for that would help the machines stay current, without having to go back and change it after deployment? 

Like I mentioned before, this article made me about the way that data sets exist and are used in correlation with machine learning models. Going further, this article made me think about the privileges I have and the way that in many different aspects of my life, I would not have to consider the biases that may arise. I think that goes to show why it is so important to have a variety of backgrounds and perspectives in every single step of the process. Having white men in every position of power means that something will be overlooked or forgotten. Fostering diverse work environments and collaboration is one way of resolving bias. Another way to resolve bias is to stay educated and aware, as well as acknowledging the privileges that you may hold. 