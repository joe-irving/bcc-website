---
layout: home
top_image: "/uploads/fibbers-books.jpeg"
image: "/uploads/Fibbers front w Banner.jpg"
jump:
  target: about
  text: Find out more
blocks:
- type: text
  text: |-
    # About

    {{ site.description }}
  buttons:
  - target: "/about"
    text: Read more
- type: image
  image: "/uploads/fibbersbanner.png"
  text: |-
    # New site!

    We are currently located at 3-5 Toft Green
    (location of the old night club Fibbers)
- template: block
  type: image
  image: "/uploads/citzens-of-earth.jpg"
  text: |-
    # Petition

    Please sign the petition for the council to bring the Barbican brownfield site back into council ownership through a Compulsory Purchase Order.
  buttons:
  - text: Sign the petition
    target: http://chng.it/DD6GPNVCHb
  heading: ''
  heading_background: false
- template: block
  type: map
  image: ''
  heading: ''
  heading_background: false
  text: ''
  buttons: []
- template: block
  type: image
  half: true
  image: "/uploads/fireplace.jpg"
  heading: ''
  heading_background: false
  text: |-
    # Mailing list

    Subscribe to get updates straight to your inbox and join in the (moderated) discussion.

    Treat all emails as publicly available, because they are!

    {% include riseuplist.html %}

---
