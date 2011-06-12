---
layout: default
title: Index
---

# Welcome to the Ruby User Group Speaker Exchange

We are in the process of setting up the project. A work in progress description of it can be found on [google docs](https://docs.google.com/document/d/1svmhGQkjFJxahxnXm1eKarfB0gX_xekjYvum4jOJWAE/edit?hl=en_US). 

The following user groups have joined so far:

* [Amsterdam - Netherlands](http://amsterdam-rb.org/) (Josh Kalderimis)
* [Berlin - Germany] (http://rug-b.de) (Thilo Utke)
* [Edinburgh - Scotland](http://scotrug.org/) (Paul Wilson)
* [London - UK](http://lrug.org/) (Murray Steele)
* [Surrey - UK](http://surreyrubyists.tumblr.com)
* [Tallinn - Estonia](http://ruby.ee/en) (Priit Tamboom)



If you want to support the exchange by sponsoring or participation please join the [Google Group](http://groups.google.com/group/usergroup-speaker-exchange).


## Recent updates

{% for post in site.posts limit:1%}

### {{post.title}}
<p class="meta">published {{post.date | date: "%B %d, %Y"}}</p>

{{post.content}}

{% endfor %}


<a id="archive" href="/archive.html">&raquo; more updates</a>

