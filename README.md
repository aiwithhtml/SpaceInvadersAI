# SpaceInvadersAI
Code for teaching an AI how to play Space Invaders with Keras and OpenAI gym. 

Packages needed are tensorflow, keras and gym. 
in order to install, run commands in order:

pip install gym[all]

pip install stable-baselines3

pip install gym[accept-roms-license]

Then close out of VSCode and reopen, it should have installed.

In order to train a model, function agent.train() trains your model. 
In order to make the model play, function agent.test() tests your model. 

The saved model is SpaceInvadersModel.h5 for anybody who wishes to skip the training. 
