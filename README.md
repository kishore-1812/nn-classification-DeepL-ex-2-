# Developing a Neural Network Classification Model

## AIM

To develop a neural network classification model for the given dataset.

## Problem Statement

An automobile company has plans to enter new markets with their existing products. After intensive market research, they’ve decided that the behavior of the new market is similar to their existing market.

In their existing market, the sales team has classified all customers into 4 segments (A, B, C, D ). Then, they performed segmented outreach and communication for a different segment of customers. This strategy has work exceptionally well for them. They plan to use the same strategy for the new markets.

You are required to help the manager to predict the right group of the new customers.

## Neural Network Model

![neural network model](https://user-images.githubusercontent.com/63336975/189726216-a65ea909-94d1-4973-a90e-04d9810d852f.png)


## DESIGN STEPS

### STEP 1:
Load the dataset.

### STEP 2:
Split the dataset into training and testing.

### STEP 3:
One hot encode the categorical data.

### STEP 4:
Create MinMaxScalar objects ,fit the model and transform the data.

### STEP 5:
Build the Neural Network Model and compile the model.

### STEP 6:
Train the model with the training data.

### STEP 7:
Plot the performance plot

### STEP 8:
Evaluate the model with the testing data.

## PROGRAM

```python
print('helloworld')
```

## Dataset Information

![image](https://user-images.githubusercontent.com/63336975/189724440-bf32225f-6c82-463a-bb9c-907cffb784b3.png)

## OUTPUT

### Training Loss, Validation Loss Vs Iteration Plot
![image](https://user-images.githubusercontent.com/63336975/189725455-3755410b-2126-4126-a41e-d85c6ef8d07b.png)


### Classification Report

![image](https://user-images.githubusercontent.com/63336975/189725564-eb937507-a563-47c5-9e61-4601f64699e3.png)


### Confusion Matrix
![image](https://user-images.githubusercontent.com/63336975/189725653-74944f4b-317f-4a5c-9159-b2d5bbf2600c.png)



### New Sample Data Prediction

![image](https://user-images.githubusercontent.com/63336975/189725738-21ac0e4d-f571-4699-be3e-0aeeab37bf9b.png)


## RESULT
Successfully built a neural network classification model for the given dataset and produced successful results.
