---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# <i class="fas fa-envelope"></i>Contact

Our lab is part of the [School of Biological Sciences](https://www.ed.ac.uk/biology) at the University of Edinburgh.
We are part of the [Wellcome Centre for Cell Biology](https://www.wcb.ed.ac.uk), and are located on the 4<sup>th</sup> floor of the Michael Swann building.

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
  link="https://www.google.com/maps?q=Michael+Swann+Building,+King%27s+Buildings,+Edinburgh,+UK&ll=55.924634,-3.17462&spn=0.029046,0.092182&sll=37.0796465826016,-95.76678664320204&sspn=76.88164146107661,102.38890067050892&t=m&dg=opt&hq=Michael+Swann+Building,+King%27s+Buildings,&hnear=Edinburgh,+City+of+Edinburgh,+United+Kingdom&z=14"
  style="button"
%}
{:.center}

{% include section.html %}


{% capture col1content %}

### <i class="fas fa-mail-bulk"></i>Mailing Address  
{:.left}

Kenneth E. Sawin, Ph.D.  
Professor of Cell Biology  
The Wellcome Trust Centre for Cell Biology  
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
