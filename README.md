# Google-Brain---Ventilator-Pressure-Prediction-Keggle-proyect

This is the notebook I worked on to submit my first kaggle competition: Google Brain - Ventilator Pressure Prediction.

All the information and data about the competition is available in https://www.kaggle.com/c/ventilator-pressure-prediction. 

The competiton is a regression task where the objective is to accurately predict values of a variable representing the airway pressure measured in the respiratory circuit, having 7 features to deal with it.

I worked on a single jupyter notebook, and with this proyect I put into practise some theoretical concepts I learned about deep learning models to deal with sequential data.

I trained all the models using a colab free gpu, so I could not make very complex models, but I think that I completed my objective of putting those concepts into practise.

## Notebook structure:
- The first section of the notebook is about importing data, and making an initial recognition of the dataset.
- In the second section (Modelization section) I firstly tried some simple ML and DL models, and then I worked on optimizing these models increasing complexity. Finally I tested the best models.
- In the last section I worked on training the models with the whole train dataset, and making predictions to submmit with the test dataset.

## Notes:
- I wrongly supposed that the score metric was the mean squared error, and after a while I found out it was the mean average error, that is why all the tentative models have mse like the loss function, and then it changes to mae.
