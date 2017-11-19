---
layout: post
title: "Disqus and open graph"
date: 2017-11-18 21:01 +0100
categories: blogpost
---

I used Disqus too implement comments on my web page. I went to the Disqus website an followed the instructions to install comments for a jekyll site.
It was a struggle at first to figure out how to paste in the generated code Disqus gave me but then i researched how and I solved it.

Open graph enables any web page to turn into graph objects. You need to add basic metadata to your page using the "meta" tag in the "head" of your web page.
There is four required properties for every page and those are "title", "type", "image" and "url". It's supposed to look something like this.

{% highlight ruby %}
<meta property="og:title" content="whatever" />
<meta property="og:type" content="whatever" />
<meta property="og:url" content="a url for your site" />
<meta property="og:image" content="an image of your chosing" />
{% endhighlight %}