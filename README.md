# My Travel Recommender System

## Overview

Content-based filtering is a prominent information retrieval technique utilized in various domains, such as recommender systems and personalized content delivery. It involves the analysis and evaluation of relevant features and characteristics present within the content items themselves to facilitate accurate and targeted recommendations or filtering.

Content-based filtering offers several advantages, including the ability to provide recommendations in the absence of user history or community data, the potential for serendipitous discovery of new items based on content similarity, and reduced dependency on the availability and quality of user ratings or reviews.

## How to Run the Notebook

To run the notebook of our recommendation model run the following command:
```bash
git clone https://github.com/Project-Capstone-Bangkit-2023/myTravel-model.git
```
and open the `recommender.ipynb`.

## Recommendation Model

For the recommender system used in myTravel App we choose the content based filtering method. Our team is utilizing Tensorflow for the implementation and TFJS for the deployment to cloud.

Here is the summary of our model,

![Model Summary](/images/summary.jpg "Model Summary")

With this model and after training we get this accuracy,

![Model accuracy](/images/accuracy.jpg "Model accuracy")

and loss,

![Model loss](/images/loss.jpg "Model loss")
## Dataset

The dataset we use for the recommendation system is in [here](https://www.kaggle.com/datasets/aprabowo/indonesia-tourism-destination).