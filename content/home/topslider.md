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
  loop: true
  # Duration of transition between slides (in ms)
  interval: 2000

content:
  slides:
    - title: 👋 Welcome to IEL
      content: Take a look at what we're working on...
      align: center
      background:
        position: right
        color: '#000'
        brightness: 0.7
        media: nagy-group-4.jpg
        fit: contain
    - title: Lunch & Learn ☕️
      content: 'Share your knowledge with the group and explore exciting new topics together!'
      align: left
      background:
        position: center
        color: '#000'
        brightness: 0.7
        media: research-methods.jpg
        fit: contain
    - title: World-Class Semiconductor Lab
      content: 'Just opened last month!'
      align: right
      background:
        position: center
        color: '#000'
        brightness: 0.5
        media: research-applications.jpg
        fit: contain
      link:
        icon: graduation-cap
        icon_pack: fas
        text: Join Us
        url: ../contact/
---
