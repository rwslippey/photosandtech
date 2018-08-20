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
  title: "Blog"
<<<<<<< HEAD
  url: '/blog'
  image: typewriter_blog.jpg
=======
  url: 'https://rwslippey.github.io/blog/'
  image: widget-1-302x182.jpg
>>>>>>> parent of 7769b9d... added image for blog's main page link
  text: 'Checkout my Blog! Here I cover a range of topics. Recent events, tech how to articles, reviews of different products and service and, just occasionally, I ramble.'
widget2:
  title: "Just show me the photos"
  image: outdoors-portrait-002.jpg
  url: '/portfolio/'
  text: 'This site is not intended to be a professional portfolio, just a fun place to put my thoughts down. I will however share some images from my personal projects and just images I plan like, here. For my portfolio, checkout my business website.'
widget3:
  title: "New to photography?"
  url: '/photography-getting-started/'
  image: Canon-60D-mode-dial.jpg
  text: "Checkout my series on photography 101 if you're just getting started in photography. You don't need any expensive equipment or much money at all really to make great images, just a camera and a little know how. Here I'll cover that know how to get you started on the path to making images. Plus I'll highlight some AWESOME teachers I've read and watched over the years."
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
  url: https://tinyletter.com/feeling-responsive
  text: Join the mailing list to get updates on new posts!
  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---
<!--REMOVE THIS VIDEO
<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/3b5zCFSmVvU" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
---bye bye video-->
