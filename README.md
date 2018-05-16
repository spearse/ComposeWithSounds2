# ComposeWithSounds2

some text and [here is possible to download the file in PDF][1]

[1]:{{ site.url }}/downloads/CWS2.22.mpkg.zip

{% assign image_files = site.static_files | where: "image", true %}
{% for myimage in image_files %}
  {{ myimage.path }}
{% endfor %}
