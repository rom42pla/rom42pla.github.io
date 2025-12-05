---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I’m currently at my second **Postdoc** position as a **Researcher in Artificial Intelligence** at the Division of Robotics, Perception and Learning (RPL) of KTH Royal Institute of Technology, in Stockholm.
Until mid 2025, I was a Postdoc at the Computer Science Department of Sapienza University of Rome.
My research lies at the intersection of Computer Vision, Continual Learning, and Representation Learning.

I hold a PhD from the *Italian National PhD in Artificial Intelligence* program, where I deepened my expertise in AI and Deep Learning. My doctoral research, titled [*"Sparking Light on Deep Learning in EEG Research"*](https://iris.uniroma1.it/retrieve/535c6ba9-66b7-4799-808e-05254230efde/Tesi_dottorato_Lanzino.pdf), critically examined the recent success of neural networks in physiological signal analysis, highlighting and challenging some of the more surprising claims in the field.

Before pursuing my PhD, I earned both my BSc and MSc in Computer Science at Sapienza, graduating with honors. My master’s thesis, *"Laplacian-regularized Transductive Inference for Few-shot Object Detection"*, was supervised by Prof. Fabio Galasso.

Beyond research, I actively contribute to the academic community. I serve as a reviewer for top-tier conferences and journals such as **ICCV**, **NeurIPS**, **IEEE Transactions on Multimedia**, and **Nature Scientific Reports**, and co-organize workshops at major venues, including **BISCUIT** and **VisionDocs** at ICCV'25.

You can find [my complete CV here](files/cv.pdf).

## News

{% if site.author.linkedin %}
  <div class="wordwrap">You can find an updated list of news about me on <a href="https://www.linkedin.com/in/{{site.author.linkedin}}">my LinkedIn profile</a>.</div>
{% endif %}

<!-- <iframe src='https://widgets.sociablekit.com/linkedin-profile-posts/iframe/25567725' frameborder='0' width='100%' height='500'></iframe> -->

### 2025

#### September

:snowflake: :computer: Just started my second Postdoc position, this time at KTH!

#### May

:palm_tree: :ocean: Our proposed workshops, [BISCUIT](https://sites.google.com/di.uniroma1.it/biscuit-workshop-1/home) and [VisionDocs](https://sites.google.com/view/avml-lab-visiondocs-iccv2025) have been accepted at ICCV'25

#### January

:mortar_board: Finally defended my PhD thesis [*"Sparking Light on Deep Learning in EEG Research"*](https://iris.uniroma1.it/retrieve/535c6ba9-66b7-4799-808e-05254230efde/Tesi_dottorato_Lanzino.pdf) in front of the committee

### 2024

#### July

:trophy: Proud to have won a best presentation award at the poster competition at the [International Computer Vision Summer School (ICVSS'24)](https://iplab.dmi.unict.it/icvss2024/) 

## Organized workshops

- [**BISCUIT**](https://sites.google.com/di.uniroma1.it/biscuit-workshop-1/home) @ ICCV'25\\
<sup>1st International Workshop on Biomedical Image and Signal Computing for Unbiasedness, Interpretability, and Trustworthiness</sup>
- [**VisionDocs**](https://sites.google.com/view/avml-lab-visiondocs-iccv2025/) @ ICCV'25\\
<sup>2nd Workshop on Computer Vision Systems for Document Analysis and Recognition</sup>

## Selected publications

{% if site.author.googlescholar %}
  <div class="wordwrap">You can find a complete list of my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

### Conferences

<ul>
{% assign title_shown = false %}
{% for post in site.publications reversed %}
  {% if post.category != "conferences" %}
    {% continue %}
  {% endif %}
  {% include archive-single-cv.html %}
{% endfor %}
</ul>

### Journals

<ul>
{% assign title_shown = false %}
{% for post in site.publications reversed %}
  {% if post.category != "manuscripts" %}
    {% continue %}
  {% endif %}
  {% include archive-single-cv.html %}
{% endfor %}
</ul>
