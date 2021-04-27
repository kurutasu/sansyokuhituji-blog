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
  title: "ブログ"
  url: '/blog/category/blog/'
  image: widget-blog-450x450.jpg
  text: ''
widget2:
  title: "イベント情報"
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

## SNSリンク

### Twitter

<a class="twitter-timeline" data-chrome="transparent noheader nofooter  noborders noscrollbar" data-width="400" data-height="500" href="https://twitter.com/sansyokuhituji?ref_src=twsrc%5Etfw" >Tweets by sansyokuhituji</a> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

### facebook

<div id="fb-root"></div>
<script async defer crossorigin="anonymous" src="https://connect.facebook.net/ja_JP/sdk.js#xfbml=1&version=v10.0" nonce="Ho8N2uoW"></script>
<div class="fb-page" data-href="https://www.facebook.com/sansyokuhituji/" data-tabs="timeline" data-width="400" data-height="500" data-small-header="true" data-adapt-container-width="true" data-hide-cover="false" data-show-facepile="false"><blockquote cite="https://www.facebook.com/sansyokuhituji/" class="fb-xfbml-parse-ignore"><a href="https://www.facebook.com/sansyokuhituji/">三色ひつじ</a></blockquote></div>