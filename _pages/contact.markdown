---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults


remote_theme             : "mmistakes/minimal-mistakes"
minimal_mistakes_skin    : "default" # "air", "aqua", "contrast", "dark", "dirt", "neon", "mint", "plum", "sunrise"

defaults:
  # _pages
  - scope:
      path: "/_pages/contact.markdown"
      type: pages
    values:
      layout: single
      author_profile: true
permalink: /contact/
---
## Contact

<!-- modify this form HTML and place wherever you want your form -->
<form
  action="https://formspree.io/f/mdobenqd"
  method="POST"
>
  <label>
    Your email:
    <input type="email" name="_replyto">
  </label>
  <label>
    Your message:
    <textarea name="message"></textarea>
  </label>
  <!-- your other form fields go here -->
  <button type="submit">Send</button>
</form>

Leave a message and I'll reply as soon as possible :)
