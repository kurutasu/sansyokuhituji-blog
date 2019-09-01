---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage

header:
  title: ""
  image_fullwidth: header.jpg
  
widget1:
  title: "Blog・イベント報告"
  url: '/blog/category/blog/'
  image: widget-blog-450x450.jpg
  text: ''
widget2:
  title: "出展情報"
  url: '/blog/category/event/'
  image: widget-store_open_info-450x450.jpg
  text: ''
widget3:
  title: "キャラクター紹介"
  url: '/character/'
  image: widget-character_introduction-450x450.jpg
  text: ''
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

#callforaction:
#  url: https://store.line.me/search/ja?q=%E4%B8%89%E8%89%B2%E3%81%B2%E3%81%A4%E3%81%98
#  text: LINE スタンプ STORE ›
#  style: success

permalink: /index.html

#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

### Instagram Gallery
<!-- InstaWidget -->
<a href="https://instawidget.net/v/user/sansyokuhituji" id="link-0fa728fa86adfc5bd45363d61ace2e368fe1968564329420444b0d1811c81a97">@sansyokuhituji</a>
<script src="https://instawidget.net/js/instawidget.js?u=0fa728fa86adfc5bd45363d61ace2e368fe1968564329420444b0d1811c81a97&width=1000px"></script>

### Twitter Timeline
<a class="twitter-timeline" data-chrome="transparent noheader nofooter  noborders noscrollbar" data-width="1000" data-height="400" href="https://twitter.com/sansyokuhituji?ref_src=twsrc%5Etfw" >Tweets by sansyokuhituji</a> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>