---
layout: post
title: Migration to GitHub
tags: site github news bootstrap sass
---

Since I created this website I always thought that a future migration to [GitHub](https://github.com) would be 
required to minimize maintenance, streamline the push procedure and increase the reliability.

The setup on a dedicated server was a great lesson that taught me how to deal with Jekyll. Having had some spare time 
I decided to perform the migration and knowing that GitHub runs Jekyll in safe mode (custom ruby code doesn't work), I 
replaced the [Tag Generator plugin](https://github.com/danieldevries/jekyll-tag-generator) with a simple, static 
[Tag page](http://ciroprincipe.info/blog/tags/).

I took advantage of the situation and I replaced also the static [Bootstrap](http://getbootstrap.com/) CSS with its 
[SASS enabled version](https://github.com/twbs/bootstrap-sass). Next step will be to customize the resume and project 
pages with a nicer (but minimal) compatible template.