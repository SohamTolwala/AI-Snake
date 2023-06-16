# Teach AI To Play Snake! Reinforcement Learning With PyTorch and Pygame

In this game the AI i.e agent will teach itself how to play a normie snake 
game. The main modules that have been used are PyTorch and Pygame. We 
have implemented Q-Learning which is Reinforcement Learning technique.

Reinforcement learning - Reinforcement learning (RL) is an area of machine learning concerned with how software agents ought to
                         take actions in an environment in order to maximize the notion of cumulative reward.
                         In other words we can also say is teaching a software agent how to behave in an environment by telling him
                         how good its doing.

                                                [agent is refereed as computer player]

Q Learning Algorithm - Value based approach based on Q - table.
                       Basically calculates the maximum expected future reward for each action at each state
                       1. Initialize Q-values (=init model)
                       2. Choose an action(a) for current state(s) - based on current best Q-value (model.predict(state))
                       3. Perform action(a) and then we observe then we get a new state(s')
                       4. Measure the reward for the action
                       5. Update the Q-value using Bellman equation ( + train model)
                       6. Then we repeat steps 2-5 until the learning no longer improves and then in the end we get a Q-table

              NOTE - a. In the beginning choose the action(a) randomly so that the agent can explore the environment.
                     b. The more training steps we get, the more we reduce the random exploration and use exploitation instead
                     c. We have implemented Deep Q Learning in this project







Modules used in the project:
    1) pygame - for creating a game environment
    2) Enum - it is a class for creating symbolic names / enumerations
    3) Torch - torch.nn - A neural networks library deeply integrated with autograd designed for maximum flexibility
               torch.optim - torch.optim is a package implementing various optimization algorithms. Most commonly used
                             methods are already supported, and the interface is general enough, so that more sophisticated ones
                             can be also easily integrated in the future.
                             REFER - https://pytorch.org/docs/stable/torch.html

                            



