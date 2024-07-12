---
title: Contact
nav:
  order: 7
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Our lab currently moved to Yale after staying in Brigham and Women's Hospital / Harvard Medical School for ten years. We are now a core part of the new Stephen and Denise Adams Center for Parkinson's Disease Research at Yale, affiliated with the Yale School of Medicine’s Department of Neurology and Section of Biomedical Informatics and Data Science (BIDS). We are geographically located at the 100 College Street and 300 George St in New Haven, Connecticut. From 2025, we will move to the new building of 101 College St. 

{%
  include button.html
  type="email"
  text="xianjun.dong@yale.edu"
  link="xianjun.dong@yale.edu"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://www.google.com/maps/place/Building+for+Transformative+Medicine+at+Brigham+and+Women's+Hospital/@42.3352602,-71.1085375,20.5z/data=!3m1!5s0x89e37a04d2c64fff:0xc5411e43fc7f57ac!4m15!1m8!3m7!1s0x89e37999978f0f23:0x896e8c84ea476eba!2sParking+garage+at+dead+end+to+the+right,+60+Fenwood+Rd,+Boston,+MA+02115!3b1!8m2!3d42.3353181!4d-71.1087369!16s%2Fg%2F11rvdz5n_0!3m5!1s0x89e3798e3a9cbd31:0x35376a566e389c7d!8m2!3d42.3353661!4d-71.1087175!16s%2Fg%2F11c1tt43yh?entry=ttu"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/yale-campus1.jpeg"
  caption="Yale campus"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/yale-campus2.jpg"
  caption="Yale campus"
%}

{% endcapture %}

{% capture col3 %}

{%
  include figure.html
  image="images/yale-campus3.jpeg"
  caption="New building at 101 College St "
%}

{% endcapture %}

{% capture col4 %}

{%
  include figure.html
  image="images/yale-campus4.jpeg"
  caption="New building at 100 College St "
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}
{% include cols.html col3=col4 col4=col3 %}

