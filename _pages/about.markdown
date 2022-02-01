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

gallery:
  - url: /assets/shrekframeSMALL.jpg
    image_path: /assets/shrekframeSMALL.jpg
    alt: "placeholder image 1"
    title: "I like music"
  - url: /assets/shrekframeSMALL.jpg
    image_path: /assets/shrekframeSMALL.jpg
    alt: "placeholder image 2"
    title: "I like making games"
  - url: /assets/shrekframeSMALL.jpg
    image_path: /assets/shrekframeSMALL.jpg
    alt: "placeholder image 3"
    title: "I like competing"

---

{% include gallery %}
