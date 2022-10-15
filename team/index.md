---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# <i class="fas fa-users"></i>Team

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

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

## Join

#### PhD Projects
{:.left}

If you are interested in our research and want to undertake a PhD project with us do not hesitate to contact. We advertise projects with [EastBio](http://www.eastscotbiodtp.ac.uk), within the [Wellcome Four Year PhD Programme in Integrative Cell Mechanisms](https://www.wcb.ed.ac.uk/iCMPhD), and the [Darwin Trust of Edinburgh](https://www.wcb.ed.ac.uk/iCMPhD).

#### Postdocs
{:.left}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.  

#### Undergraduates
{:.left}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. 

{%
  include link.html
  link="Contact"
  text="Contact us"
  icon="fas fa-arrow-right"
  flip=true
%}
{:.center}


{% include section.html %}
## Past members
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
