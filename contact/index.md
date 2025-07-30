---
title: Contact
nav:
  order: 7
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Our lab recently moved to the new building of 101 College st at Yale after staying in Brigham and Women's Hospital / Harvard Medical School for ten years. We are now a core part of the newly established Stephen and Denise Adams Center for Parkinson's Disease Research at Yale, affiliated with the Yale School of Medicine’s Department of Neurology and Biomedical Informatics and Data Science (BIDS). Our wet lab is still located at 300 George St in New Haven, and anticipated to move into 101 College st in 2026.

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
  link="https://maps.app.goo.gl/9V3Z9dR8AjDg5CSSA"
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

