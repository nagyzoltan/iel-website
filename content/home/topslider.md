widget: slider  # Use the Slider widget as this page section
weight: 1  # Position of this section on the page
active: true  # Publish this section?
headless: true  # This file represents a page section.

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
    - title: 👋 Welcome to the group
      content: Take a look at what we're working on...
      align: center
      background:
        position: right
        color: '#666'
        brightness: 0.7
        media: nagy-group-4.jpg
        fit: cover
    - title: Research Methods ☕️
      content: 'We work in all areas of machine learning applied to the built environment!'
      align: left
      background:
        position: center
        color: '#555'
        brightness: 0.7
        media: research-methods.jpg
        fit: cover
    - title: Teaching
      content: 'Check out our courses'
      align: right
      background:
        position: center
        color: '#333'
        brightness: 0.5
        media: DSC0038.jpg
        fit: cover
      link:
        icon: graduation-cap
        icon_pack: fas
        text: Join Us
        url: ../contact/
