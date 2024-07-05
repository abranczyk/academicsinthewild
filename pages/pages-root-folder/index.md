---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: "header-tiger-jungle-background-flip.jpg"
widget1:
  title: "Nonlinear careers"
  url: '/about'
  text: 'Academics in the Wild (AITW) is an initiative to support physicists and mathematicians on their nonlinear career adventure from academia to industry. Are you currently on any stage of this journey? If so, join us!'
  video: '<a href="#" data-reveal-id="videoModal2"><img src="./images/frontpage-aitw-title-page-screenshot-play.png" width="302" height="182" alt=""/></a>'
widget2:
  title: "Events"
  url: '/events/'
  image: frontpage-jungle-animals.png
  text: 'We believe that learning from each other is the best way to nagivate a career transition. We welcome you to our Discord server where we host informative and supportive events, including AMAs/Q&As with former academics who are now in industry, 1-1 coffee chats, workshops, and watch parties.'
widget3:
  title: "Physicists in the Wild"
  url: 'https://youtube.com/playlist?list=PLnwt2ODY2PX0hnUJgIwCwHSkPzH4J4fVX&si=9vLMk1CJqqb3z_xy'
  text: 'If you can see it you can be it. Join Aggie Branczyk as she interviews physicists who have turned their PhD training into diverse and often unconventional careers, from the corporate world to government, from education to finance, and more.'
  video: '<a href="#" data-reveal-id="videoModal"><img src="./images/frontpage-pitw-trailer-screenshot-emily-katiuscia-play.png" width="302" height="182" alt=""/></a>'

#
# Use the call for action to show a button on the frontpage
#
# To make internal links, just use a permalink like this
# url: /getting-started/
#
# To style the button in different colors, use no value
# to use the main color or success, alert or secondary.
# To change colors see sass/_01_settings_colors.scss
#
callforaction:
  url: https://forms.academicsinthewild.com/subscribe
  text: Subscribe to our mailing list
  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/fJ5oW9WiNTg" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>

<div id="videoModal2" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/eZv9o0Q5YMg" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
