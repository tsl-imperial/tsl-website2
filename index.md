---
redirect_from:
  - home/
  - cive60008_21/
  - cive60008_21/week01/seminar1/
  - cive60008_22/
  - cive60008_22/assignments/1/
  - cive60008_22/assignments/2/
  - cive60008_22/week01/notebooks/
  - cive60008_22/week02/notebooks/
  - cive60008_22/week03/notebooks/
  - cive60008_22/week04/notebooks/
  - cive60008_22/week05/notebooks/
  - cive60008_22/week06/notebooks/
  - cive60008_22/week07/notebooks/
  - cive60008_22/week08/notebooks/
  - cive60008_22/week09/notebooks/
  - cive97129_23/assignments/1/
  - cive97129_23/assignments/2/
  - demo-pathfinding/
  - project/shift-project/
  - research/autonomy/
  - research/logistics/
  - tags/
  - tag/autonomy
  - teaching/
  - tf/
  - tf/60008_21/
  - wsds/
---



The Transport Systems & Logistics Laboratory focuses on the algorithms and models for the **design**, **management** and **deployment** of **autonomous transport systems**, in **land**, **air** and **water**. Our emphasis is on  **distributed control**, optimising **freight distribution** and building **resilience against disruptions**.

TSL is led by [**Professor Panagiotis Angeloudis**](/members/angeloudis-p). We have strong links with our wide network of academic collaborators, industrial partners and policymakers.

{%
  include figure.html
  image="images/team/team.jpg"
%}

{% include section.html %}



{% capture text %}

Our research focuses on how transport systems can become more efficient, safe and resilient, through the three interlinked strands of **autonomy**, **modelling** and **control** for **strategic and tactical decision making**. The models we built incorporate the effects of operational uncertainty (future demand, operational disruptions, targetted attacks) in real-world operations. 

We have sought solutions using **optimisation**, **reinforcement learning**, **network modelling**, and bespokely developed high performance **agent based modelling** tools.


{%
  include button.html
  link="papers"
  text="Recent publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}


{% endcapture %}

{%
  include feature.html
  image="images/img_research.jpg"
  link="projects"
  title="Our Research"
  flip=tru
  style="bare"
  text=text
%}

{% capture text %}

Our researchers benefit from the strong links of our group with other laboratories within the Imperial College community, external collaborators, and industry partners. Our alumni have achieved success in academia, secured influential roles in industry, or launched their own startups.

**Join us:** We are looking for talented researchers to join our team, and to contribute to the development of next generation of models and technologies for transport systems and logistics. Several sholarships are available for qualified applicants.

{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{%
  include button.html
  link="apply"
  text="Join us"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{% include section.html %}

#### Our Themes

{% include list.html component="card" data="projects" filters="group: theme" style="small" %}

{% include section.html %}

{%
  include feature.html
  image="images/img_team.jpg"
  link="team"
  title="Our Team"
  style="bare"
  text=text
%}


{% include section.html %}

#### Our Funders


{% capture col1 %}
<img src="images/funders/ukri.svg">
{% endcapture %}

{% capture col2 %}
<img src="images/funders/jsps.jpg">
{% endcapture %}

{% capture col3 %}
<img src="images/funders/innovateuk.svg">
{% endcapture %}

{% capture col4 %}
<img src="images/funders/alan-turing.svg">
{% endcapture %}

{% capture col5 %}
<img src="images/funders/hefce.jpg">
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 col4=col4 col5=col5%}
