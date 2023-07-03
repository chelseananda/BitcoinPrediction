# BitcoinPrediction
In this repository, we will be working on the future rate prediction of Bitcoin.
We have just cleaned and worked a little bit on our dataset. 
In addition to that we have built some basic graphs without using any type of model in the framework.

# Deep Learning (DL):
Form of machine learning that utilizes a neural network to transform a set of inputs into a set of put vis artificial neural network. So, we have used two models of deep learning which are Recurrent Neural Networks and N-beats.
# Reinforcement Learning (RL):
A process in which an agent learns to make decisions through trial and error.
(It is similar to training your dog, when your dog performs the trick you reward him and if he does not you punish him.)
                <img width="538" alt="dog example" src="https://github.com/chelseananda/BitcoinPrediction/assets/60791339/6d191c2f-dec1-41a9-9d9b-5fb876061ac1">

Terminologies used in the RL are defined below:
1. Agent: The decision-maker to train
2. Environment: General setting where the agent learns and decides what actions to take.
3. Action: One among the set of possible actions the agent can perform. (a)
4. State: Conditions that the agent is on. (s)
5. Reward: The resulting agent gets from its action from the environment in terms of gain or loss. (r)
6. Policy: The strategy chosen by the agent. It represents a mapping between the set of situations and the set of possible actions. (∏ - pie)
To understand more efficiently we can think of the PacMan game.
                <img width="550" alt="Screenshot 2023-05-15 at 5 43 41 PM" src="https://github.com/chelseananda/BitcoinPrediction/assets/60791339/ec69bbc6-5430-4b30-ac17-752165808eb6">

# Metrics: 
There are 2 metrics for the RL:
a. Value Function V∏(s): It is the expected discounted REWARD starting g with state s and successively the following policy ∏.
                <img width="312" alt="Screenshot 2023-05-15 at 5 45 58 PM" src="https://github.com/chelseananda/BitcoinPrediction/assets/60791339/50d38a3e-49c9-456c-90c2-051043f54a1b">
                
b. Q-Value Q∏(s, a): It is the expected discount return when in a given states s and for given action a while following the policy ∏* thereafter.
                <img width="197" alt="Screenshot 2023-05-15 at 5 48 19 PM" src="https://github.com/chelseananda/BitcoinPrediction/assets/60791339/7b93a114-c077-456a-95e1-a599a1954580">
    
# Deep Reinforcement Learning:
A subfield of machine learning that combines reinforcement learning and deep learning.
# ADVANTAGES: 
1. Outperformance in many challenging games compared to humans.
2. Returning the maximized trading goal.
3. Providing sequential feedback for the stock market.
4. Usage of exploration and exploitation techniques.
5. Computational Power by using Q-Learning and Deep Learning Neural Networks.
Therefore for the provided thesis, we can combine Deep Learning and Reinforcement Learning using the Q-Learning approach which consists of building and training the neural networks or model capable of estimating a given state, by using different Q - Values for each action.
                <img width="859" alt="Screenshot 2023-05-15 at 6 14 26 PM" src="https://github.com/chelseananda/BitcoinPrediction/assets/60791339/7c6db205-187d-40c9-aba8-88271e86af63">

# Question: Why are we combining deep learning and Reinforcement Learning? 
We are combining the rL and DL to maximize the performance. In Deep Learning we have some limitations such as the requirement of massive data resulting into a long training time. But by adding the Reinforcement Learning we can solve more complicated tasks with lower prior knowledge and resulting in lesser time and maximizing the reward.

# Question: Why we are using DRL in stock trading?
1. The main aim of stock trading is to maximize returns while avoiding the risks, which DRL solves perfectly by maximizing the expected total reward from the future action over the period.
2. We are using the DRL in stock trading due to some limitations in the current models or works. For example, in the case of DRL and Modern Portfolio Theory, the performance is not well performed in the out-of-sample data. Moreover, it is only calculated based on the stock returns irrespective of the other technical indicators for stock prices.

Three actor-critic (name of the deep learning algorithms) based algorithms: 
1. Proximal Policy Optimization (PPO)
2. Advantage Actor-Critic (A2C)
3. Deep Deterministic Policy Gradient (DDPG)
The performance of the algorithms and been is evaluated using the SHARPE RATIO which is done by comparison with 1. Dow Jones Industrial Average Index and 2. Traditional min-variance portfolio allocation strategy.

#Coding
Worked in the FINRL Coding and found out the models techniques and all the data sources used in the code.
In addition to that working on how to add N-beats and RNN models into the FINRl models.
Downloaded and fixed the code to make it run.

