# space-hospitality

![Blastoff](/figures/image_blastoff.jpg)

# Natural Language Processing and Sentiment Analysis of the Interstellar travel industry

**Authors**: [Fennec C. Nightingale,](mailto:fenneccharles@gmail.com) & [Matthew Lipman](mailto:matthewrlipman@gmail.com)

## Overview

###### "It's a fixer upper of a planet, but we can make it work." -Elon Musk

There is a huge arena of both positive and negative discussions about space. To ensure that the leading businesses in the interstellar travel industry drive revenue, they’ll need to create a huge demand for and positive discussion around this currently unknown and unexplored industry. This project takes into account the discourse around the space travel industry by analyzing over two million Tweets scraped from Twitter and over two hundred thousand dive YouTube comments from over two hundred different YouTube videos to better understand the sentiment around the most popular words used to discuss the space travel industry. With millions of different statements published by Twitter and YouTube users online and a number of features and attributes about each statement, this dataset provides a strong basis to illustrate what words are used to describe space travel and classify how those words are used in the context of them having an opinion. By understanding, analyzing, and modeling the data, we are able to classify text into three different clusters with with XX.X% accuracy. By accurately classifying this text, we can best inform the industry leaders the way to most appropriately and successfully market space travel to the Twitter and YouTube communities, and beyond.

![MostCommon](/figures/fig_histogram.png)


## Business Problem

The interstellar travel industry is a gold mining waiting to have its gold rush. The wealthiest and most successful companies are investing in tremendous resources to create a new way to the people of the world to travel: Interstellar Travel

With this impending bounty waiting to be explored, the industry still has a tremendous gap to cover with many unanswered questions that the public will require in order to be comfortable spending their money on traveling to space and investing in the companies that dedicate their time and resource to providing this soon-to-be-real service. 

![WordCloud](/figures/fig_wordplot.png)


The word cloud above displays the most commonly used nouns found in the corpus of 3.58 million nouns. As you can see, these words hold substantial relevance and importance. But to dig deeper, our study’s guiding question gets at the significance and sentiment of these meaningful words. Through this research and development, I will be answering/addressing the following questions:
<ol>
  <li> How do the Twitter and YouTube communities talk about space?
  <li> Can sentiment around space travel be divided into distinct clusters representing distinct and differing sentiment?
  <li> How can an understanding of the lexicon of words used to describe space travel help inform future space travel industry leaders how to most effectively market space travel?
</ol>

The clustesr we created aims to classify sentiment into three distinct buckets. The model we created aims to be able to classify whether or not a statement is positive, negative, or neutrals.


## Data

We dug into the online discourse around the subject of space travel. Specifically, our scope of analysis looks at both Twitter and YouTube as platforms by which people converse and pontificate about the industry. We began our work by applying for both Twitter and Google’s Application Programming Interface to gain the ability to acquire recent Tweets and YouTube comments along with a few of their important features beyond the text itself such as the favorite count, likes, and repost count. We scraped over two million tweets about space with a focus on travel/tourism and over two hundred thousand comments from over two hundred YouTube videos through the months of March and April 2021 all pertaining to interstellar travel--whether it be NASA’s recent rover landing to Mars, SpaceX’s launches, or discussion about the future potential businesses and missions yet to occur on our moon, Mars, and beyond. After preprocessing and stripping down our text down to base words, we ended up with about half a million unique text pieces.


## Methods

This classification modeling project is in accordance with the CRISP-DM method. After acquiring the data, natural language processing requires certain important preprocessing techniques on the text such as addressing casing, punctuation, stop word removal, lemmatization, tokenization, as well as a number of normalization techniques on the other features. By preprocessing this data, we are able to reduce randomness and dimensionality. Arguably the most significant part of this study was clustering. Since we are working with unsupervised data--meaning data that has not been predetermined as having a specific sentiment--none of our tweets and youtube comments have any predetermined classification. With that said, being able to label and map associations between words is the first major step before identifying and modeling the sentiment of said word. Each subsequent clustering technique had an iterative approach using a number of techniques to address a variety of modeling obstacles such as class imbalances, dimensionality reduction, and inertia. By successfully clustering the text, we were able to streamline the modeling process, and identify a number of evaluation metrics to best analyze our model and selected one metric to strive to minimize classification inaccuracies.


## Results

![Clusters](/figures/fig_silhouette05.png)


We used a number of different clustering techniques with a series of evaluation metrics to best identify the right cluster. The goal here is to find the ideal number of classifications to best describe the sentiment. Instead of forcing the sentiment into a binary classification of positive versus negative, we looked into creating more of a gradient of sentiment. Using a number of techniques, we were able to pin down THREE CLUSTERS [SUBJECT TO CHANGE] to best categorize the text.

![Elbow](/figures/k6.png)

The most effective clustering technique we used to classify the text had the following attributes:
<ol>
  <li> Three clusters
  <li> Inertia = XXXXX
  <li> Imbalance Mean = | Imbalance Median =  
  <li> Hyperparameter tuning to optimize the model's recall and reduce model overfitting
</ol>

We used a Naive Bayes Classifier to model our finding and found that XX.X% of the text is accurately predicted by the model.

[INSERT MATRIX HERE]

In addition, this Naive Bayes Classifier illustrates:
<ol>
  <li> Coming soon...
  <li> Coming soon...
       
![AdvanceImage1](/figures/wordcloud_cluster0.png)
    
  <li> Coming soon...
  
![AdvanceImage2](/figures/tfidf.png)
  
  <li> Coming soon...
</ol>

By honing in on accuracy, the model ensures that we capture a holistic approach where a both false positive and false negative misclassifications are taken into account. By focusing on accuracy, this model avoids both types of errors.

## Conclusions

This analysis leads to three recommendations:

- **ONE.** Coming soon...
- **TWO.** Coming soon...
- **THREE.** Coming soon...

### Future Work

Further analyses could yield additional insights to substantiate behavior leading to more effective marketing.

- **Incorporate more social media platforms:** We recognize that our current study involved the Twitter and YouTube communities, which may have their own biases and perspective. By bringing in more platforms such as Reddit, Facebook, and Instagram, this study will improve in comprehensiveness tremendously.
- **Time series analysis:** Looking at change of space sentiment after major events could help companies best adapt to substantial changes in requirements to the safety and understanding of how customers will travel. In addition, it will be effective to study how specific words have changed in sentiment over time to forecast how certain features may become more important in the future as well as products to invest more/less in for future development.


## For More Information

See the full analysis in my <a href="https://github.com/Fennecnightingale/space-hospitality/master/Insert%20Name%20Here.ipynb">Jupyter Notebook</a> or review my <a href="https://github.com/Fennecnightingale/space-hospitality/blob/master/Presentation.pdf">Presentation</a>.

For additional info, contact us here: [ Fennec C. Nightingale,](mailto:fenneccharles@gmail.com) & [ Matthew Lipman,](mailto:matthewrlipman@gmail.com)

## Repository Structure

```
Coming soon...
