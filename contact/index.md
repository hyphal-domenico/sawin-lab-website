---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# <i class="fas fa-envelope"></i>Contact

Our lab is part of the [School of Biological Sciences](https://www.ed.ac.uk/biology) at the University of Edinburgh.
We are located on the 4<sup>th</sup> floor of the Michael Swann building.
{:.left}

{%
  include link.html
  type="email"
  icon=""
  text="ken.sawin@ed.ac.uk"
  tooltip=""
  link="ken.sawin@ed.ac.uk"
  style="button"
%}
{%
  include link.html
  type="phone"
  icon=""
  text="+44 (0)131 650 7064"
  tooltip=""
  link="+44 131 650 7064"
  style="button"
%}
{%
  include link.html
  type="address"
  icon=""
  text="Google Maps"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://maps.app.goo.gl/QJKfUi5Q4hoj94gB9)"
  style="button"
%}
{:.center}

{% include section.html %}


{% capture col1content %}

### <i class="fas fa-mail-bulk"></i>Mailing Address  
{:.left}

Kenneth E. Sawin, Ph.D.  
Professor of Cell Biology,  
School of Biological Sciences, University of Edinburgh  
Michael Swann Building, Max Born Crescent  
Edinburgh EH9  3BF  
United Kingdom  


{:.left}
{% endcapture %}

{% capture col2content %}

{%
  include figure.html
  image="images/swann.jpg"
  caption="Michael Swann Building"
  width = "300px"
%}
{% endcapture %}
{% include two-col.html col1=col1content col2=col2content %}
