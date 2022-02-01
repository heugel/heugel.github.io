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
      layout: splash
      author_profile: false
permalink: /about/

feature_row:
  - image_path: /assets/shrekframeSMALL.jpg
    alt: "placeholder image 1"
    title: ""
    excerpt: ""
  - image_path: /assets/shrekframeSMALL.jpg
    image_caption: "Image courtesy of [Unsplash](https://unsplash.com/)"
    alt: "placeholder image 2"
    title: "Music"
    excerpt: "I like to make music :)"
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/shrekframeSMALL.jpg
    title: ""
    excerpt: ""
feature_row2:
  - image_path: /assets/shrekframeSMALL.jpg
    alt: "placeholder image 2"
    title: "Game Design"
    excerpt: 'I like making games :)'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row3:
  - image_path: /assets/shrekframeSMALL.jpg
    alt: "placeholder image 2"
    title: "Melee"
    excerpt: 'I like to compete :)'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"

---

{% include feature_row %}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="right" %}