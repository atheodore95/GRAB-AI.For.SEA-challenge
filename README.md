# GRAB-AI.For.SEA-challenge
This is a submission for GRAB AI For SEA challenge - computer vision. The project is about car classification. Given an image of a car, the model should be able to detect the brand, make, year, and color of the car. The data is using [Cars_Dataset](https://ai.stanford.edu/~jkrause/cars/car_dataset.html) from standford

## Accuracy
Accuracy achieved is approx. 89% on valididation data and 76% on test data so fine-tuning is still needed. Model used is Densenet121.

## Running the Code
All documentation is inside the notebooks, so you should be able to understand what each line of code does.

### Process Data
To process and split the data into train, validation and test, use:
```
Preprocess.ipynb
```
### Train and Validation
To train the model, use:
```
train.ipynb
```
### Test
To test the model, use 
```
test.ipynb
```

