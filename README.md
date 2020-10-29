# autonomous-vehicle-reinforcement
 The project self-driving (autonomous) vehicle, uses Udacity open-source simulator to implement deep-reinforcement and semi-supervised learning, The provided simulator is the sole property of Udacity.

## How to use:

###1) Use anaconda environment
###2) Install all the requirements from ```requirements.txt``` file by typing ```pip install -r requirements.txt```
###3) Initially start the simulator in training mode, click on record button, collect the image dataset (collected from 3 different cameras fixed on our simulated car)
###4) Check the IMG folder having image dataset, and also check driving_log.csv (consisting path of 3 images at a time and intensity of L R A B respectively)
###5) Run the model.py file, which consist our CNN model (feel free to edit and experiment)
###6) Once model trained, open the simulator in autonomous mode, and in anaconda environment type ```python drive.py <model.h5>```, for reference you can also use ```driving_model.h5```

##Simulator Images
![](screenshot1.gif)

**************************************

![](screenshot2.gif)

**************************************

![](screenshot3.gif)


