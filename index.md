---
layout: splash
title: "Cosby Cyber"
permalink: /
header:
  overlay_color: "#0f172a"            # deep slate overlay
  overlay_filter: 0.35                # darken the hero for readable text
  overlay_image: /assets/img/hero.jpg # wide banner (1600×600+)
  actions:
    - label: "Join the Club"
      url: /join/
    - label: "Calendar"
      url: /calendar/
excerpt: "Cyber club projects, resources, and calendar."
intro: 
  - excerpt: "We build useful, secure things—then explain how they work. No experience required."
feature_row:
  - image_path: /assets/img/card-join.png
    alt: "Join"
    title: "Start here"
    excerpt: "What to expect, how to join, and our code of conduct."
    url: "/join/"
    btn_label: "Join the Club"
    btn_class: "btn--primary"
  - image_path: /assets/img/card-projects.png
    alt: "Projects"
    title: "Projects"
    excerpt: "Websites, Minecraft servers, mini-CTFs, and more."
    url: "/projects/"
    btn_label: "See Projects"
  - image_path: /assets/img/card-resources.png
    alt: "Resources"
    title: "Resources"
    excerpt: "Cheat sheets, guides, and practice data."
    url: "/resources/"
    btn_label: "View Resources"
feature_row2:
  - title: "Policies & ROE"
    excerpt: "We only test what we own or have permission to use. Safety > speed."
    url: "/policies/"
    btn_label: "Read the Rules"
    btn_class: "btn--inverse"
---

{% include feature_row id="intro" type="center" %}
{% include feature_row %}
{% include feature_row id="feature_row2" type="center" %}
