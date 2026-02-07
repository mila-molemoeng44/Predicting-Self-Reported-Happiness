# Predicting-Self-Reported-Happiness
This brief independent project aimed at extrapolating dataset features to predict self-reported happiness. The objection of this project was to build a neural network that would predict the target feature: self-reported happiness.

# Model Features
With my recent acquisition in the knowledge of how to create and optimize a neural network, I used the Keras API derived from the Tensorflow framework. In the process of optimiszing my model, I consiered the impact of the width and linear depth of the models, initially opting to make the model's layers as wide as I reasonably could and as reasonably linearly dense as I thought was necessary. Due to computing limitations and time constraints, the performance of the model was set to a standard that wouldn't compromise both the model's performance and the efficiency of the model. Early stopping was utilized with Mean Absolute Error being chosen as the regression metric. 

# Evaluating the MAE and The Limitations Behind Predicting Happiness
The MAE was a score of 2.24 and the base-line MAE was 2.5. This indicated to me that, although the MAE was higher than desired, the model was performing on the basis of learning valuable signal instead of noise, or at least a majority learninship of signal than noise. The computational limitations of predicting an emotion like happiness can also be seen as a real-world challenge that perhaps, models like this, could help in predicting for better health care solutions or mimic the real world and interpret more noise than valuable information. 




