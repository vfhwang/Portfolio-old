---
layout: default
---


<section class="bio">
  <img alt="Victor Hwang Portrait" src="assets/victorPortrait.png">
  <div class="bio1"><p>{{ site.description }}</p></div>
  <ul class="sociallinks"><li>— <a target="_blank" href="#">{{ site.email }}</a> </li><li>— <a target="_blank" href="#">{{ site.twitter_username }}</a></li></ul>
</section>

<div class="sectiontitle"><h2><span class="decorativetext" aria-hidden="true">¸,ø¤º°`°º¤ø,¸,ø¤°º¤ø,¸¸,ø¤º°`°º¤ø,¸ </span>Project notes<span class="decorativetext" aria-hidden="true"> ¸,ø¤º°`°º¤ø,¸,ø¤°º¤ø,¸¸,ø¤º°`°º¤ø,¸</span></h2></div>
<section class="projects">

  {% for post in site.categories[project notes] %}

  <div class="projectitem">
    <div style="background-color:#{{ post.colour }}" class="project logo parliament"><img alt="UK Parliament logo" src="assets/{{ post.image }}"></div>
    <div class="descriptivetext"><h3>{{ post.year }} {{ post.title }}</h3><p>{{ post.description }}
      <a href="{{ post.url }}">Read more</a>
    </p></div>
  </div>

  {% endfor %}

  <div class="projectitem">
    <div class="project logo parliament"><img alt="UK Parliament logo" src="assets/parliamentlogo.svg"></div>
    <div class="descriptivetext"><h3>a.a.a - UK Parliament</h3><p> First steps in a new website for Parliament, which aims to bring people closer to their MPs, Lords and ultimately democracy.
    </p></div>
  </div>

  <div class="projectitem">
  <div class="project logo iplayer"><img alt="UK Parliament logo" src="assets/iplayerlogo.svg"></div>
  <div class="descriptivetext"><h3>b.b.b - iPlayer</h3><p>A brief look at the journey towards a better iPlayer homepage.
  </p></div>
</div>
</section>

<div class="sectiontitle"><h2><span class="decorativetext" aria-hidden="true">(¯`·._.·(¯`·._.·(¯`·._.·(¯`·._.·(¯`·._.·(¯`·._.· </span>Things made<span class="decorativetext" aria-hidden="true"> ·._.·´¯)·._.·´¯)·._.·´¯)·._.·´¯)·._.·´¯)·._.·´¯)  </span></h2></div>
<section class="projects">

</section>
