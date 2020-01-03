---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  #image_fullwidth: pattern_concrete_high.jpg
    image:  "image-with-logo.png"
    pattern:  "pattern_concrete.jpg"
widget1:
  title: "Our Workshops"
  url: 'https://escience-academy.github.io/'
  image: workshops.jpg
  text: 'Our workshops are hands on and interactive. Learn how to efficiently process, visualise and analyse your data.'
widget2:
  title: "Our Lessons"
  url: '/lessons/'
  image: python.jpg
  text: 'Our lessons are developed in collaboration with the wider community of experts or based on other  training materials developed by wider Carpentries community.'

widget3:
  title: "Our Trainers"
  url: 'https://carpentries.org/community/'
  image: trainers.jpg
  text: 'Our workshops are taught by the expert research sofotware engineers from the Netherlands eScience Center, who are also certified Carpentries instructors.'
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
old_callforaction:
  old_url: https://tinyletter.com/feeling-responsive
  ext: Inform me about new updates and features ›
  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

