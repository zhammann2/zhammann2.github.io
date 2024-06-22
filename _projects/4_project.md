---
layout: page
title: IT Ticket Prioritization
description: Is there a better process than FIFO? How we found out!
img: assets/img/ticket.png
importance: 3
category: work
---

This project was completed during the summer of 2023 while I was working as a Software Development Intern in Kiewit Technology Group.

IT tickets are the bane of many peoples' existence when it comes to receiving help in a corporate setting. While many systems work on tickets in the order that they are submitted, I was provided some time to research and design an algorithm that might be able to help the process which is frustrating for so many workers.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/ticketing.png" title="IT ticketing" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/scikit.jpg" title="Scikit Learn" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/bayes.png" title="Naive Bayes" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    To explore aspects of tickets that might be indicative of their elevated importance, I was able to utilize Naive Bayes and several other Machine Learning techniques provided with ready-to-use implementation by Sci-Kit Learn.
</div>

After some exploratory data analysis, I was able to identify several factors that affect the likelihood of receiving a negative survey review after ticket completion. Priority was elevated for ticket submitters that were new to the company, had high positions within the company, and to specific types of tickets that tended to have greater sensitivity to completion time. The final product was a python script that was able to pull all open tickets and give suggestions on what tickets should be completed first in order to ensure the highest level of employee satisfaction.

If you have any questions about my experience working on this algorithm, please contact me via email.