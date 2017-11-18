---
layout: post
title:  "robots.txt and how i did it"
date:   2017-11-14 12:22:44 +0100
categories: blogpost
---
Robot.txt is a text file that sets what search-engines look for when they search for your web page. Search-engines look automatically for your robots.txt to look what you have allowed.
This file is important to put in your root directory.
{% highlight ruby %}
User-agent:*
Disallow:/whatever/
Disallow:/whatever2/
{% endhighlight %}


