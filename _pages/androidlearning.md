---
title: "Android Learning"
layout: splash
permalink: /android-learning/
date: 2016-03-23T11:48:41-04:00
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/unsplash-image-1.jpg
excerpt: "Bacon ipsum dolor sit amet salami ham hock ham, hamburger corned beef short ribs kielbasa biltong t-bone drumstick tri-tip tail sirloin pork chop."
intro: 
  - excerpt: 'Nullam suscipit et nam, tellus velit pellentesque at malesuada, enim eaque. Quis nulla, netus tempor in diam gravida tincidunt, *proin faucibus* voluptate felis id sollicitudin. Centered with `type="center"`'
feature_row:
 
feature_row2:
  - image_path: /images/bird.jpeg
    alt: "placeholder image 2"
    title: "Placeholder Image Left Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Left aligned with `type="left"`'
    url: "/myfirstarticle/"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row3:
  - image_path: /images/bird.jpeg
    alt: "placeholder image 2"
    title: "Placeholder Image Left Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Left aligned with `type="left"`'
    url: "/myfirstarticle/"
    btn_label: "Read More"
    btn_class: "btn--primary"

---

{% include feature_row id="intro" type="center" %}

{% include feature_row id="feature_row" type="left" %}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="left" %}