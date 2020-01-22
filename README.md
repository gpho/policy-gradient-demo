# A demo of REINFORCE: the simplest Policy Gradient reinforcement learning algorithm

REINFORCE is the most basic of policy gradient algorithms, a class of reinforcement learning algorithms which represent the policy explicitly and optimize its parameters using gradient descent. As described in our presentation slides, the algorithm underlying REINFORCE is simple to understand and has a direct analogy to gradient descent in supervised learning.

As a project in Harvard's [Advanced Machine Learning, Data Mining, and Artificial Intelligence (CSCI E-82)](https://canvas.harvard.edu/courses/52820/assignments/syllabus) course in Fall 2018, I developed this notebook to demonstrate a simple implementation of the REINFORCE algorithm using TensorFlow, Keras, and OpenAI gym.

### Prerequisites

This code uses the following packages:

```
pip install gym
```

### TO-DO
* Add videos to demo
* Update Prerequisites

## Acknowledgments

Thanks to Mahmood M. Shad who collaborated with me on the presentation slides for this project.

This work lends code and/or inspiration from multiple sources:

Learning material
* Great blog post intro by Andrej Karpathy: http://karpathy.github.io/2016/05/31/rl/
* Great course materials:
  * Reinforcement Learning at UCL by David Silver: http://www0.cs.ucl.ac.uk/staff/d.silver/web/Teaching.html
  * Deep RL at Berkeley by Sergey Levine: http://rail.eecs.berkeley.edu/deeprlcourse/
*  Best intro book: Reinforcement Learning by Sutton & Barto (free pdf): http://incompleteideas.net/book/the-book.html
* Great YouTube explanations by Arxiv Insights: https://www.youtube.com/channel/UCNIkB2IeJ-6AmZv7bQ1oBYg

Code bases
* OpenAI Spinning Up: https://spinningup.openai.com/en/latest/
* See also Baselines https://github.com/openai/baselines)
* garage/rllab (Berkeley): https://github.com/rlworkgroup/garage
* Deep RL course with ipynb examples: https://github.com/simoninithomas/Deep_reinforcement_learning_Course
* Minimal and clean code examples: https://github.com/rlcode/reinforcement-learning
