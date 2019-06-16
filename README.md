# GRAB-AI.For.SEA-challenge
This is a submission for GRAB AI For SEA challenge - computer vision. The project is about car classification. Given an image of a car, the model should be able to detect the brand, make, year, and color of the car. The data is using [Cars_Dataset](https://ai.stanford.edu/~jkrause/cars/car_dataset.html) from standford

## Dependencies
Library needed to run the codes:

- [NumPy](http://docs.scipy.org/doc/numpy-1.10.1/user/install.html)
- [Tensorflow](https://www.tensorflow.org/versions/r0.8/get_started/os_setup.html)
- [Keras](https://keras.io/#installation)
- [OpenCV](https://opencv-python-tutroals.readthedocs.io/en/latest/)


## Running the Code
All documentation is inside the notebooks, so you should be able to understand what each line of code does.

### Process Data
To process and split the data into train, validation and test, use:
```
preprocess.ipynb
```
### Train and Validation
To train and validate the model, use:
```
train_validation.ipynb
```
### Test
To test the model, use:
```
test.ipynb
```

## Accuracy
Accuracy achieved is approx. 89% on valididation data and 76% on test data so fine-tuning is still needed. Model used is Densenet121.
