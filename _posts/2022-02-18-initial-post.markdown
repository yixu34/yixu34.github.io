---
layout: post
title:  "Python reflection"
date:   2022-02-18 22:27:37 -0800
---
I've been interested lately in how various Python libraries serialize ordinary functions and classes
into artifacts that can be run on remote machines. This technique bridges the gap between local
development and scalable production services. It also forms the underpinning of popular
scalable Python compute frameworks like pySpark and Ray. I wanted to write this post to serve
as a notebook of my deep dive into this topic, along with all of the edge cases and gotchas that
one might run into.

# Pickle
First, there's the `pickle` module in the Python standard library.


{% highlight python %}
if
{% endhighlight %}

