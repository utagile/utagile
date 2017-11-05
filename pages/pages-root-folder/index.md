---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: background.png
widget1:
  title: "Product Owners"
  url: 'http://localhost:4000/feeling-responsive/images/'
  image: product_owner.png
  text: 'We hold quarterly meetups for Product Owners, Project Managers, Product Managers, and those responsible for the guidance of software development teams. Come explore topics like effective user story splitting, multi-project coordination, and relentless prioritization.'
widget2:
  title: "Scrum Masters"
  url: 'http://phlow.github.io/feeling-responsive/info/'
  image: Scrummaster.png
  text: 'Do you help development teams get the most out of Agile / Scrum practice? Come join our quarterly meetup to discuss team building activities, conflict resolution, and facilitation, and other core Scrum Master skills. '
widget3:
  title: "Developers"
  url: 'https://github.com/Phlow/feeling-responsive'
  image: Developer.png
  text: 'Developers need Agile education and skill building as much as anyone! Come join any of our regular meetups and learn from fellow developers, DevOps practitioners, and business analysts. Agile isnt just for Product Owners and Scrum Masters.'
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
  url: https://meetup.com/utagile
  text: Join one of our Meetups ›
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
