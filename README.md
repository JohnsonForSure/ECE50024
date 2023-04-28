# ECE50024 Machine Learning Final Report 
### The L2R.ipynb file is a reimplementation of the research paper "Learning to Reweight Examples for Robust Deep Learning" by Ren et al. (2018).
### Setting: The implementation is based on Google Colab
### Experiment Design: To examine the effectiveness of implementing the Reweighted Algorithm, we conducted experiments to evaluate its impact on three different scenarios: 1) class imbalance 2) noisy data 3) different sizes of meta-data
For both the class imbalance and noisy data scenarios, we compared the performance of the LeNet with Reweighted Algorithm (L2R) and without (Baseline). We also analyzed the effects of hyperparameters, including the proportion of the dominant class, the variance of the noise, and the size of the meta data. Our experiments aimed to determine the extent to which the Reweighted Algorithm can improve the performance of Baseline model on custom datasets with varying degrees of class imbalance, noise, and meta data size.
### Some Result for Class Imbalance
![Fgiure 2](https://user-images.githubusercontent.com/43269704/235262843-e6cb89c2-56f7-4848-ac61-4623baadb18c.png)
