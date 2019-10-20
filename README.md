# Dataset
This repository contains the dataset used for the project. The dataset is a collection of 26 classes with 40 samples for each class.

# Data Sample Structure
Each sample of a class has 50 lines, each corresponding to the 50 timesteps the sensors were sampled at. Each timestep contains 11 sensor values 
- accelerometer_x
- accelerometer_y
- accelerometer_z
- gyroscope_x
- gyroscope_y
- gyroscope_z
- flexsensors(5)

## Naming of the files
```
classLabel-timestamp.csv
```