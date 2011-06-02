---
layout: default
title: Index
---

# Welcome to the Ruby User Group Speaker Exchange

We are in the process of setting up the project. A work in progress description of it can be found on [google docs](https://docs.google.com/document/d/1svmhGQkjFJxahxnXm1eKarfB0gX_xekjYvum4jOJWAE/edit?hl=en_US). 

The following user groups have joined so far:

* [Amsterdam - Netherlands](http://amsterdam-rb.org/) (Josh Kalderimis)
* Barcelona - Spain (Christian Amor)
* [Berlin - Germany] (http://rug-b.de) (Thilo Utke)
* [Edinburgh - Scotland](http://scotrug.org/) (Paul Wilson)
* [London - UK](http://lrug.org/) (Murray Steele)

If you want to support the exchange by sponsoring or participation please join the [Google Group](http://groups.google.com/group/usergroup-speaker-exchange).

# Updates

{% for post in site.posts %}

### {{post.title}}
<p class="meta">published {{post.date | date: "%B %d, %Y"}}</p>

{{post.content}}

{% endfor %}

