# SpaceInvadersAI
Code for teaching an AI how to play Space Invaders with Keras and OpenAI gym. 

Packages needed are tensorflow, keras and gym. 
in order to install, run commands:

pip install gym[atari]

pip install tensorflow

pip install keras

pip install gym[accept-roms-license]

pip install ale-py

pip install pyyaml h5py

Then close out of VSCode and reopen, it should have installed.

In order to train a model, agent.train() trains your model. 
In order to make the model play, agent.test() tests your model. 

The saved model is SpaceInvadersModel.h5 for anybody who wishes to skip the training. 
