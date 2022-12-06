

################  Resume of our Work on Obesity Dataset ############



############################  First Part DataViz ############################

In the Obesity_viz Jupyter Notebook, we try to understand our Dataset, the sens of each variable,
 possible coorelations between some variables, but also  bias in the dataset. For instance, 
the age distribution doesn't look to be representative. Thanks to this part, we decided to focus on 
predicting and understanding the causes of Obesity. When looking at the data, we understood it's difficult to 
separate causes from consequences of Obesity.

############################  Second Part Preprocessing and IA ############################

In the AI_Obesity_Project Jupyter Notebook, we encode the best way possible each colum 
of our dataset and scale them when possible. Then, we applied multiple algorithms to try to 
predict the level of obesity of each individuals. The RandomForest algorithm was excellent with more than 0.95 accuracy.
However, due to the data, our model is probably highly biaised for older people. 
We also looked at which variables are the most significant to make those predictions.
At the end, we save our model and the preprocessing to use it in the next part.

############################  Third Part API ############################

We use a virtual environnment and the Djando module to built an easy to use 
and to deploy API predicting the level of obesity. The API is under the .zip file
and the requirements.txt file contains all packages necessary to make the API work in a 
virtual environnment.

Note : The API is under a .zip file because the model take too much memory for GitHub(26Mo).
Main Documentation for the API : https://towardsdatascience.com/productionize-a-machine-learning-model-with-a-django-api-c774cb47698c

############################  Conclusion   ###########################

Thnaks to this work, we learned to work in group on a very specific issue, train and 
deploy a model in a virtual environnment. Even if, we cleary found that family inheritance is one major factor of Obesity, 
our Conclusions are that is difficult to assess the real causes of Obesity.
Moreover, it's difficult to apply Machine Algorithms on ethical cases like this one and to differentiate
causes from consequences of an issue.



