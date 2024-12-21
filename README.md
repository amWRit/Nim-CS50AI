# amWRit

# CS50AI 2020
## Week 3 (Learning) || Assignment -> Nim

Developed upon the original distro code provided by CS50AI team.

### Nim

Write an AI that teaches itself to play Nim through reinforcement learning.

````
$ python play.py
Playing training game 1
Playing training game 2
Playing training game 3
...
Playing training game 9999
Playing training game 10000
Done training

Piles:
Pile 0: 1
Pile 1: 3
Pile 2: 5
Pile 3: 7

AI's Turn
AI chose to take 1 from pile 2.
````

#### Background
Recall that in the game Nim, we begin with some number of piles, each with some number of objects. Players take turns: on a player’s turn, the player removes any non-negative number of objects from any one non-empty pile. Whoever removes the last object loses.

There’s some simple strategy you might imagine for this game: if there’s only one pile and three objects left in it, and it’s your turn, your best bet is to remove two of those objects, leaving your opponent with the third and final object to remove. But if there are more piles, the strategy gets considerably more complicated. In this problem, we’ll build an AI to learn the strategy for this game through reinforcement learning. By playing against itself repeatedly and learning from experience, eventually our AI will learn which actions to take and which actions to avoid.
#### Keywords
````
Machine Learning
Supervised Learning
Unsupervised Learning
Reinforcement Learning
Nearest-Neighbor Classification
Perceptron Learning
Support Vector Machines
Regression
Loss Functions
Overfitting
Regularization
scikit-learn
Q-Learning
````

#### References
````
https://cs50.harvard.edu/ai/2020/notes/4/
````
