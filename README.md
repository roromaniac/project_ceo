# project_ceo

# Step-by-step Instructions for Use
1. Clone this repository.
2. Navigate to the root directory (.../project_ceo).
3. Run the following: `python train.py --dataset "MNIST" --optim "Adam"`
  3a. The choice of optimizers at the moment include "Adam", "SGD, "Adamax", "RMSProp", and "Adagrad".
      The optim argument is case sensitive.
      Additionally, the choice of "All" will train all of the optimizers at once. 
