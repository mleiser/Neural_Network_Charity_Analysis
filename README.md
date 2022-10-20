# Neural_Network_Charity_Analysis
## Overview of the Analysis
### Purpose
  The purpose of this assignment was to determine if it was possible to make a neural network that can predict if applicants would be successful if funded. This is done using the a Deep Neural Network to predict and measure accuracy. I also attempt to optimize the neural network for better accuracy later.  
## Neural_Network_Charity_Analysis Results
  -Preprocessing 
  --The target for the model is the IS_SUCCESSFUL column which is the main focus on training the data to predict
  --Features of the model are AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, INCOME_AMT, and SPECIAL_CONDIDERATIONS.
  --Variables that should be removed are EIN and NAME
  -Compiling, Training, and Evaluating the Model
  --I ended up going with 2 layers with 20 and 30 neurons respectivly all done using relu activation. I chose these since it seemed like a good baseline to start
  ![image](https://user-images.githubusercontent.com/46801182/196838492-b2fc5b8e-4e3e-43c4-aa85-f1dabcf102d2.png)
  --I was not able to achieve the target model performance of 75%
  ![image](https://user-images.githubusercontent.com/46801182/196838564-18548015-1956-4ad7-9c15-cfb38e4a44f1.png)
  --To optimize the neural network, I increased the number of layers to 3, increased the number of neurons by a large amount, changed the activation to tanh and increased the number of epochs to 150. Ulitmately, it didn't help.
  ![image](https://user-images.githubusercontent.com/46801182/196838838-c53f898d-afc8-4ae3-a574-78e39d0ccb29.png)

## Neural_Network_Charity_Analysis Summary
  When looking at the results of the neural network, it's clear that my attemps did not succeed in reaching 75% accuracy. This could be due to a number of issues such as not enough bins, outliers in the data, or the data was overfit. A different model that could be used instead could be the random forest due to the speed at which random forest can train the data compared to deep learning. This could allow for more optimization to be done due to the lower amount of time spent training the data.
