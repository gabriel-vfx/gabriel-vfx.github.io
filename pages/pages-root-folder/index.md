---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: video
permalink: /index.html
homepage: true
iframe: "<iframe src='https://player.vimeo.com/video/225656888' frameborder='0' allowfullscreen></iframe>"

gallery:
  - image_url: images/pic_01.jpg
    thumb_url: images/pic_01_thumb.jpg
    caption: 
  - image_url: images/pic_05.jpg
    thumb_url: images/pic_05_thumb.jpg
  - image_url: images/pic_03.jpg
    thumb_url: images/pic_03_thumb.jpg
  - image_url: images/pic_04.jpg
    thumb_url: images/pic_04_thumb.jpg
  - image_url: images/pic_06.jpg
    thumb_url: images/pic_06_thumb.jpg
  - image_url: images/pic_07.jpg
    thumb_url: images/pic_07_thumb.jpg
  - image_url: images/pic_02.jpg
    thumb_url: images/pic_02_thumb.jpg
  - image_url: images/pic_08.jpg
    thumb_url: images/pic_08_thumb.jpg

services_title: Filming Services
services:
  - title: Events
    description: Make it forever.<br>Be it a concert, live show, wedding or anything else in this world.
  - title: Narrative
    description: Add moving pictures to your story.<br>Pictures can add more than a 1000 words to describe your story. 
  - title: Commercial
    description: Show the world your product or service with images.<br>Images can be a great way to communicate.

contact_title: Let's get in touch
---

{% include _services.html %}
{% include _gallery.html %}
{% include _contact.html %}
{%- include _about.html -%}
