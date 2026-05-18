# LEAF &amp; CROP
##Latent encoding of agricultural features and context-based recommendations for optimised planting
Deeplearning project for the IACOMM class at the UPV.

## Objective
Implement and train an autoencoder to create representations of soil and weather conditions in a latent spae, which are then being used for the classification of most suitable crops. With this project, we want to simplify a change in agricultural methods: Planting crops depending on the given conditions of an area, not adapting the conditions to suit a specific kind of crop to be planted.

## Includes
### [] Analysis of dataset
[] Missing values  
[] Format  
[] Number of classes  
[] Necessary data preparation  
[] Research possible augmentation  
### [] Data preprocessing
[] Possibly transformation  
[] Data normalization  
[] Create Dataset & Dataloader -> get_dataset  
[] Split up into training-, validation- & test-set  
[] Apply augmentation  
### [] Training loop
[] Setup training loop with optimizer and criterion (loss function)  
[] Classification & regression in one training (added to one lost-function for example or just parallel)? Might be worth a try  
[] Evaluation of model  
### [ ] Model(s)
[ ] Create architecture  
[ ] Define hyperparameters (use configuration), flexible architecture  
[ ] Adapt training & evalation if necessary  
[ ] Autoencoder with classification head  
### [ ] Hyperparameter optimization 
[ ] Bayesian Optimization  
