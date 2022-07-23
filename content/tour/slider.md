---
widget: slider
weight: 1
active: true
headless: true

design:
  # Slide height is automatic unless you force a specific height (e.g. '400px')
  slide_height: ''
  is_fullscreen: true
  # Automatically transition through slides?
  loop: false
  # Duration of transition between slides (in ms)
  interval: 2000

content:
  slides:
    - title: Our Lab on 17th Floor MHMK
      content: Department of Chemical Technology, Faculty of Science, Chulalongkorn University
      align: center
      background:
        position: right
        color: '#666'
        brightness: 0.7
        media: coders.jpg
    - title: Lecture and Learn
      content: ''
      align: left
      background:
        position: center
        color: '#555'
        brightness: 0.7
        media: welcome.jpg
    - title: Algae Lab
      content: ''
      align: right
      background:
        position: center
        color: '#333'
        brightness: 0.5
        media: algae.jpg
      link:
        icon: graduation-cap
        icon_pack: fas
        text: Join Us
        url: ../contact/
---
