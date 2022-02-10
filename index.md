---
title: Home
---

# Yang Lab

Welcome to the Yang Lab at [Nanjing Medical University](https://www.njmu.edu.cn/)!

The introduction of Yang Lab.
.........................................................

Click around to learn more about the lab's research vision and focus!

{%
  include link.html
  type="github"
  icon=""
  text="See our open science projects"
  link="biostat0903"
  style="button"
%}
{%
  include link.html
  icon="fas fa-users"
  text="Join the Team"
  link="https://gwxy.njmu.edu.cn/"
  style="button"
%}
{:.center}

{% include section.html full=true %}

{% include banner.html image="images/nanjing.png" %}

{% include section.html %}

# Highlights

{% capture text %}
We use ..............................to improve the ..........................
We develop ............................. to .........................
We focus on .........................

[See what we've published &nbsp;→](research)
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/dna.jpg"
  link="research"
  headline="Our Research"
  text=text
%}

{% capture text %}
We also release software to enable reproducible computational biology analyses and workflows.
All of our software is open source, and we encourage active learning through meaningful code contributions.
Please cite any software you use!
.................................

[See our resources &nbsp;→](resources)
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/software.jpg"
  link="resources"
  headline="Our software"
  text=text
%}

{% capture text %}
We are recruiting!
To see your face in this page, please reach out!

[Meet our team &nbsp;→](people)
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/bee.jpg"
  link="team"
  headline="Our lab team"
  text=text
%}

{%
  include link.html
  type="github"
  icon=""
  text="Website template"
  link="wayscience/lab-website-template"
  style="button"
%}
{:.center}
