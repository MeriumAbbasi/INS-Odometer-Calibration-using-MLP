# INS-Odometer Integrated Navigation Error Correction using MLP

This project aims to correct the residual errors in the integrated navigation solution of Inertial Navigation Systems (INS) and Odometer (ODO) by using a Multilayer Perceptron (MLP). The GPS velocity is used as a reference to cater to errors in the INS-ODO integrated solution. Additionally, accelerometer, gyroscope, and heading data are included as extra features for improved accuracy.

## Table of Contents

- [Introduction](#introduction)
- [Data](#data)
- [Model](#model)
- [Usage](#usage)
- [Results](#results)
- [Dependencies](#dependencies)

## Introduction

Inertial Navigation Systems (INS) and Odometer (ODO) based navigation systems are commonly used for various applications. However, these systems tend to accumulate errors over time, which can degrade the overall navigation accuracy. This project leverages a Multilayer Perceptron (MLP) to correct the residual errors in the INS-ODO integrated navigation solution by using GPS velocity as a reference.


## Data

The dataset includes:
- Accelerometer data
- Gyroscope data
- Heading data
- INS-ODO integrated navigation solution
- GPS velocity (used as the reference)

The data was collected from various trajectories and split into training and testing sets.

## Model

A Multilayer Perceptron (MLP) was used to model and correct the residual errors. The model takes in accelerometer, gyroscope, heading data, and the INS-ODO integrated navigation solution as inputs and outputs the corrected navigation solution.

## Usage

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/ins-odo-navigation-correction.git
   cd ins-odo-navigation-correction

## Results

The trained MLP model successfully reduced the residual errors in the INS-ODO integrated navigation solution, demonstrating improved accuracy across different trajectories.

## Dependencies

- Python 3.x
- numpy
- pandas
- scikit-learn
- tensorflow/keras
- matplotlib
- jupyter

