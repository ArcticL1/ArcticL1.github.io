---
title: "Home Page"
layout: splash
permalink: /
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/wolfban2.png
  actions:
    - label: "Download CV"
      url: "https://drive.google.com/file/d/1ePqrAcar-abcMBgLCd7uo0HUbZDd929t/preview"
      target: "_blank"
    - label: "Linkedin"
      url: "https://uk.linkedin.com/in/lewis-esler-9a787b3b3"
      target: "_blank"

excerpt: "This website is dedicated to showing my work within game development and design, showing my projects, about me and how to contact me and get key information such as my CV and LinkedIn profile. "


skills:
  - name: "Unity -"
    icon: "fab fa-fw fa-unity"
    badges: ["C#", "Game Dev", "Lighting/Effects", "Particle-Systems"]
    text: "Using Unity for several different skills working in both 2D and 3D design, such as programming with C#, Lighting and particle systems, UI elements and much more. Over the past year, I created many small projects while learning Unity and the skills behind it."
  - name: "Game Design -"
    icon: "fas fa-fw fa-gamepad"
    badges: ["Game Mechanics", "Levels", "UI", "Art"]
    text: "I have experience in art and design across a wide range of elements, including digital, traditional, and perspective art styles. I have developed mechanics that the player will use within gameplay, such as generators that power’s up certain elements in a platformer game and have worked with features such as health bars for the player/enemy, as well as main menus."

feature_row:
  - image_path: assets/images/hornet1.png
    alt: "placeholder image 1"
    title: "Art Styles -"
    excerpt: "This is one of the many art styles I can draw in, This artwork above features a popular game character from the game “Hollow Knight – Silksong.” And you see this in more detail and my other styles on my content page."
    url: "https://arcticl1.github.io/content/"
    btn_label: "Read More"
    btn_class: "btn--primary"

    
  - image_path: /assets/images/20260417_133124.jpg
    alt: "placeholder image 2"
    title: "Hobbies -"
    excerpt: "3D printing is one of my hobbies. I have made several small items, though this is one of my biggest projects. It is a scale replica of the portal gun from the game Portal, which took over 37.5 hours to print and assemble. You can see more about my hobbies on the About Me page.                             

    "
    url: "https://arcticl1.github.io/about-me/"
    btn_label: "Read More"
    btn_class: "btn--primary"
    
  - image_path: /assets/images/rudo.png
    alt: "placeholder image 4"
    title: "Projects -"
    excerpt: "This is one of my projects I have created in my first year of university, this is a game Called Cat-acombs which is an exploratory dungeon clawer fighting rats as a cat, and you can see this and many for projects on my project page."
    url: "https://arcticl1.github.io/projects/"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

{% include skills skills=page.skills %}

  
    
