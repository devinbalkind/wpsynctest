---
ID: 1846
post_title: GNU social and cities
author: Manuel Ortega
post_date: 2015-12-18 10:59:05
post_excerpt: |
  <p>The SocialCapital plugin is a key piece for the promotion of GNU social as an operating system for cities. Overcoming the limitation of seeing GNU social as a mere alternative to centralized services like Facebook or Twitter was the most important contribution of the first GNU social camp. With this limitation overcome, GNU social becomes [&hellip;]</p>
  <p>The post <a rel="nofollow" href="http://blog.p2pfoundation.net/gnu-social-and-cities/2015/12/18">GNU social and cities</a> appeared first on <a rel="nofollow" href="http://blog.p2pfoundation.net/">P2P Foundation</a>.</p>
layout: post
permalink: >
  http://flolab.org/wp3/2015/12/18/gnu-social-and-cities/
published: true
enclosure:
  - |
    |
        
        
        
syndication_source:
  - P2P Foundation
syndication_source_uri:
  - http://blog.p2pfoundation.net
syndication_source_id:
  - >
    http://feeds.feedburner.com/P2pFoundation
"wfw:commentRSS":
  - >
    http://blog.p2pfoundation.net/gnu-social-and-cities/2015/12/18/feed
syndication_feed:
  - >
    http://feeds.feedburner.com/P2pFoundation
syndication_feed_id:
  - "2"
syndication_permalink:
  - >
    http://feedproxy.google.com/~r/P2pFoundation/~3/M2tZ1RxlnQw/18
syndication_item_hash:
  - bb8fdbd58caa7ac50b8caa7dc500c62a
---
<img class="aligncenter size-full wp-image-53111" src="http://blog.p2pfoundation.net/wp-content/uploads/sharingcitiesseminar.jpg" alt="sharingcitiesseminar" width="850" height="478" />

### <span style="color: #808080">The SocialCapital plugin is a key piece for the promotion of GNU social as an operating system for cities.</span>

* * *

Overcoming the [limitation of seeing GNU social as a mere alternative to centralized services][1] like Facebook or Twitter was the most important contribution of the first GNU social camp. With this limitation overcome, [GNU social becomes a platform][2] on which we can build a thousand social and distributed applications.

The first set of applications designed with this thinking aim to offer a new operating system for cities. This is a new operating system meant to facilitate and drive participation and interaction between the people in a neighborhood, and, through federation, in the city. In the end, it’s about promoting social cohesion.

> Let’s imagine for a second that we will create a system of rules to measure those interactions and estimate their impact on the community. Let’s imagine that a good part of that virtual skin of sharing is blended with neighborhoods, with neighborhood spaces that have their own nodes. We could at least have a index and a series of indicators of social capital in each neighborhood. Additionally, we could measure how the actions of an NGO influence social capital in its surroundings, or how incentivizing exchanges between two cities has an influence on the wealth of your neighbors. Let’s add to all this Juan’s latest reflections, returning to the relationship between common knowledge and social change. Far beyond “karma” or “popularity,” having a measure of what freely is shared would allow any city agent to have a much more effective plan of social action.

The development and specifications of this index us brings us to the first component in this set of applications: SocialCapital.

In a [first][3][ development][3][ effort][3], we have created the basic structure of this plug-in and some early functionality. The core of this plug-in is the class *SocialCapitalIndex* where queries on users’ interaction are encapsulated and each one of them is assigned an index of social capital provided to the network. The early functionality of the plugin adds the index created by the class *SocialCapitalIndex *to the profile of each user.

In parallel to this early development effort, we’ve also written a [first specifications document for the development of SocialCapital][4].

Starting from this first version of SocialCapital and its specifications document, our objective is to open up development of this important piece for the promotion of [GNU social as an operating system for cities][5].

Among the next steps to continuing development are the improvement of current database queries, interaction, and visualization in Qvitter. But, the most important point is designing and improving the algorithm that creates the user index, or, as Andrés commented on GNU social, we want to have a number or set of labels associated with each user. Also, we would have to consult and evaluate other similar algorithms that can serve as a guide–for example, the [reputation ][6][system][6][ at Stack Overflow][6].

*Translated by [Steve Herrick][7] from <a title="GNU social y las ciudades" href="https://lasindias.com/gnu-social-y-las-ciudades" rel="bookmark">the original</a> (in Spanish)*

