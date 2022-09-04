# Identifying Hate Speech in Philippie Election-Related Tweets

Machine Learning Course Submission

See full report [HERE](https://github.com/mbdelaresma/hate-speech-identification-tweets/blob/main/FinalReport.ipynb)

![image](https://user-images.githubusercontent.com/71246479/188298679-8c5cbe15-3232-456e-8fee-4527b90fe96f.png)

# Executive Summary

Increased usage of social media, particularly during election seasons, has intensified political division and hate speech. In line with this, this project aims to build a model that automatically detects hate speech and to understand patterns of political hate speech in a local context.

We used a dataset from Cabasag et. al. of tweets scraped during the 2016 Philippine electoral campaign that are labeled as hate and non-hate speech. We cleaned and processed the data using various NLP methods such as TF-IDF. We then built various machine learning classifier models including linear, tree-based, and multilayer perceptron models and then performed hyperparameter tuning to arrive at the best model based on the accuracy metric and the corresponding runtime. The best model was then used to test another dataset made up of recently scraped and manually labeled tweets about the 2022 elections. Finally, we employed SHAP to understand the factors that contribute to hate speech on a global scale, and we also used another interpretability method, LIME, to interpret the results on a more local level.

Among the models built, Logistic Regression had among the best accuracies, with the shortest runtime. This same model trained on 2016 data was then used to classify tweets from the present election campaign season. Global and local interpretability were then used to derive real-world insights from the results.

Some of the key findings after interpreting the results are that netizens naturally use certain keywords and nicknames when bashing candidates, with their sentiments varying depending on the name of choice. Also, a common behavior found on specific candidates' supporters is that their hate tweets are also mostly directed to the other supporters rather than the opposing candidates themselves.

Political ads can also make or break a candidate's campaign as a negatively accepted ad is usually a cause of a huge volume of hate tweets online. Meanwhile, links to websites or external sources on a person’s tweet, depending on the election season, can be used to legitimately inform or could also be weaponized to use in hate mongering online.

To further improve the applicability of the model on future studies, it is highly recommended to use a larger 2022 election related dataset either for testing or retraining the model. The dataset is preferred to be balanced on hate and non-hate tweets. Labeling techniques such as semi-supervised learning can also be deployed to ease the difficulty of manual labeling

# Contributors

Baluyut, Margs

dela Resma, Marvee

Fernando, Toby

Lapid, Norman

Sy, Sharyl

Timajo, Gelo
