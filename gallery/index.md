---
title: Gallery
nav:
  order: 4
  tooltip: lab photos
---

# {% include icon.html icon="fa-solid fa-wrench" %}Gallery


{%
  include figure.html
  image="images/group-photos/IMG_4458.jpg"
  caption="Team gathering at Fuji Assembly, 2023"
  width="1200px"
%}


{% capture content %}
  {% include figure.html image="images/group-photos/IMG_15851.jpg" width="300px" %}
  {% include figure.html image="images/group-photos/IMG_9606.jpg" width="300px" %}
  {% include figure.html image="images/group-photos/IMG_1602.jpg" width="300px" %}
  {% include figure.html image="images/group-photos/IMG_15771.jpg" width="300px" %}
  {% include figure.html image="images/group-photos/IMG_1574.jpg" width="300px" %}
  {% include figure.html image="images/group-photos/IMG_1578.jpg" width="300px" %}
{% endcapture %}

{% include grid.html content=content style="square" %}

<figcaption class="figure-caption"> BAA 10K, 2023. <br>Kudos to Maoxuan, Ruifeng, Lucy, Anthony, Rambo, Xianjun (and 12yo Mia) </figcaption>

{%
  include figure.html
  image="images/group-photos/IMG_1547.jpg"
  caption="Lucy is happy with her new seat!"
  width="1200px"
%}

{%
  include figure.html
  image="images/group-photos/IMG_1422.jpg"
  caption="Our first visit to the new office at Assembly Row, 2023"
  width="1200px"
%}

{%
  include figure.html
  image="images/group-photos/IMG_4933.jpg"
  caption="Our team with Dennis Selkoe at the ARCND holiday party, 2023"
  width="1200px"
%}

{%
  include figure.html
  image="images/group-photos/IMG_8653.jpeg"
  caption="First group visit to Yale (01/19/2024)"
  width="1200px"
%}

{%
  include figure.html
  image="images/group-photos/IMG_5488.jpg"
  caption="Group gathering, 2024"
  width="1200px"
%}

{% capture col1 %}
  {% include figure.html image="images/group-photos/IMG_7024.jpg" width="100%" %}
{% endcapture %}
{% capture col2 %}
  {% include figure.html image="images/group-photos/IMG_7020.jpg" width="100%" %}
{% endcapture %}

{%
  include cols.html
  col1=col1
  col2=col2
%}

<figcaption class="figure-caption"> Lucy's master degree defense. Congrats, Lucy!! (05/11/2024) </figcaption>

{% capture content %}
  {% include figure.html image="images/group-photos/IMG_6290.jpg" width="300px" %}
  {% include figure.html image="images/group-photos/IMG_6595.jpg" width="300px" %}
  {% include figure.html image="images/group-photos/IMG_6304.jpg" width="300px" %}
{% endcapture %}

{% include grid.html content=content %}

<figcaption class="figure-caption"> Goodbye to Boston (6/27/2024) and greeting in New Haven (6/28/2024) </figcaption>


{% capture col1 %}
  {% include figure.html image="images/DongLab.logo.dark.png" width="100%" caption="Style 1 ([PNG](/images/DongLab.logo.dark.png), [SVG](/images/DongLab.logo.dark.svg))" %}
{% endcapture %}
{% capture col2 %}
  {% include figure.html image="images/DongLab.logo.white.png" width="100%" caption="Style 2 ([PNG](/images/DongLab.logo.white.png), [SVG](/images/DongLab.logo.white.svg))" %}
{% endcapture %}

{%
  include cols.html
  col1=col1
  col2=col2
%}

<figcaption class="figure-caption"> Lab Logo </figcaption>