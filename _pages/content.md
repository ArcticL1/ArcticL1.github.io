---
title: "Content"
layout: image-head
permalink: /content/
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/🔥Gachiakuta rudo🔥.jpg
  actions:
    - label: "Download CV"
      url: "https://drive.google.com/file/d/1ePqrAcar-abcMBgLCd7uo0HUbZDd929t/preview"
      target: "_blank"

excerpt: "You can add text here."

intro: 
  - excerpt: 'You can also add text like this....'

feature_row:
  - image_path: /assets/images/🔥Gachiakuta rudo🔥.jpg
    alt: "placeholder image 1"
    title: "Placeholder 1"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"

 gallery_gameart:
  # Recommended: width "240px" to "320px" keeps a neat grid
  - url: /assets/images/placeholder.png
    image_path: /assets/images/🔥Gachiakuta rudo🔥.jpg
    alt: "Art 1"
    title: "Style pass"
    caption: "Style pass"
  - url: /assets/images/placeholder.png
    image_path: /assets/images/🔥Gachiakuta rudo🔥.jpg
    alt: "Art 2"
    title: "Final polish"
    caption: "Final polish"
    image_path: /assets/images/🔥Gachiakuta rudo🔥.jpg
    alt: "Art 3"
    title: "Final polish"
    caption: "Final polish"
---
{% include feature_row id="intro" type="center" %}
{% include gallery id="gallery_gameart" layout="third" thumb_height="180px" %}
{% include feature_row type="left" %}

