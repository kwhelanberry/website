---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: percheader.jpg
widget1:
  title: "Personal Coaching"
  url: 'coaching/'
  image: coaching.jpg
  text: 'I help individuals take steps to be their ideal selves every day, based on a strong foundation in positive psychology. I offer one-on-one personal coaching sessions in the Rhode Island area.'
widget2:
  title: "Consulting for Teams"
  url: 'consulting/'
  text: 'For a team to be most productive, it has to be more than just a group of people. I offer consulting for teams that enables them to work together on another level.'
  image: 'team.jpg'
widget3:
  title: "About Me"
  url: 'about/'
  image: karen.jpg
  text: 'I have many years of both academic and professional experience with positive psychology and team building, and I look forward to helping you apply their core principles for better personal or professional results.'
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
scallforaction:
  url: https://tinyletter.com/feeling-responsive
  text: Inform me about new updates and features ›
  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

<!-- <div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/3b5zCFSmVvU" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div> -->
