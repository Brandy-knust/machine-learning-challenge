# Machine-Learning-Challenge

## Training computers to Find New Exoplanets

### Technologies Used
* Jupyter/Python
* Neural Networks
* Linear/Logistical Regressions
* Decision Trees/Random Forest
* KNN/SVM
* Grid Search/HyperParameter Tuning

## About the Challenge
Given large amounts of data collected from satellites, I trained models to classify possible exoplanets. <br> I was able to train the models with a set of collected data, and then find the best model to be able to most<br>accurately classify the possibility of a future set of data as being an exoplanet or not. 

# Best Models
While we did not have to test as many models as I did, I tested seven different models to get the best possible<br> results. Also, I researched the data points to determine some of the information to be able to make better<br> decisions on the ability to accurately predict the exoplanet. From there, I was able to use the research, coupled with the<br> importances ranking (the importances by itself did not get equal results), to select the features that would<br> come up with the best results. At that point, I put those features through seven different models, using the grid<br> search on all but the neural networks, to get the most accurate model possible. <br>

Through these efforts, my best model, Random Forest, was able to predict with 89.9% accuracy. This seems to be <br>higher than most of the other models could even compare to since most were in the 70%-80% range. One downside <br>was that after running a grid search, the results went down, not up, so I may need to find different parameters to  <br>tune instead. 

The exception to that was the Deep Learning model. It was able to get an average of 89.4% accuracy. Most others <br>in my cohort were not able to get such accuracy in their models, and I think a large part of the reason my <br>numbers were so high go back to the fact that I put the time into researching the dataset to begin with, really <br>understanding what would impact and what would not impact the results more. 