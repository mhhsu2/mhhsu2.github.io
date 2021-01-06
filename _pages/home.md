---
layout: splash
permalink: /
hidden: true
header:
  overlay_color: "#5e616c"
  # overlay_image: /assets/images/mm-home-page-feature.jpg
  actions:
    - label: "<i class='fal fa-file'></i> Resume"
      url: "/assets/images/min_resume.pdf"
    - label: "<i class='fas fa-tasks'></i> Projects"
      url: "/projects/"
title: Hey, I am Min!
excerpt: 
  This is the place for storing my Data Science treasure.<br>
  <small>
    Check out my projects, codebase as well as readings, 
    and hope you can find out something interesting and useful.
  </small> 
intro: 
  - title: A little about me
  - excerpt: I am looking for full-time positions in **Data Science**, **Machine Learning**, and **AI** after graduating in **May 2021** from the [University of Illinois Urbana-Champaign (UIUC)](https://illinois.edu/) with an M.S. degree in MechSE.
  - excerpt: I was a Data Science Intern at <a href="https://www.irobot.com/about-irobot/careers/data-science-and-machine-learning"> iRobot</a> and a Machine Learning Engineer Intern at <a href="https://quantrend.ai/">Quantrend Technology</a>. I have an extensive background working with various fields including customer analytics, quantitative trading, industry 4.0, recommender system, computer vision, and reinforcement learning.
  - excerpt: So, why I am interested in Data Science? I am always excited to explore new areas, define problems, and utilize data to drive our decisions. Thus, Data Scientist gives me the perfect opportunity to purse what I love to do!
  - url: "/about/"
    btn_class: "btn--info"
    btn_label: "Learn more about me"    


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

<h2 class="archive__item-title">How others think about me</h2>
{% include rec.html %}

{% include feature_row %}