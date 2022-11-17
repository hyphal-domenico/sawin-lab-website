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

If you are interested in our research and want to undertake a PhD project with us do not hesitate to contact. We take on students through [EastBio](http://www.eastscotbiodtp.ac.uk), within the [Wellcome Four Year PhD Programme in Integrative Cell Mechanisms](https://www.wcb.ed.ac.uk/iCMPhD), and the [Darwin Trust of Edinburgh](https://darwintrust.bio.ed.ac.uk/edinburgh).

Projects for 2023 start:  
- EastBio: [Understanding hyphal growth of filamentous fungi through omics approaches](https://www.findaphd.com/phds/project/eastbio-understanding-hyphal-growth-of-filamentous-fungi-through-omics-approaches/?p148077). Deadline: December 5<sup>th</sup> 2022.
- Darwin Trust: [Eukaryotic cell polarity regulation and its regulation by stress](https://www.findaphd.com/phds/project/eukaryotic-cell-polarity-regulation-and-its-regulation-by-stress/?p150365). Deadline: January 2023.

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


{:.center}
{% endcapture %}

{% capture col2content %}

Hilary Snaith  
Eric Lynch  
Weronika Borek  
Delyan Mutavchiev  
Xun Bao  


{:.center}

{% endcapture %}

{% capture col3content %}


Harish Thakur  
Sanju Ashraf  
Hayley Johnson  
Su Ling Leong  
Ana Rodriguez

{:.center}

{% endcapture %}


{% include three-col.html col1=col1content col2=col2content col3=col3content%}
