# PredictiveEnvironments
_Exploring how the underlying assumptions of predictive environments influence human systems._

In supervised machine learning, there is _often_ an underlying assumption that the data the model will encounter in the future (test set) is statistically similar to data encountered in the past (training set). When humans encode these beliefs in predictive environments that shape what news we read, what friends we interact with, what products we buy, ..., surprising outcomes can emerge.

The goal of this project is to answer:
- What are these suprising outcomes?
- Can we explore them in a lab?
- Can we simulate these effects with reinforcement learning agents? See: https://github.com/BlissChapman/WarGames

### Experiment Framework
Agent A-Z are provided a representation of the state of the world by the _Omega_ game simulation. However, unlike a traditional reinforcement learning environment, _Omega_ itself is a predictive model with a reward function. _Omega_ interacts with the world only through the state representations it provides the agents. The reward function of agents A-Z and of the _Omega_ environment are not the same. 

- Under what conditions can the agents succeed?
- What if we allow agents more direct control of their coevolution with the environment?
