# HealthySleep

HealthySleep is a Swift-based iOS app designed to help coffee drinkers optimize their sleep schedule. By asking a few simple questions and leveraging the power of Core ML, HealthySleep predicts the best time for you to go to bed to wake up feeling refreshed.

## Overview
HealthySleep combines a user-friendly interface with advanced machine learning techniques to solve a practical problem. Exploring topics such as:

1. **Stepper** - For entering numeric values.
2. **DatePicker** - For selecting dates and times.
3. **DateFormatter** - For working with date and time formatting.
4. **Core ML** - For training and using a machine learning model.
5. **Create ML** - For generating and testing the machine learning model.

## Features
The app asks three simple questions:

1. **When do you want to wake up?**
2. **How many hours of sleep do you need?**
3. **How many cups of coffee do you drink per day?**

Using these inputs, HealthySleep calculates your optimal bedtime using a regression analysis model trained with Core ML.

## Learning Outcomes
By working through this project, you will:

1. Understand how to use **Stepper** for numeric input.
2. Learn to use **DatePicker** for intuitive date and time selection.
3. Manipulate and display dates and times using **DateFormatter**.
4. Train and integrate machine learning models into your app with **Core ML**.
5. Use **Create ML** to generate machine learning models for practical applications.

## Topics Breakdown
### 1. Entering Numbers with Stepper
Learn how to use the `Stepper` control to allow users to increment or decrement numeric values, such as the number of cups of coffee.

### 2. Selecting Dates and Times with DatePicker
Use the `DatePicker` control to capture the user’s desired wake-up time in a simple and intuitive way.

### 3. Working with Dates
Explore `DateFormatter` to format dates and times for display, and calculate time differences to help determine sleep schedules.

### 4. Training a Model with Create ML
Use **Create ML** to train a regression model that can predict the optimal bedtime based on user inputs.

### 5. Integrating Core ML
Integrate machine learning model into the app to perform on-device predictions based on the user’s input.

## How it Works
1. **User Input**: The user provides their desired wake-up time, sleep hours, and coffee consumption.
2. **Model Prediction**: The app uses a Core ML regression model to calculate the ideal bedtime.
3. **Result Display**: The calculated bedtime is displayed to the user in a readable format.
