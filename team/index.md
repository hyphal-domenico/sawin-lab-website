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

If you are interested in our research and want to undertake a PhD project with us, do not hesitate to contact. The main sources of recent PhD student funding have been [EastBio](http://www.eastscotbiodtp.ac.uk) and the [Darwin Trust of Edinburgh](https://darwintrust.bio.ed.ac.uk/edinburgh).
{:.left}

Projects for 2025 start:
- EastBio: [Spatial regulation of mRNAs in filamentous fungi](https://www.findaphd.com/phds/project/eastbio-spatial-regulation-of-mrnas-in-filamentous-fungi/?p179680). Deadline: January 17, 2025.


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

Eric Lynch  
Weronika Borek  
Andreas Anders  
Vicky Miller  
Claudia Bicho  
Lynda Groocock  
Itaru Samejima  

{% endcapture %}

{% capture col2content %}

Hilary Snaith  
Delyan Mutavchiev  
Xun Bao  
Harish Thakur  
Sanju Ashraf  
Hayley Johnson  

{% endcapture %}

{% capture col3content %}

Su Ling Leong  
Ana Rodriguez  
Ye Dee Tay  
James Le Cornu  
Tanya Dudnakova  
Gaurav Barve

{:.center}

{% endcapture %}


{% include three-col.html col1=col1content col2=col2content col3=col3content%}
