---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: header.png
widget2:
  title: "People"
  url: https://thepoliticsofinformalgovernance.github.io//people/
  text: "Learn more about who's involved in this project."
widget1:
  title: "About the Project"
  url: https://thepoliticsofinformalgovernance.github.io//project/
  text: "Learn more about the goals of this project."
widget3:
  title: "Data"
  url: https://thepoliticsofinformalgovernance.github.io//data/
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
