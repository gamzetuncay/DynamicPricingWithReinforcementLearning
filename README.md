# Dynamic Pricing with Reinforcement Learning

https://doi.org/10.1080/03155986.2023.2235223
 
In this study, we propose a novel model to design dynamic hotel room pricing strategies that consider the specific requirements associated with the tourism sector. Reinforcement learning (RL) is used to formulate the problem as a Markov decision process (MDP) and Q-learning is used to solve this problem with a new reward function for hotel room pricing which considers both the profit and demand. In the proposed model, the basic features of the hotels are digitized and expressed in a way that similar hotels get close values. In this way, price predictions for the hotels that are newly included in the system can be made through similar hotels and the cold start problem is solved. In order to observe the performance of the proposed model, we used a real-world dataset provided by a tourism agency in Turkey and the results show that the proposed model achieves less mean absolute percentage error on test data. In addition, we also observe the training phase and show that the proposed RL method has smooth reward transitions between timesteps and has a reward curve more similar to the desired exponential rise compared to recently recommended RL models with different reward functions in dynamic pricing.

### DETAILS

The proposed model has experimented with the performance of predictions of the actual prices on a real data set obtained from a website of a tourism company in Turkey. The number of foreign tourists visiting Turkey has increased exponentially in the last two decades. In 1990, Turkey drew 4.8 million overseas tourists, generating $3.4 billion in revenue, but by 2019, before the COVID-19 pandemic, the figure had risen to $28.7 billion, with 51.7 million visitors. In addition to this insight, when assessing top destinations for international tourism based on international tourism receipts and international tourist departures, Turkey has maintained its status in recent years as the fourth most popular destination in the Mediterranean region and the sixth in Europe after tourism behemoths France, Spain, Italy, the UK and Germany. For these reasons, it has been interesting to
use tourism sale data belonging to Turkey. The dataset includes the room sales records of eighty popular hotels in Turkey for a total of 162 weeks in peak seasons between January 2013 and October 2021. To the best of our knowledge, this is the first study that investigates a dynamic pricing model based on the RL technique for the hotel industry. The main contributions of this study can be summarized as follows:

- Propose an Artificial Intelligence (AI) based dynamic pricing strategy for a realworld e-commerce platform of a tourism company
- Use of RL to formulate the hotel room pricing as a finite Markov Decision Problem (MDP) and solve it with Q-learning
- Propose a novel easy-to-use reward function for hotel room pricing which considers both the profit and ground truth demand values
- By using the basic features of the hotels in a way to make hotel comparisons; To be able to make price estimations for hotels that are newly included in the system and to find solutions to the cold-start problem
- Conduct detailed experiments on real-world data set to analyse different aspects of our proposed method

