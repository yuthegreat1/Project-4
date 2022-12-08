Many risk factors have been determined by scientists and doctors to contribute to the hospitalization or death of COVID-19 patients. Through the use of the dataset at the following link, we aim to apply machine learning to visualize and understand these risk factors. https://www.kaggle.com/datasets/meirnizri/covid19-dataset 

Our plan was to clean up the data in a Jupyter notebook using Pandas. From there, we would train various machine learning models and evaluate them for their accuracy. We would utilize neural network models and a random forest model. We chose to utilize both MatPlotLib and Tableau to incorporate visualizations into our final presentation. The purpose of this analysis was to determine an individual’s likelihood of encountering complications from COVID-19. Specifically, we wanted to determine if there was a way to predict a patient’s likelihood of being hospitalized or dying as a result of COVID-19. 

Using the above plan, we developed various models.

The random forest classifier model resulted in a final accuracy of about 90.5%. The neural network models predicting death and hospitalization had final accuracies of 93.3% and 90.4% respectively.

Through the use of our various models, we aimed for a prediction rate of 95% or greater, as to make the models viable for use in a medical setting. Although attempts were made to fine tune our models to reach this goal, we saw minimal improvement using a Keras tuner. Moving forward, further optimization of the models would require greater resources in computing power, more time, and further refinement of our parameters.
