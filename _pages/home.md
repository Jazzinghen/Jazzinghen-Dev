---
layout: splash
paginate: false
title: "Michele Bianchi"
permalink: /

header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/PANO_crop_light.jpg
  actions:
    - label: "<i class='fas fa-scroll'></i> Resume"
      url: "/resume/"

excerpt: |
        Software engineer with 5+ years experience in C++ development in R&D companies.

        I have worked on multiplatform simulations, SDKs, embedded systems, and CI pipelines.

        I love videogames, tabletop RPGs, and anime. They are what allowed me to get here.
intro: 
  - title: "Projects"
feature_row1:
  - image_path: /assets/images/headers/ge-mu.jpg
    alt: "Games header"
    title: "Games"
    excerpt: "Games I worked on for passion, university or research"
    url: "/projects/games"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row2:
  - image_path: /assets/images/headers/science.jpg
    alt: "Research projects header"
    title: "Research"
    excerpt: "Research projects I worked on during my academia period"
    url: "/projects/research"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row3:
  - image_path: /assets/images/headers/rpg.jpg
    alt: "Tabletop RPGs header"
    title: "Tabletop RPGs"
    excerpt: "Various tabletop RPGs materials I created while playing one of my favourite forms of game"
    url: "/projects/rpg"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row4:
  - image_path: /assets/images/headers/keebs.jpg
    alt: "Keyboards header"
    title: "Mechanical Keyboards"
    excerpt: "Keyboards I made to use at work or at home"
    url: "/projects/keyboards"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row5:
  - image_path: /assets/images/headers/others.png
    alt: "Other projects header"
    title: "Other"
    excerpt: "All the projects that don't fall in the other categories"
    url: "/projects/other"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row id="feature_row1" type="left" %}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="left" %}

{% include feature_row id="feature_row4" type="left" %}

{% include feature_row id="feature_row5" type="left" %}
