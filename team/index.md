---
title: Team
nav:
  order: 2
  tooltip: About our team
redirect_from:
  - /lab-members
  - /alums
  - /mascots
  - /staff
  - /trainees
---

# {% include icon.html icon="fa-solid fa-users" %}Team

{% include section.html %}

Our lab is made up of a highly engaged and collaborative team of researchers.
We recognize that diverse teams do better research.
We foster an environment where team members are treated equally, and where we respect and admire our differences.
The team includes postdocs, staff, and students at all levels.

## Current Members

{% include list.html  data="members"  component="portrait"  filters="role: pi, group: " %}
{% include list.html  data="members"  component="portrait"  filters="role: ARS, group: " %}
{% include list.html  data="members"  component="portrait"  filters="role: postdoc, group: " %}
{% include list.html  data="members"  component="portrait"  filters="role: phd, group: " %}
{% include list.html  data="members"  component="portrait"  filters="role: master, group: " %}
{% include list.html  data="members"  component="portrait"  filters="role: engineer, group: " %}
{% include list.html  data="members"  component="portrait"  filters="role: researchassociate, group: " %}
{% include list.html  data="members"  component="portrait"  filters="role: researchassistant, group: " %}
{% include list.html  data="members"  component="portrait"  filters="role: trainee, group: " %}
{% include list.html  data="members"  component="portrait"  filters="role: manager, group: " %}
{% include list.html  data="members"  component="portrait"  filters="role: technician, group: " %}


{% include section.html %}

We work with a wide range of outstanding groups from around the world, and we're always on the lookout for new and unique perspectives.
We want to push the frontier of data science and train the next generation of data scientists.

{%
  include button.html
  icon="fa-solid fa-handshake-angle"
  text="Join the Team"
  link="join"
  style="button"
%}

{% include section.html %}


## Alumni

{% include list.html  data="members"  component="portrait"  style="small" filters="role: ARS, group: alum" %}
{% include list.html  data="members"  component="portrait"  style="small" filters="role: postdoc, group: alum" %}
{% include list.html  data="members"  component="portrait"  style="small" filters="role: phd, group: alum" %}
{% include list.html  data="members"  component="portrait"  style="small" filters="role: master, group: alum" %}
{% include list.html  data="members"  component="portrait"  style="small" filters="role: engineer, group: alum" %}
{% include list.html  data="members"  component="portrait"  style="small" filters="role: researchassociate, group: alum" %}
{% include list.html  data="members"  component="portrait"  style="small" filters="role: researchassistant, group: alum" %}
{% include list.html  data="members"  component="portrait"  style="small" filters="role: trainee, group: alum" %}
{% include list.html  data="members"  component="portrait"  style="small" filters="role: manager, group: alum" %}
{% include list.html  data="members"  component="portrait"  style="small" filters="role: technician, group: alum" %}

{% include section.html %}

## Funding

{% capture content %}
[![American Parkinson's Disease Association](/images/team/apda-logo.png)](https://www.apdaparkinson.org)

[![Aligning Science Across Parkinson’s](/images/team/ASAP-logo.png)](https://parkinsonsroadmap.org)

[![Parkinson's Foundation](/images/team/pdf-logo.png)](https://www.parkinson.org/)

[![National Institute of Neurological Disorders and Stroke](/images/team/ninds-logo.png)](https://www.ninds.nih.gov/)

[![NIH Heal Initiative](/images/team/heal-logo.png)](https://heal.nih.gov)

[![NIH Small Business Innovation Research](/images/team/seed-logo.png)](https://seed.nih.gov)

[![Brigham Research Institute](/images/team/BRI-logo.png)](https://www.discoverbrigham.org/)

[![Massachusetts Life Sciences Center](/images/team/MLSC-logo.jpeg)](https://www.masslifesciences.com)

[![Yale AI Seed](https://upload.wikimedia.org/wikipedia/commons/6/6e/Yale_University_logo.svg)](https://ai.yale.edu/seed-grants-2025)

{% endcapture %}
​
{% include grid.html content=content %}

