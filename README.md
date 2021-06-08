# About Myself
I am Jiayang (David) Xu, a PhD candidate at the University of Michigan. My research ranges of PCA-based Model Order Reduction (MOR) to deep-learning-based simulations of physical systems. 

This repo shares the results for some of my work. It would be my greatest pleasure if you find some of them interesting!

# Flow Simulation with Conditionally Parameterized (CP)-GNN
Rollout prediction of complex flow on irregular meshes for hundreds to thousands of steps.
## Reacting Flow
Ground truth data taken from a public dataset (https://afcoe.engin.umich.edu/benchmark-data) for a 2D rocket injector. A highly irregular mesh is used.

![Predicted CH4 mass fraction](https://user-images.githubusercontent.com/24285886/121130524-83b07e00-c7fc-11eb-9132-4c01c9ddfde5.gif)
![Predicted temperature](https://user-images.githubusercontent.com/24285886/121130533-8612d800-c7fc-11eb-93fc-f8fb367e4bf9.gif)


## Flow Over Cylinder
A classic test case. Ground truth generated using an openfoam tutorial (https://wiki.openfoam.com/Vortex_shedding_by_Joel_Guerrero_2D).

![Predicted velocity magnitude](https://user-images.githubusercontent.com/24285886/121128545-8eb5df00-c7f9-11eb-98e5-4aefa5020dd3.gif)
![Predicted pressure](https://user-images.githubusercontent.com/24285886/121128550-91183900-c7f9-11eb-8608-00a1695c3a76.gif)




# Super-Resolution with CP-MLP
Predicting high-resolution flow images from low-resolution ones. 
![super_resolv](https://user-images.githubusercontent.com/24285886/121130087-e35a5980-c7fb-11eb-90b8-f2f0259045b1.png)

<!-- # Parametric Time-Series Prediction with Multi-Level Autoencoders

# Point Cloud Perception
# Gesture Classification
# Protein Property Prediction -->
