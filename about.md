---
layout: page
title: About
permalink: /about/
published: true
redirect_from: "/"
---

<div class="page" markdown="1">

{% capture page_subtitle %}
<img
    class="me"
    alt="{{ author.name }}"
    src="{{ site.author.photo | relative_url }}"
    srcset="{{ site.author.photo2x | relative_url }} 2x"
/>
{% endcapture %}

{% include page/title.html title=page.title subtitle=page_subtitle %}

## Hello

An avid data science enthusiast with theoretical and practical experience in predictive analysis and machine learning. Currently in my final year at University of Sydney Business School, specialising in analytics and information systems. I continue to further my technical skills through MOOC platforms, participating in Kaggle competitions and working on data projects.

Available for new opportunities in the realm of a business analyst, data analyst/scientist or related fields.

Competencies:
Data Science (EDA, preparation, cleansing, feature selection, modelling, validation) | Machine Learning | Predictive Modelling | Statistical Analysis | Data Interpretation | Supervised Learning (Regression, Classification) | Unsupervised Learning (Dimensionality Reduction) | Time Series Analysis | Web Scraping

Languages & Frameworks:
Python (pandas, numpy, scikit-learn, seaborn, matplotlib) | Tableau | SQL | LaTeX 

</div>
