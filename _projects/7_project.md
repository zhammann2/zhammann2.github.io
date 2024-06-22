---
layout: page
title: Automated Dashboarding
description: Making tracking warehouse progress easier
img: assets/img/dashboard.jpg
importance: 5
category: work
related_publications: false
---

This project was completed during the summer of 2022 while I was a Data Analytics intern at MSI Express.

Dashboarding can be a fantastic way to glean measurable and actionable figures from large swaths of data. As a contract manufacturing company, MSI Express has a huge amount of data regarding machinery, product lines, and warehouse materials. My main project involved finding any machinery parts or components that didn't meet company standards regarding data entry, and providing warehouse managers with insights into how organized and up-to-standard their parts storage was. 

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/postgres.jpg" title="PostgreSQL" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/excel.jpg" title="Microsoft Excel" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/msi.jpg" title="MSI Express" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    In order to provide actionable insights to warehouse managers, I created an automated dashboard within Excel. With Excel, I was not only able to automate the updating of the service, but also create pivot tables to provide multiple levels of granularity to the data, as well as track total problems per site over time.
</div>

The dashboard was created in Excel using an ODBC connection to MSI's PostgreSQL server. This tool provided much needed clarity regarding organizational standards at each of the different sites in an effort to unify standards across the company. Automated notifications were also starting to be implemented to update managers via email on a weekly basis, but the internship concluded before the feature could be fully implemented. I also completed work within Tableau for smaller stakeholders during this process.

If you have any questions regarding my experience with this project, please contact me via email.