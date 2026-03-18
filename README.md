# Comparison of Ground Reaction Forces and Net Joint Moment Predictions: Skeletal Model Versus Artificial Neural Network-Based Approach 

<p align="center">

Recurrent Neural Networks to predict ground reaction forces and lower limb net joint moments from kinematic data in running.

## Requirements

- Python version 3.11.0.
- Tensorflow version 2.15.0 or higher.
- Numpy version 1.16.2 or higher.
- Pandas version 2.2.0 or higher.

---

## Instructions

- Prepare the input data. Input data are compose for the hip, knee and ankle flexion and hip abduction and rotation joint angles. Input data should be time normalized (101 data points) and scaled about the maximum joint angle value.
- Input data can be storage in a .csv file with one kinematic input variable per column. 
- Load the appropiate RNN to predict the desired kinetic variable.

<br>

See the example [Python code](https://github.com/JuanCS96/Running_Biomechanics_ANN/blob/main/RNN_Predictions.py) to perform predictions.

If you use this code, please cite the article associated with this study:
- Cordero-Sánchez J, Bazuelo-Ruiz B, Pérez-Soriano P, Serrancolí G. Comparison of Ground Reaction Forces and Net Joint Moment Predictions: Skeletal Model Versus Artificial Neural Network-Based Approach. J Appl Biomech. 2025 Apr 9;41(4):290-303. [doi: 10.1123/jab.2024-0113](https://doi.org/10.1123/jab.2024-0113)
