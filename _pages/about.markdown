---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults


remote_theme             : "mmistakes/minimal-mistakes"
minimal_mistakes_skin    : "default" # "air", "aqua", "contrast", "dark", "dirt", "neon", "mint", "plum", "sunrise"

title: "About Me"

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
  - image_path: /assets/shrekframeSMALL.jpg
    alt: "placeholder image 1"
    title: ""
    excerpt: ""
  - image_path: /assets/shrekframeSMALL.jpg
    image_caption: "Image courtesy of [Unsplash](https://unsplash.com/)"
    alt: "placeholder image 2"
    title: "I like to make music :)"
    excerpt: ""
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/shrekframeSMALL.jpg
    title: ""
    excerpt: ""
feature_row2:
  - image_path: /assets/shrekframeSMALL.jpg
    alt: "placeholder image 1"
    title: ""
    excerpt: ""
  - image_path: /assets/shrekframeSMALL.jpg
    image_caption: "Image courtesy of [Unsplash](https://unsplash.com/)"
    alt: "placeholder image 2"
    title: "I like to make games :)"
    excerpt: ""
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/shrekframeSMALL.jpg
    title: ""
    excerpt: ""
feature_row3:
  - image_path: /assets/aboutme/rank2018.jpg
    alt: "placeholder image 1"
    title: ""
    excerpt: ""
  - image_path: /assets/aboutme/meleegif1.gif
    image_caption: "Image courtesy of [Unsplash](https://unsplash.com/)"
    alt: "placeholder image 2"
    title: "I like to compete :)"
    excerpt: ""
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/aboutme/tourny.jpg
    title: ""
    excerpt: ""

---

{% include feature_row %}

{% include feature_row id="feature_row2" %}

{% include feature_row id="feature_row3" %}