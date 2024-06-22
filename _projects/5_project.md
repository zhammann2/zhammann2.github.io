---
layout: page
title: Twitter Sentiment Analysis
description: How we correlated public events with Twitter Sentiment
img: assets/img/sentiment.jpg
importance: 3
category: school
---

This was completed as a final project for my sophomore year Machine Learning course.

Tasked with investigating and using a technique common in machine learning, my group decided to focus on sentiment analysis. Sentiment analysis is the practice of quantifying emotion within natural language and we decided to turn to twitter data for a large set of free text to analyze. 

Specifically, we focused on three areas. Donald Trump's tweets, Elon Musk's tweets, and a large set of tweets from 2019. We decided to calculate the average montly sentiment of the individual's tweets and try to link them to public events during that time period. For the large set of tweets from 2019, we focused on calculating sentiment for all tweets to try and understand the rough distribution of sentiment on twitter.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/vader.jpeg" title="Darth Vader" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/py.jpg" title="Python Programming Language" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/scale.png" title="Sentiment Scale" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    To complete our sentiment analysis, we utilized the Vader Sentiment python package. We were able to write scripts on data sets that we obtained from Kaggle, and display our findings and their relation to public events using the MatPlotLib python package.
</div>

Completed for a research presentation, we compiled our findings and visuals onto a research grade poster. Results were interesting, with a fairly clear link between sentiment on twitter and controversial current events that related to the individuals. We discussed the limitations of rule based sentiment classifiers, as well as possible future uses of the technology. We were also surprised by the sentiment distribution of a normal twitter data set, with the vast majority of tweets being neutral as opposed to containing highly positive or negative sentiments.

If you have any questions regarding my experience and involvement on this project, please contact me via email.