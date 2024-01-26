# Spam Email Detector

### Project Overview

The project aims to classify SMS messages as spam or non-spam using a dataset collected from Kaggle. The initial steps include loading the dataset, cleaning 
it by removing unwanted columns, null values, and duplicate rows. Exploratory Data Analysis (EDA) was performed using NLTK, Seaborn, and Matplotlib. 
The data preprocessing steps involve converting text to lowercase, tokenization, removing special characters, eliminating stop words and punctuation, and applying stemming.


### Model Training:
trained with many models mainly on :
Gaussian Naive Bayes (gnb)
Multinomial Naive Bayes (mnb)
Bernoulli Naive Bayes (bnb)
The selected Multinomial Naive Bayes model (mnb) achieved the following results on the test data:

Accuracy: 97.87%
Precision: 93.28%



### Conclusion and Future Work:
The Multinomial Naive Bayes model performed well with high accuracy and precision, indicating its effectiveness in classifying 
spam SMS messages. In the future, further optimization, hyperparameter tuning, and the exploration of other advanced models could be considered to enhance the model's performance. 
Additionally, monitoring and updating the model with new data will contribute to its ongoing reliability.

<img width="1462" alt="Spam Mail" src="https://github.com/nandhini799/Spam_email_detector/assets/153508488/ab566c76-fad5-4253-ae8c-48558d8d3b76">
