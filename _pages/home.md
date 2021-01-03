---
layout: splash
permalink: /
hidden: true
header:
  overlay_color: "#5e616c"
  # overlay_image: /assets/images/mm-home-page-feature.jpg
  actions:
    - label: "<i class='fal fa-file'></i> Resume"
      url: "/docs/quick-start-guide/"
    - label: "<i class='fas fa-tasks'></i> Projects"
      url: "/projects/"
title: Hey, I am Min!
excerpt: 
  This is the place for storing my Data Science treasure.<br>
  <small>
    Check out my projects, codebases as well as readings, 
    and hope you can find out something interesting and useful.
  </small>
intro: 
  - title: A little about me
  - excerpt: 
feature_row:
  - image_path: /assets/images/test.png
    alt: "customizable"
    title: "Super customizable"
    excerpt: "Everything from the menus, sidebars, comments, and more can be configured or set with YAML Front Matter."
    url: "/docs/configuration/"
    btn_class: "btn--primary"
    btn_label: "Learn more"
  - image_path: /assets/images/mm-responsive-feature.png
    alt: "fully responsive"
    title: "Responsive layouts"
    excerpt: "Built with HTML5 + CSS3. All layouts are fully responsive with helpers to augment your content."
    url: "/docs/layouts/"
    btn_class: "btn--primary"
    btn_label: "Learn more"
  - image_path: /assets/images/mm-free-feature.png
    alt: "100% free"
    title: "100% free"
    excerpt: "Free to use however you want under the MIT License. Clone it, fork it, customize it... whatever!"
    url: "/docs/license/"
    btn_class: "btn--primary"
    btn_label: "Learn more"      
---
{% include feature_row id="intro" type="center" %}

{% include feature_row %}