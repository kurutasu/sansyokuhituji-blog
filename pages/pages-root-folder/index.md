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
  url: 'https://www.sansyokuhituji.com/blog/'
  image: widget-blog-450x450.jpg
  text: ''
widget2:
  title: "出店情報"
  url: 'https://www.sansyokuhituji.com/store_open_info/'
  image: widget-store_open_info-450x450.jpg
  text: ''
widget3:
  title: "キャラクター紹介"
  url: 'https://www.sansyokuhituji.com/character_introduction/'
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
