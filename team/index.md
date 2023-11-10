---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# <i class="fas fa-users"></i>Team

We are a diverse group of people coming from throughout the globe.
{:.center}

{% include section.html %}

{%
  include list.html
  data="members"
  component="portrait"
  filters="role: pi"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: postdoc"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: phd"
%}
{:.center}

{% include section.html %}

## <i class="fas fa-user-plus"></i>Join

#### PhD Projects
{:.left}

If you are interested in our research and want to undertake a PhD project with us, do not hesitate to contact. The main sources of recent PhD student funding have been [EastBio](http://www.eastscotbiodtp.ac.uk), the [Wellcome Four Year PhD Programme in Integrative Cell Mechanisms](https://www.wcb.ed.ac.uk/iCMPhD), and the [Darwin Trust of Edinburgh](https://darwintrust.bio.ed.ac.uk/edinburgh).
{:.left}

Projects for 2024 start:
- EastBio: [Hyphal growth of filamentous fungi: regulation and omics analysis](https://www.findaphd.com/phds/project/eastbio-hyphal-growth-of-filamentous-fungi-regulation-and-omics-analysis/?p161798). Deadline: November 27<sup>th</sup> 2023.


{%
  include link.html
  link="Contact"
  text="Contact us"
  icon="fas fa-arrow-right"
  flip=true
%}
{:.center}


{% include section.html %}
## <i class="fas fa-scroll"></i>Past members
{:.left}

{% capture col1content %}

Andreas Anders  
Vicky Miller  
Claudia Bicho  
Lynda Groocock  
Itaru Samejima  

{% endcapture %}

{% capture col2content %}

Hilary Snaith  
Eric Lynch  
Weronika Borek  
Delyan Mutavchiev  
Xun Bao  


{% endcapture %}

{% capture col3content %}


Harish Thakur  
Sanju Ashraf  
Hayley Johnson  
Su Ling Leong  
Ana Rodriguez
Ye Dee Tay

{:.center}

{% endcapture %}


{% include three-col.html col1=col1content col2=col2content col3=col3content%}
