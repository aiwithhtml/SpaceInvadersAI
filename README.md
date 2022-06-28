# SpaceInvadersAI
Code for teaching an AI how to play Space Invaders with Keras and OpenAI gym. 

This is my project on training a model to play Space Invaders with stable baselines 3 and gym! Initially I used KerasRL and Tensorflow to try and create a model. That process was slow and quite complicated, and in the end, I had a script that could get the average score to about 250, and it would not get reliably higher than that. The average score for a random agent is about 150, and here is an example: 

![space_invaders](https://user-images.githubusercontent.com/53868567/176220892-61a10366-5da4-49b0-a463-a667a4e1f07b.gif)


My trained keras model was not exactly great, and required a lot of time to train it. If anybody wants to try, the script I was using is in the main branch, Keras Script is the file name.

Initially, I had used a modified version of that script for the Cartpole environment, and it solved it in about 50000 steps. However, Space Invaders was not going to work with that, and I had to try something different this time. I had begun hearing about something called Stable Baselines 3, the new and updated version of Stable Baselines. This library, which I would highly recommend for Machine Learning, was very convenient, and relatively easy to use. It gives a library of algorithms and ways to use them, as well as detailed documentation. If anybody wants a detailed look at it, here is the link:

https://stable-baselines3.readthedocs.io/en/master/index.html

Space Invaders is a discrete environment, and there are only a few algorithms in Stable Baselines that work with it. PPO, DQN and A2C are the best for this specific problem, and I used PPO, a more updated version of A2C. Be warned, if you want to use DQN, it is a great algorithm, but it takes a lot of space and memory to store the entire model of what you are training. 

https://stable-baselines3.readthedocs.io/en/master/guide/algos.html 

And now after training for about 20 million steps, here are a few gifs of our final model! I will include the code to make the gifs in this repository so you can show your friends what you created if you like ;).


