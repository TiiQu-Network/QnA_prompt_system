# QnA_prompt_system
Improve the efficacy and correctness of the QnA questions.

Guide to Repo

# Keywords approach 

- This approach takes into accounts the pre-defined keywords to see if they can help predict the labels. The results were not good as the pre-defined keywords did not help predict the labels

# K-Means(Clustering approach)

- This approach used k-means clustering. The clusters were then used to predict if they could help predict the labels by comparing it with pre-defined labels.
- This approach limitation was that science and tech words were overlapping into other clusters.
- This approach did not produce adequate results aswell.

  # Supervised Learning approach

  - This approach used machine learning models to predict labels.
  - This approach shows promise as logistic regression had higest accuracy achieved so far at 73%.
  - This approach should be pursued as showing good signs.
 
  # Data imbalence

  -  This repo uses randomoversampler and setting the parameters of the models to balenced to counter the data imbalence issue
  -  This shows that these methods can help models, as it allows them to take into account the data imbalence issues in the dataset
