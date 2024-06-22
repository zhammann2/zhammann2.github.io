---
layout: page
title: Predicting the Euros
description: Who we will the 2024 European Championships?
img: assets/img/soccer.jpg
importance: 5
category: school
related_publications: false
---

This experience was my final group project for my junior year Machine Learning course.

The UEFA European Championships are a huge cultural sporting event in Europe, and are often a stage for incredible international soccer. We wanted to try our hand at using neural networks for game predictions, and we did just that using FIFA data and a Keras Neural Network.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/fifacard.jpg" title="Fifa player cards" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/euros.png" title="UEFA Euro's" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/network.png" title="Neural Networks" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    For inputs, we used player data from the FIFA videogame. We trained our model using match data from the top 5 European Leagues, and then predicted the Euros using the top 23 rated players for each participating country.
</div>

For training data, we used historical matches from the last three years in the Premier League (Britain), La Liga (Spain), the Bundesliga (Germany), Ligue 1 (France), and Serie A (Italy). Our input data was the player data for each team (23 players each), and an encoding for either a home win, draw, or away win as our target label. After training, our model predicted Belgium to taken home the first place at the Euros.

For any questions regarding my experience on this project, please contact me via email.