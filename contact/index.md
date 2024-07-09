---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact



{%
  include button.html
  type="email"
  text="hujingchu@gmail.com"
  link="hujingchu@gmail.com"
%}
{%
  include button.html
  type="phone"
  text="(555) 867-5309"
  link="+1-555-867-5309"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on GaoDe Maps for easy navigation"
  link="https://surl.amap.com/1GnbKBG1B4Mk"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="罗湖分院"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="坪山分院"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}
深圳康宁医院（罗湖分院）
深圳市罗湖区翠竹路1080号(田贝地铁站D口步行360米)
{% endcapture %}

{% capture col2 %}
深圳康宁医院（坪山分院）
深圳市坪山区振碧路77号
{% endcapture %}

{% capture col3 %}
EMAIL US AT hujingchu@gmail.com
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
