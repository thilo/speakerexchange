<h2>Latest update</h2>

{% for post in site.posts limit:1%}
<div class="post">
<h3>{{post.title}}</h3>
  <p>published {{post.date | date: "%B %d, %Y"}}</p>
  <div class="content">
  {{post.content}}
  </div>
</div>
{% endfor %}

<a href="/archive.html">&raquo; See all updates</a>
