---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults


remote_theme             : "mmistakes/minimal-mistakes"
minimal_mistakes_skin    : "default" # "air", "aqua", "contrast", "dark", "dirt", "neon", "mint", "plum", "sunrise"

title: "About Me"
author_profile: true
layout: single
classes: wide
defaults:
  # _pages
  - scope:
      path: "/_pages/about.markdown"
      type: pages
    values:
      layout: single
      author_profile: true
permalink: /about/

feature_row:
  - image_path: /assets/aboutme/bandme.jpg
    alt: "placeholder image 1"
    title: ""
    excerpt: ""
  - image_path: /assets/aboutme/pianogif.gif
    image_caption: ""
    alt: "placeholder image 2"
    title: "I like to make music :)"
    excerpt: ""
    url: "/music/"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/aboutme/mixcraftSMALL.jpg
    title: ""
    excerpt: ""
feature_row2:
  - image_path: /assets/aboutme/monster.jpg
    alt: "placeholder image 1"
    title: ""
    excerpt: ""
  - image_path: /assets/aboutme/gamegif1.gif
    image_caption: "frog"
    alt: "placeholder image 2"
    title: "I like to make games :)"
    excerpt: ""
    url: /games/
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/aboutme/paintball.jpg
    title: ""
    excerpt: ""
feature_row3:
  - image_path: /assets/aboutme/rank2018.jpg
    alt: "placeholder image 1"
    title: ""
    excerpt: ""
  - image_path: /assets/aboutme/meleegif1.gif
    image_caption: "[Slippi](https://slippi.gg/)"
    alt: "placeholder image 2"
    title: "I like to compete :)"
    excerpt: ""
    url: "/melee/"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/aboutme/tourny.jpg
    title: ""
    excerpt: ""

---
{% include feature_row %}

{% include feature_row id="feature_row2" %}

{% include feature_row id="feature_row3" %}