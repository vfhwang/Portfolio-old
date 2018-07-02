---
layout: default
---

<header class="sectiontitle">
  <h1><span class="decorativetext l" aria-hidden="true">`'-.,_,.-'``'-.,_,.='``'-.,_,.-'``'-.,_,.='` </span>
  {{ site.title }}
  <span class="decorativetext r" aria-hidden="true"> `'-.,_,.='``'-.,_,.-'``'-.,_,.='``'-.,_,.-'`</span></h1>
</header>

<section class="bio">
  <div class="biogrid1"><img alt="Victor Hwang Portrait" src="assets/victorPortrait.png"></div>
  <div class="biogrid2"><p>{{ site.description }}</p></div>
  <div class="biogrid3">
    <ul class="sociallinks">
      <li>— <a target="_blank" href="#">{{ site.email }}</a> </li>
      <li>— <a target="_blank" href="#">{{ site.twitter_username }}</a></li>
    </ul>
  </div>
</section>


<div class="sectiontitle">
  <h2><span class="decorativetext l" aria-hidden="true">¸,ø¤º°`°º¤ø,¸,ø¤°º¤ø,¸¸,ø¤º°`°º¤ø,¸ </span>
  Project notes
  <span class="decorativetext r" aria-hidden="true"> ¸,ø¤º°`°º¤ø,¸,ø¤°º¤ø,¸¸,ø¤º°`°º¤ø,¸</span></h2>
</div>
<section class="projects">

  {% for post in site.categories[project notes] %}

  <!-- <div class="project"> -->
    <div style="background-color:#{{ post.colour }}" class="projectlogo"><img alt="" src="assets/{{ post.image }}"></div>
    <div class="projectdescription"><h3>{{ post.year }} — {{ post.org }}</h3><p>{{ post.description }}
      <a href="{{ post.url }}">Read more</a>
    </p></div>
  <!-- </div> -->

  {% endfor %}


</section>

<!-- <div class="sectiontitle"><h2><span class="decorativetext" aria-hidden="true">(¯`·._.·(¯`·._.·(¯`·._.·(¯`·._.·(¯`·._.·(¯`·._.· </span>Things made<span class="decorativetext" aria-hidden="true"> ·._.·´¯)·._.·´¯)·._.·´¯)·._.·´¯)·._.·´¯)·._.·´¯)  </span></h2></div>
<section class="projects">

</section> -->
