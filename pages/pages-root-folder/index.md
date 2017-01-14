---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: header_unsplash_12.jpg
widget1:
  title: "Jekyll Politico Posts"
  url: 'https://singularityhacker.github.io/Jekyll-Politico/blog/'
  image: widget-1-302x182.jpg
  text: 'Every news website claims objectivity but it that even possible? <em>Jekyll Politico</em> offers unfiltered plain talk about todays political horizon. Read all out recent posts here.'
widget2:
  title: "what is discrimination?"
  url: 'https://singularityhacker.github.io/Jekyll-Politico/info/'
  text: 'Liberty assuems your right to discriminate.<br/>1. Age<br/>2. Gender<br/>3. Race.<br/>4. Ability,...'
  video: '<a href="#" data-reveal-id="videoModal"><img src="https://singularityhacker.github.io/Jekyll-Politico/images/start-video-feeling-responsive-302x182.jpg" width="302" height="182" alt=""/></a>'
widget3:
  title: "Give us feedback"
  url: 'https://singularityhacker.github.io/Jekyll-Politico/design/comments/'
  image: widget-github-303x182.jpg
  text: '<em>Jekyll Politico</em> is new and we want your feedback. Give us your first impressions of the site. Then hit me up on Twitter <a href="http://twitter.com/phlow">@phlow</a>.'
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
  url: https://tinyletter.com/singularityhacker
  text: Inform me about updates ›
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
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/lfUVjbFQwxw" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
