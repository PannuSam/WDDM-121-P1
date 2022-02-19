---
title: Ruhe
layout: "index.njk"
---
<div class="intro">
Hey!<br>Thank you for visiting.<br><br> This is my very first blog and I want to share my opinion and thoughts with you on different topics.
</div>
<div>
<ul>
{% for post in collections.posts %}
 <li>
 
 <figure class="music-img">
        <img src="{{ post.data.path }}" alt="Sorry! Something went wrong.">
 </figure>
 <a href="{{ post.url }}" class="img-data">
 {{ post.data.title }}
 </a>
 </li>
{% endfor %}

</ul>
</div>