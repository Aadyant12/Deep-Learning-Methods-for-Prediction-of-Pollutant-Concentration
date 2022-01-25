# Predicting-Pollutant-Concentration
_Done under the guidance of **Prof. Farnaz Hosseinpour - Desert Research Institute, University of Nevada, Reno**_

This project is aimed at predicting PM2.5 particle concentration over the state of Nevada, USA. 
For this project, the data (PM2.5 particle concentration over Nevada for the period 1999-2021) was collected from United States Environmental Protection Agency.
The fact that there is a yearly rise in the concentration during certain months of the year, forms the basis of this project.

PM2.5 Concentration in 2021 -->

![image](https://user-images.githubusercontent.com/62593634/150922619-ae78145c-0c69-4a53-a1be-39b223482921.png)

Sliding window approach was used to create training examples for our models wherein, prior time steps are used to predict the next time step. The number of previous time steps being used to make the prediction is called window size. Then, multiple types of neural networks including dense neural network, recurrent neural network and convolutional neural network were trained and tested in this project
