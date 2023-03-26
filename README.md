# AWS
Employee Salary Predictions Using AWS Sagemaker Linear Learner
Project Overview: The objective is to predict the employee salary based in the number of exprience.


Preprocessing:
1. Data should be suffled before training.
2. Data has to be normalized. (feature scaling is offered by AWS)

Training:
1. Linear Learner uses stochastic gradient descent
2. Optimizer: Adam, AdaGrad, SGD
3. Hyperparameters: Learning rate, epochs, batch size, predictor_type, etc.,
4. Regularization to avoid overfitting
5. Multiple models could be optimized in parallel 

Validation:
Evaluate the model based on MSE, MAE, cross entropy loss, absolute error

Input/Output Data:
Linear Learner supports 
      (Input Data),
      1. RecordIO-wrapped protobuf 
      2. Text/SCv (I column to be the target label)
      3. File or pipe mode
      (Output Data),
      1. Json
      2. x-recordio-protobuf
      3. text/csv
      
EC2 Instances: Single CPU is used for this project.

