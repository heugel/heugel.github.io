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
  - image_path: /assets/lonelym2.jpg
    alt: "placeholder image 1"
    title: "Music"
    excerpt: "I like to make music :)"
	url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/lonelym2.jpg
    image_caption: "Image courtesy of [Unsplash](https://unsplash.com/)"
    alt: "placeholder image 2"
    title: "Game Design"
    excerpt: "I like to make games :)"
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/lonelym2.jpg
    title: "Melee"
    excerpt: "I like to compete :)"
	url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"

---

{% include feature_row %}

