# Capstone_Project_On_Netflix_Movies_And_TV-Shows_Clustering

## **Abstract:**

Netflix is a corporation that handles a big library of TV series and films that can be seen online at any time. Because consumers pay a monthly fee to access the platform, this business is profitable. Customers can, however, terminate their memberships at any moment. As a result, the company must keep consumers interested in the platform and not lose them. This is where recommendation systems come into play, as offering useful ideas to consumers is critical.

## **Introduction :**

Netflix's recommendation system contributes to the company's popularity among service providers by increasing the number of items sold, offering a diverse selection of items, increasing user satisfaction and user loyalty, and providing a better understanding of what the user wants. The user will thus be able to make better judgements from a large range of movie products. Netflix is the world's biggest Internet television network and the most-valued largest streaming service, with over 139 million paid customers (total viewer pool -300 million) spanning 190 countries, 15,400 titles throughout its regional libraries, and 112 Emmy Award Nominations in 2018.Netflix's incredible digital success story would be incomplete without mentioning its recommender systems that emphasise personalisation. There are various ways to generate a list of recommendations based on your choices.

## **Objective:**

Netflix Recommender suggests Netflix films and TV series based on a user's preferred film or television show. These recommendations are made using a Natural Language Processing (NLP) model and a K-Means Clustering methodology. These models produce recommendations based on information about films and TV shows such as storyline descriptions and genres. The goal of this project is to gain a better understanding of recommender systems and to design a model capable of Clustering on comparable material by matching text-based features. Consider how Netflix creates algorithms to personalise content depending on user likes and behaviour.

## **Data Description:**

The dataset provided contains 7787 rows and 12 columns.
The following are the columns in the dataset:
●	Show id: Unique identifier of the record in the dataset

●	**Type:** Whether it is a TV show or movie

●	**Title:** Title of the show or movie

●	**Director:** Director of the TV show or movie

●	**Cast:** The cast of the movie or TV show

●	**Country:** The list of the country in which a show/ movie is released or watched

●	**Date added:** The date on which the content was onboarded on the Netflix platform

●	**Release year:** Year of the release of the show/ movie

●	**Rating:** The rating informs about the suitability of the content for a specific age group

●	**Duration:** Duration is specified in terms of minutes for movies and in terms of the number of seasons in the case of TV shows

●	**Listed in:** This columns species the category/ genre of the content

●	**Description:** A short summary about the storyline of the content


## **Tools Used:**

The whole project was done using python, in google Collaboratory. Following libraries were used for analyzing the data and visualizing it and to build the model to predict the Netflix clustring 
•	**Pandas:** Extensively used to load and wrangle with the dataset.

•	**Matplotlib:** Used for visualization.

•	**Seaborn:** Used for visualization.

•	**Nltk:** It is a toolkit build for working with NLP.

•	**Datetime:** Used for analyzing the date variable.

•	**Warnings:** For filtering and ignoring the warnings.

•	**NumPy:** For some math operations in predictions.

•	**Wordcloud:** Visual representation of text data.

•	**Sklearn:** For the purpose of analysis and prediction.

## **Reference:**

*  https://towardsdatascience.com/silhouette-coefficient-validating-clustering-techniques-e976bb81d10c#:~:text=Silhouette%20Coefficient%20or%20silhouette%20score%20is%20a%20metric%20used%20to,each%20other%20and%20clearly%20distinguished.&text=a%3D%20average%20intra%2Dcluster%20distance,each%20point%20within%20a%20cluster.
*  https://machinelearningmastery.com/clustering-algorithms-with-python
*  geek for geeks
*  https://www.kdnuggets.com/2020/04/dbscan-clustering-algorithm-machine-learning.html
*  https://www.kdnuggets.com/2020/08/content-based-recommendation-system-word-embeddings.html
*  Chatgpt





