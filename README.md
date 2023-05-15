# BitcoinPrediction
In this repository we will be working on the future rate prediction of bitcoin.
We have just cleaned and worked little bit on our dataset. 
In addition to that we have built som basic graphs without using any tyoe model in framework.

# Deep Learning (DL):
Form of machine learning that utilize a neural network to transform a set of input into a set of put vis artificial neural network. So, we have used two models of the deep learning which are Recurrent Neural Network and N-beats.
# Reinforcement Learning (RL):
A process in which an agent learns to make decisions through trial and error.
(It is similar to training you dog, when your dog performa the trick you reward him and if he does not you punish him.)
                <img width="538" alt="dog example" src="https://github.com/chelseananda/BitcoinPrediction/assets/60791339/6d191c2f-dec1-41a9-9d9b-5fb876061ac1">

Terminologies used in the RL are defined below:
1. Agent: The decision-maker to train
2. Environment: General setting where agent learns and decides what actions to take.
3. Action: One among the set of possible actions the agent can perform. (a)
4. State: Conditions that the agent is on. (s)
5. Reward: The result agent get from its own action from the environment in terms of gain or loss.(r)
6. Policy: The strategy chosen by the agent. It represents a mapping between the set of situations and the set of possible actions. (∏ - pie)
To understand more efficiently we can think of the PacMan game.
                <img width="550" alt="Screenshot 2023-05-15 at 5 43 41 PM" src="https://github.com/chelseananda/BitcoinPrediction/assets/60791339/ec69bbc6-5430-4b30-ac17-752165808eb6">

# Metrics: 
There are 2 metrics for the RL:
a. Value Function V∏(s): It is the expected discounted REWARD startin g with state s and successively following policy ∏.
                <img width="312" alt="Screenshot 2023-05-15 at 5 45 58 PM" src="https://github.com/chelseananda/BitcoinPrediction/assets/60791339/50d38a3e-49c9-456c-90c2-051043f54a1b">
                
b. Q-Value Q∏(s,a): It is the expected discount return when in a given states s and for given action a while following the policy ∏* thereafter.
                <img width="197" alt="Screenshot 2023-05-15 at 5 48 19 PM" src="https://github.com/chelseananda/BitcoinPrediction/assets/60791339/7b93a114-c077-456a-95e1-a599a1954580">
    
# Deep Reinforcement Learning:
A subfield of machine learning that combines reinforcement learning and deep learning.
# ADVANTAGES: 
1. Outperformance in many challenging games compare dto humans.
2. Returning hte maximized trading goal.
3. Providing the sequential feedback for the stock market.
4. Usage of exploration and exploitation technique.
5. Computational Power by using Q-Learning and Deep Learning Neural Networks.
Therefore for the provided thesis we can combine Deep learning and Reinforecement Learning using the Q-Learning approach which consist of building and traing the neural networks or model capable of estimating given state, by using different Q - Values for each action.
                <img width="859" alt="Screenshot 2023-05-15 at 6 14 26 PM" src="https://github.com/chelseananda/BitcoinPrediction/assets/60791339/7c6db205-187d-40c9-aba8-88271e86af63">

# Question: Why are we combining the deep learning and Reinforcement Learning? 
We are combining the rL and DL to maximise the performance. In Deep Learning we a have some limitations such as requirement of massive daa resulting into long training time. But adding the Reinforcement Learning we can solve more complicated tasks with lower prior knowledge and resulting into lesser time and maximising the reward.

# Question: Why we are using DRL in stock trading?
1. The main aim of stock trading is to maximize returns while avoiding the risks, which DRL solves perfectly by maximizing the expected total reward from the future action over the time period.
2.We are using the DRL in the stock trading due to some limitation in the current models or works. For example, in case of DRL and Modern Portfolio Theory he performance is not well performed in the out-of-sample data. Moreover, it is only caluclated based on the stock returns irrespective of the ither technical indicators for stock prices.

Three actor-critic (name of the deep learning algorithms) based algorithms: 
1. Proximal Policy Optimization (PPO)
2. Advantage Actor-Crtic (A2C)
3. Deep Deterministic Policy Gradient (DDPG)
The performance of the algorithms and brrn evaluated using the SHARPE RATIO which is done by the comparison with 1. Dow jones Industrial Average Index and 2. Traditional min -variance portfolio allocation strategy.

