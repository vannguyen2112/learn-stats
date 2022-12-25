---
date: [[2022-12-24]]
tag: writing, statistic, probability
---
ref: [[Mathematical statistic with application]] - [[what is statistic]], [[MIT_statistic for application]], [[Quantum dice]]
link: [[050 Writings MOC]], [[YOUR WRITING PROJECT GOES HERE]]


This piece is written to represent the answer of two question:
- What is the relationship of statistic and probability?
- How is it presented in statistical mechanic or more specifically: how from a simplified problem of quantum dice, the Bose and Einstein statistic is derived . 

#### Part 1: statistica and probability
In the half of the first lecture of [[MIT_statistic for application]], there was one figure that withdraw my attention:
![[Pasted image 20221224221414.png]]

One of the reason for my amazement is how simple it is to describe the concept of probability and statistic with just one figure. As you can see from this, probability concern with how the data will distribute, under the condition that some certain truth of the datatset is known. Statistics is, in reverse, questioning the population and the underlying truth of the population by looking at how it is distributed. 
However, by focusing on the relation between initial condition, result and method (probabilty/statistic), this figure overlook at how probability and statistics is connected and accidentally, might not contain fully information of the whole picture. This, luckily, is better communicated with words in book [[Mathematical statistic with application]]
Let's consider the example from [[what is statistic]] - [[Mathematical statistic with application]]. The example deal with a very simple typical problem in statistic: election poll - can we conclude if JOHN, our president candidate, is favored to win the election? Though the original  sample showed how probabilist and statistician answer this question out of our dataset, I would like to twisted it a bit by seeing how with the same set of data, which type of questions probailist and statiscian are interested in?
From the response of all eligible voters on election day, 20 sample was collected to form the population of interest. All 20 outcomes are in Favor for JOHNS. 
Given this same data, probabilist and statistician would analysis differently
|              | Info they know from the data                                                                                             | Info they should know to make conclusion                                                                                            | Question of interest                                                                                        |
| ------------ | ------------------------------------------------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------- |
| Probabilist  | The structure of dataset (the truth): 1. size of the data: 20 2. Outcome of each sample: in this case all favor for JOHN | Theory of probability                                                                                                               | Distribution of the data: Probability (fraction) of people favor for john out of population, in this case 100% |
| Statistician | Observation: 20 out of 20 favor for JOHNs                                                                                | Probability: hypothesis: there is less than 50 % want to vote for John. To check the hypothesis:  probability to have 20/20 outcome | The truth of the population: What is the confidence of our hypothesis? In this case, our confidence is low=> our hypothesis is wrong and we can include that John might win (with errors)                                                                                                               |

At the end of the day, probabilist use the theory of probability to characterise a known population, the statiscian in contrast would infer from this and probability theory the information of interest of an unknown population. Thus, the method of statistic inference can only be build up from a strong foundation of probability. 

#### Part 2: projecting this relationship onto statistical mechanics. 
(next week)