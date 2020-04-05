## Photo projet during COVID-19

**Project description:** These are photos I took during the COVID-19 "lockdown" in Munich. Since I was forced to do home 
office I took the time in the morning to try out my Google Pixel 

### 2020 March xyz 

{% assign image_files = site.static_files | where: "image", true %}
{% for myimage in image_files %}
  {{ myimage.path }}
{% endfor %}

{% for image in site.static_files %}
    {% if image.path contains 'images/spring2020' %}
        <img src="{{ site.baseurl }}{{ image.path }}" alt="image" />
    {% endif %}
{% endfor %}

