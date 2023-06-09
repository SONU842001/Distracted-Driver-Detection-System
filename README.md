# Distracted_Driver_Detection


We've all been there: a light turns green and the car in front of you doesn't budge. 
Or, a previously unremarkable vehicle suddenly slows and starts swerving from side-to-side.

When you pass the offending driver, what do you expect to see? 
You certainly aren't surprised when you spot a driver who is texting, seemingly enraptured by social media,
or in a lively hand-held conversation on their phone.

![model](./graph/1.PNG)

The 10 classes to predict are:

- c0: normal driving
- c1: texting - right
- c2: talking on the phone - right
- c3: texting - left
- c4: talking on the phone - left
- c5: operating the radio
- c6: drinking
- c7: reaching behind
- c8: hair and makeup
- c9: talking to passenger

![model](./graph/2.PNG)
![model](./graph/3.PNG)

### Dependency

The main Python packages:
- [Opencv](http://opencv.org/)
- [NumPy](http://www.numpy.org/)
- [TensorFlow](http://tensorflow.org)
- [Keras](https://keras.io)

The running environment is [Jupyter Notebook](https://jupyter.org/install.html).

### Data

The dataset is provided by [Kaggle State Farm](https://www.kaggle.com/c/state-farm-distracted-driver-detection/submissions?sortBy=date&group=successful&page=1). You can down load the dataset after creating an ancount.


### Application

The real-time camera application is built in imp.ipynb.
