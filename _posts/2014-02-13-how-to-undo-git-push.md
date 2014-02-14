---
layout: post
title:  How to undo git push
date:   2014-02-13 15:40:00
categories: git
---

If you "accidentally" push a commit to the remote, you can easy rollback changes by typing:

{% highlight bash %}
git push -f origin HEAD^:master
{% endhighlight %}

Use `HEAD^^` to reverse the 2 last changes (works *n* times).