<a class="a2a_button_facebook" href="http://www.addtoany.com/add_to/facebook?linkurl=http%3A%2F%2Fblog.p2pfoundation.net%2Fgnu-social-and-cities%2F2015%2F12%2F18&linkname=GNU%20social%20and%20cities" title="Facebook" rel="nofollow"><img src="http://blog.p2pfoundation.net/wp-content/plugins/add-to-any/icons/facebook.png" width="16" height="16" alt="Facebook" /></a><a class="a2a_button_twitter" href="http://www.addtoany.com/add_to/twitter?linkurl=http%3A%2F%2Fblog.p2pfoundation.net%2Fgnu-social-and-cities%2F2015%2F12%2F18&linkname=GNU%20social%20and%20cities" title="Twitter" rel="nofollow"><img src="http://blog.p2pfoundation.net/wp-content/plugins/add-to-any/icons/twitter.png" width="16" height="16" alt="Twitter" /></a><a class="a2a_button_google_plus" href="http://www.addtoany.com/add_to/google_plus?linkurl=http%3A%2F%2Fblog.p2pfoundation.net%2Fgnu-social-and-cities%2F2015%2F12%2F18&linkname=GNU%20social%20and%20cities" title="Google+" rel="nofollow"><img src="http://blog.p2pfoundation.net/wp-content/plugins/add-to-any/icons/google_plus.png" width="16" height="16" alt="Google+" /></a><a class="a2a_button_reddit" href="http://www.addtoany.com/add_to/reddit?linkurl=http%3A%2F%2Fblog.p2pfoundation.net%2Fgnu-social-and-cities%2F2015%2F12%2F18&linkname=GNU%20social%20and%20cities" title="Reddit" rel="nofollow"><img src="http://blog.p2pfoundation.net/wp-content/plugins/add-to-any/icons/reddit.png" width="16" height="16" alt="Reddit" /></a><a class="a2a_dd a2a_target addtoany_share_save" href="https://www.addtoany.com/share#url=http%3A%2F%2Fblog.p2pfoundation.net%2Fgnu-social-and-cities%2F2015%2F12%2F18&title=GNU%20social%20and%20cities" id="wpa2a_2"><img src="http://blog.p2pfoundation.net/wp-content/plugins/add-to-any/share_save_120_16.png" width="120" height="16" alt="Share" /></a>

The post <a rel="nofollow" href="http://blog.p2pfoundation.net/gnu-social-and-cities/2015/12/18">GNU social and cities</a> appeared first on <a rel="nofollow" href="http://blog.p2pfoundation.net/">P2P Foundation</a>.

<div class="feedflare">
  <a href="http://feeds.feedburner.com/~ff/P2pFoundation?a=M2tZ1RxlnQw:TPRT36rcMRo:7Q72WNTAKBA"><img src="http://feeds.feedburner.com/~ff/P2pFoundation?d=7Q72WNTAKBA" border="0" /></img></a> <a href="http://feeds.feedburner.com/~ff/P2pFoundation?a=M2tZ1RxlnQw:TPRT36rcMRo:D7DqB2pKExk"><img src="http://feeds.feedburner.com/~ff/P2pFoundation?i=M2tZ1RxlnQw:TPRT36rcMRo:D7DqB2pKExk" border="0" /></img></a> <a href="http://feeds.feedburner.com/~ff/P2pFoundation?a=M2tZ1RxlnQw:TPRT36rcMRo:2mJPEYqXBVI"><img src="http://feeds.feedburner.com/~ff/P2pFoundation?d=2mJPEYqXBVI" border="0" /></img></a>
</div>

<img src="http://feeds.feedburner.com/~r/P2pFoundation/~4/M2tZ1RxlnQw" height="1" width="1" alt="" />

 [1]: http://litox.entramado.net/2015/12/01/gnu-social-la-plataforma-social/
 [2]: https://lasindias.com/gnu-social-como-motor-de-ostatus
 [3]: http://bitujo.enkidu.coop/manuel/SocialCapital
 [4]: https://lasindias.com/indianopedia/social-capital-plugin-de-gnu-social
 [5]: https://lasindias.club/gnu-social-camp-2015/
 [6]: http://stackoverflow.com/help/whats-reputation
 [7]: http://level.interpreters.coop/