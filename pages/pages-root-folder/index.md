---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: header.png
widget1:
  title: "News"
  url: "https://ThePoliticsOfInformalGovernance.github.io/news"
  text: "Read all the news regarding this project including data updates, new papers and upcoming events."
widget2:
  title: "About the Project"
  url: ""
  text: "Teaser including main goals of the project..."
widget3:
  title: "Data"
  url: ""
  text: "Download the data collected by this project and use it for your own research."
#
# Use the call for action to show a button on the frontpage
#
# To make internal links, just use a permalink like this
# url: /getting-started/
#
# To style the button in different colors, use no value
# to use the main color or success, alert or secondary.
# To change colors see sass/_01_settings_colors.scss
# Make newsletter with tinyletter. But maybe Twitter is more useful...

callforaction:
  url: https://tinyletter.com
  text: Inform me about new updates and features ›
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
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/3b5zCFSmVvU" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
