---
layout: default
---

<body>
  <div class="index-wrapper">
    <div class="aside">
      <div class="info-card">
        <h1>JerryLiu</h1>
        <a href="http://weibo.com/u/5237802868" target="_blank"><img src="http://www.weibo.com/favicon.ico" alt="" width="25"/></a>
        <a href="http://github.com/JerryLauzzz" target="_blank"><img src="/github.png"></a>
<!--         <a href="http://www.douban.com/people/beiyuu/" target="_blank">Git</a> -->
<!--         <img src="http://www.douban.com/favicon.ico" alt="" width="22"/> -->
<!--         <a href="http://instagram.com/JerryLiu/" target="_blank"><img src="http://d36xtkk24g8jdx.cloudfront.net/bluebar/00c6602/images/ico/favicon.ico" alt="" width="22"/></a> -->
      </div>
      <div id="particles-js"></div>
    </div>

    <div class="index-content">
      <ul class="artical-list">
        {% for post in site.categories.blog %}
        <li>
          <a href="{{ post.url }}" class="title">{{ post.title }}</a>
          <div class="title-desc">{{ post.description }}</div>
        </li>
        {% endfor %}
      </ul>
    </div>
  </div>
</body>
