---
layout: default
title: Index
---

# Welcome to the Ruby User Group Speaker Exchange

The Ruby User Group Speaker Exchange connects Ruby User Groups throughout Europe. What does this mean?

* Enable traveling Rubyists to get in touch with local user groups at their destination to join their meetups and encourage them to present as well.
* Connect speakers that like to present their topic to other user groups with local organizers and prospect sponsors to get support for travel expanses.
* Encourage underrepresented groups to present abroad by funding their trips.
* Build speaker confidence by giving inexperienced speakers the opportunity to talk to a international audience before appearing at big conferences.
* Bring the Ruby community closer together
* Making user groups more attractive to new members

The following user groups have joined so far:

* [Amsterdam - Netherlands](http://amsterdam-rb.org/) (Josh Kalderimis)
* [Berlin - Germany](http://rug-b.de) (Thilo Utke)
* [Edinburgh - Scotland](http://scotrug.org/) (Paul Wilson)
* [Krakow - Poland](http://www.ruby.org.pl/) (Maciej Książek)
* [London - UK](http://lrug.org/) (Murray Steele)
* [Stockholm - Sweden](http://rails.se/rails/show/HomePage)
* [Surrey - UK](http://surreyrubyists.tumblr.com)
* [Tallinn - Estonia](http://ruby.ee/en) (Priit Tamboom)

## Contribute to the Ruby User Group Speaker Exchange

The Exchange is just about to start so there is still much help needed to get it of the ground.

There are two ways to support the Ruby User Group Speaker Exchange:

* As a volunteer, e.g. helping out with the website, getting new sponsors, being a free roaming speaker (traveling and speak at your own expenses), accommodate travelling speakers, etc.
* As a sponsor, to help us pay for flights and accommodation for traveling speakers

If you want to support the exchange get in touch via the user group [Google Group](http://groups.google.com/group/usergroup-speaker-exchange) or write an email to thilo at upstre dot am.

## Recent updates

{% for post in site.posts limit:1%}

### {{post.title}}
<p class="meta">published {{post.date | date: "%B %d, %Y"}}</p>

{{post.content}}

{% endfor %}


<a id="archive" href="/archive.html">&raquo; more updates</a>

