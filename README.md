# my_projects
Real-world data analysis

## [Classification of Sign Language](https://www.kaggle.com/kotarosonoda/sign-language-cnn)
- Abstract: The pictures of sign language are classified into 24 groups using a deep neural network model which consists of convolution layers, max pooling layers, dropout layer, and densely-connected layer. In order to make the model robust against slight differences such as fist angles, hand position, and zoom level, data augmentation is performed. With this method, 99.5 % accuracy is achieved for a test dataset. 
- Mathods: Image data analysis, Convolutional neural network, Data augmentation

<img src="https://github.com/ksonod/my_pictures/blob/master/sign_language.png" width="500px">      


## [Prediction of a Heart Disease Based on Medical Data](https://github.com/ksonod/my_projects/tree/master/heart_disease)
- Abstract: Using [medical data](https://www.kaggle.com/ronitf/heart-disease-uci), I predicted whether patients have a heart disease. At first, it was shown that K-fold mean-target encoding for categorical features and standardization of numerical features improve the prediction accuracy and logloss value for the test dataset when using LightGBM. In addition to the LightGBM (LGBM), random forest (RF), neural network (NN), and logistic regression (LR) models were also trained to make a prediction. The predicted probabilities obtained from these models were used to construct a new feature matrix and fed to a logistic regression model to make a final prediction. This ensemble learning technique, called stacking, improved the prediction accuracy, log loss, and F1 score when LGBM, RF, and LR are used.
- Mathods: log transformation, standardization, mean-target encoding, K-fold cross validation, lightGBM, random forest, neural network, logistic regression, ensemble learning, stacking
<img src="https://github.com/ksonod/my_pictures/blob/master/entire_process.png" width="700px">      



## [Diversity of nationalities in Lausanne Marathon 2018](https://github.com/ksonod/my_projects/tree/master/LausanneMarathon)   
- Abstract: The diversity of nationalities of Lausanne Marathon participants is revealed. It is found that 10490 runners are from 119 countries and that 42 % of them are non-Swiss runners. The analyzed results are summarized as a Tableau dashboard, which enables us to interactively explore interesting findings.
- Results: [Tableau Public](https://public.tableau.com/profile/kotaro.sonoda#!/vizhome/LausanneMarathon/dashboard)  
- Methods: Web scraping, data cleaning, data visualization (matplotlib, folium, Tableau), SQL
<img src="https://i.imgur.com/cOdHOFE.png" width="500px">      

## [Japanese restaurants in Zurich](https://github.com/ksonod/my_projects/tree/master/JapaneseRestaurantsInZurich)
- Methods: API (Google Map, foursquare), data cleaning, interactive map (folium), SQL, clustering
<img src="https://i.imgur.com/0WobSrz.png" width="500px"> 
