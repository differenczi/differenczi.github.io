## Photo projet during COVID-19

**Project description:** These are photos I took during the COVID-19 "lockdown" in Munich. Since I was forced to do home 
office I took the time in the morning to try out my Google Pixel 

### 2020 March

{% assign image_files = site.static_files | where: "image", true %}
{% for myimage in image_files %}
  <img src="{{ myimage.path }}?raw=true"/>
{% endfor %}


