Runnable notebooks with basic reinforcement learning examples.

# Pre-requisites

* Jupyter notebook
* PyTorch
* Numpy
* Matplotlib
* OpenAI Gym (install using pip)
* tqdm

# Q-learning

You should see performance the looks like this:

![./images/q_learning_curve.png](Q-learning training curve)

Precise behaviour will vary and sudden dips in performance are common.

# Extensions

Things you could implement:
* Goal-dependence. Can you make the cart-pole move the pole to a specified location?
* Different environment. Can you solve MountainCar? LunarLander?
* [Double Q-learning](https://papers.nips.cc/paper/2010/file/091d584fced301b442654dd8c23b3fc9-Paper.pdf) - Conservative estimation of the Q-function, more stable.
* [DDPG](https://spinningup.openai.com/en/latest/algorithms/ddpg.html) - Allows you to use continuous action spaces.

