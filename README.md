# fake_news_detection

In this project our aim is to use RNN and Attention layers, to approach the task of fake news detection. For the task we used the PHEME dataset.

The dataset can be downloaded here: https://figshare.com/articles/dataset/PHEME_dataset_for_Rumour_Detection_and_Veracity_Classification/6392078

This dataset contains a collection of Twitter rumours and non-rumours posted during breaking news. More specifically, it contain Twitter conversation threads associated with different newsworthy events including the Ferguson unrest, the shooting
at Charlie Hebdo, the shooting in Ottawa, the hostage situation in Sydney and the crash of a Germanwings
plane, and others.


The data is structured as follows. Each event has a directory, with two subfolders, rumours and non-rumours. These two folders have folders named with a tweet ID. The tweet itself can be found on the 'source-tweet' directory of the tweet in question, and the directory 'reactions' has the set of tweets responding to that source tweet. Also each folder contains ‘annotation.json’ which contains information about veracity of the rumour and ‘structure.json’, which contains information about structure of the conversation.

*Notice that for our task, fake news detection, we used only the source tweets classified as rumours in the dataset.*

In this repo you'll find the notebooks made for the project, but they are also accessible on Kaggle: https://www.kaggle.com/code/manuelcecerepalazzo/fake-news-detection

This work was realized for the course [Multidisciplinary Project] (https://polimdp.wordpress.com/) offered by Politecnico di Milano.
