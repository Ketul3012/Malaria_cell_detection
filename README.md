# Malaria_cell_detection
Malaria cell detection using Tflearn.

To Download dataset Go to (www.kaggle.com) and download malaria cell data. Which consists of two directory Parasitized and Uninfected which have image data for infected and uninfected data.

Basic requirements:
```javascript
tensorflow
tflearn
augmentor
numpy 
opencv
pillow
```

To install this requirements first set-up python and pip installer to your system then go to command line and run following commands:
```javascript
pip install tensorflow
pip install tensorflow-gpu
pip install tflearn
pip install Augmentor
pip install numpy
pip install opencv2
pip install Pillow
```
Tensorflow-gpu for those who have cuda enabled gpu.

Augmentor used to avoid limitation of data. Augmentor augments data in differnt directions and differents zoom/shear etc and also horizontal and vertical flips for image data. This allows us to make data of any size from out small data set.

One concern is taken before data augmentation is not to augment detection object in that way thst's it loose it's meaning.

To learn more about augmentor Go to (https://augmentor.readthedocs.io/en/master/).

Tflearn is a highlevel api/library for tensorflow Which increase our productivity to make tensorflow models very easily.Tflearn provide easy to understand implementation for different algorithms and models.

To learn more about Tflearn Go to (http://tflearn.org/)

Try to take deep dive in code and njoy machine learning!.
