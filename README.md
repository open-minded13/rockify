# 2023 Rockify — A Machine Learning Practice for Rock Music Sub-genre Classification | Python, Spotify Web API, scikit-learn, Random Forest

Rockify is a machine learning project that aims to classify rock music tracks into different subgenres, such as classic rock, punk rock, metal rock, etc. The motivation behind this project is to explore the potential of machine learning in music genre classification and to create a useful tool for music producers, streaming platforms, and music enthusiasts. The project uses various machine learning algorithms, such as random forest, decision tree, KNN, SVM, and logistic regression, to train and evaluate a model on a dataset of rock music tracks obtained from Spotify API. The project also provides a convenient query program that allows users to enter a song URL from Spotify and get the subgenre analysis result.

## Demo Photos

- We use a heatmap to see the relationship between different categories:
  
  <kbd><img src="https://github.com/open-minded13/2023_Rockify/assets/52095472/7278a68e-979d-4c2b-a68f-ea131a73a09f.png" height="600px"/></kbd>

- Rockify allows users to enter a song URL and will tell them the subgenre of the song:
  
  <kbd><img src="https://github.com/open-minded13/2023_Rockify/assets/52095472/d1184af4-fef9-44e9-9114-8236510d228d.png" height="100px"/></kbd>

## Installation
1. To install and run this project, you will need Python 3.7 or higher and the following libraries: pandas, numpy, sklearn, spotipy, seaborn, matplotlib. You can install these libraries using pip or conda. For example:

   `pip install pandas numpy sklearn spotipy seaborn matplotlib`

   or if you have installed Anaconda (which is one of the world's most popular data science platforms): 

   `conda install pandas numpy sklearn spotipy seaborn matplotlib`

2. You will also need to register a Spotify developer account and obtain a client ID and client secret. You can follow the instructions here: https://developer.spotify.com/documentation/general/guides/app-settings/

3. Then, you need to set the environment variables SPOTIPY_CLIENT_ID and SPOTIPY_CLIENT_SECRET with your credentials. For example:

   `export SPOTIPY_CLIENT_ID='your-client-id`
   
   `export SPOTIPY_CLIENT_SECRET='your-client-secret`

4. Finally, you can clone this repository or download the source code as a zip file.

   `git clone https://github.com/open-minded13/2023_Rockify`
   
## Results
The main result of this project is the random forest classifier model that achieved an accuracy of 0.6310 on the test dataset. This model outperformed other models such as decision tree, KNN, SVM, and logistic regression. The model was trained on 11 audio features (Danceability, Energy, Key, Loudness, Mode, Speechiness, Acousticness, Instrumentalness, Liveness, Valence, and Tempo) obtained through the Spotify API, as well as a manual classification tag (sub-genre generated from playlists).

The following table shows the accuracy scores of different models on the test dataset:

- Random Forest	0.6310
- Decision Tree	0.4599
- KNN	0.3209
- SVM	0.2834
- Logistic Regression	0.4332

## Discussion
The discussion section of this project provides an in-depth analysis of the results and the implications of this project for music technology. It also discusses some of the challenges faced, limitations encountered, and future directions for improvement.

Some of the main points discussed are:

- Why random forest is the best model for Rockify
- How random forest handles non-linear relationships and reduces overfitting
- How different models compare with each other in terms of performance and complexity
- How correlation analysis helps to identify redundant or irrelevant features
- How grid search helps to optimize hyperparameters for random forest model
- How Delphi technique can help to improve sub-genre labeling accuracy
- How feature selection can help to reduce dimensionality and improve efficiency
- How additional features such as lyrics or album art can enhance genre classification

## Conclusion
Rockify is a machine learning project that demonstrates the potential of using machine learning for music genre classification. It provides a useful tool for music producers, streaming platforms, and music enthusiasts to classify rock music tracks into different subgenres based on audio features obtained from Spotify API. It also provides a convenient query program that allows users to enter a song URL from Spotify and get the subgenre analysis result.

The project uses various machine learning algorithms such as random forest, decision tree, KNN, SVM, and logistic regression to train and evaluate a model on a dataset of rock music tracks. The project also performs data analysis, correlation analysis, feature importance analysis, model optimization, and result visualization.

The main result of this project is the random forest classifier model that achieved an accuracy of 0.6310 on the test dataset. This model outperformed other models in terms of performance and complexity. The model was trained on 11 audio features (Danceability, Energy, Key, Loudness, Mode, Speechiness, Acousticness, Instrumentalness, Liveness, Valence, and Tempo) obtained through the Spotify API, as well as a manual classification tag (sub-genre generated from playlists).

The project also discusses some of the challenges faced, limitations encountered, and future directions for improvement. Some of these include improving sub-genre labeling accuracy using the Delphi technique, reducing dimensionality and improving efficiency using feature selection, and enhancing genre classification using additional features such as lyrics or album art.

In summary, Rockify showcases the immense potential of machine learning in music genre classification. It provides a powerful tool for classifying songs into sub-genres of rock music based on audio features. It also provides valuable insights into how different machine learning algorithms work and compare with each other. As we continue to innovate and improve our model, we hope to empower music producers, streaming platforms, and music enthusiasts to make data-driven decisions that enhance the listening experience and create a more diverse and vibrant music industry.
