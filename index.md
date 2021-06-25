---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
top_image: /uploads/barbican-comunity-center.jpeg
image: /uploads/barbican-comunity-center.jpeg
jump:
  target: about
  text: Find out more
blocks:
  - template: block
    type: heading
    half: true
    heading: About
    heading_background: false
    text: "{{ site.description }}"
    buttons:
    - target: "/about"
      text: Read more
    image: ''
  - template: block
    type: map
    half: false
    image: ''
    heading: ''
    heading_background: false
---
