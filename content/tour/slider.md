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
    - title: 👋 Welcome to the group
      content: WeAI Research Group is dedicated to research related to artificial intelligence. As a start-up research group, we do not have sufficient computing resources, technical reserves, or financial support. However, this does not prevent us from loving AI research. 
      align: center
      background:
        position: right
        color: '#666'
        brightness: 0.7
        media: coders.jpg
    - title: Lunch & Learn ☕️
      content: 'Our limitations make us realize that there are many researchers who are also interested in AI research but who also face the dilemma of inadequate support. Therefore, our group was established to pursue the following goals. First, we are committed to researching and promoting AI technologies that are applicable to low hardware conditions. Secondly, we hope to create a technological communication platform to start timely communication with our peers. Finally, we welcome you to join our group and expand the boundaries of technology applications together.'
      align: left
      background:
        position: center
        color: '#555'
        brightness: 0.7
        media: contact.jpg
    - title: The most liberal and enthusiastic research group
      content: 'Obviously, our group is still at an initial stage where we can only produce simple models and publish simple journal and conference papers. However, we will keep our hobby of AI alive and well. Whether you are an expert, a student, or even an amateur, we look forward to talking with you!'
      align: right
      background:
        position: center
        color: '#333'
        brightness: 0.5
        media: welcome.jpg
      link:
        icon: graduation-cap
        icon_pack: fas
        text: Join Us
        url: ../contact/
---
