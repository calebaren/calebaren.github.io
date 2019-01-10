---
# layout: post, default, no-sidebar, etc.
# title: "Blog title"
# subtitle: "Keep it short."
# date:   YYYY-MM-DD 23:59:59 -0800
# categories: two atmost
# headerphoto: "header1.jpg" <-- case matters!
layout: no-sidebar
title: "Hello World!"
subtitle: "Short and sweet."
categories:
header_photo: "header1.jpg"
---
This is my first blog post. I've never blogged before. I have limited experience using Markdown so I'm utterly terrified. But here goes.

I've included a bunch of reference text down below. I'm still playing around with the formatting and the CSS so please bear with me here. [View the markdown used to create this post](https://raw.githubusercontent.com/barryclark/www.jekyllnow.com/gh-pages/_posts/2014-6-19-Markdown-Style-Guide.md). This is a paragraph, it's surrounded by whitespace. Next up are some headers, they're heavily influenced by GitHub's markdown style.

## Use this header.
 
A link to [Jekyll Now](http://github.com/barryclark/jekyll-now/). A big ass literal link <http://github.com/barryclark/jekyll-now/> An image, located within /images:

<a href class="image fit"><img src="{{ site.baseurl }}/images/header.jpg" alt="an image title" /></a>

* A bulletted list
- alternative syntax 1
+ alternative syntax 2
  - an indented list item

1. An
2. ordered
3. list

- _italics_
- **bold**
- 'code()'
 
> Blockquote
>> Nested Blockquote 
 
Syntax highlighting can be used by wrapping your code in a liquid tag like so:

{{ "{% highlight javascript " }}%}  
/* Some pointless Javascript */
var rawr = ["r", "a", "w", "r"];
{{ "{% endhighlight " }}%}  

creates...

{% highlight javascript %}
/* Some pointless Javascript */
var rawr = ["r", "a", "w", "r"];
{% endhighlight %}
 
Use two trailing spaces  
on the right  
to create linebreak tags  

<script src="http://gist.github.com/1943530.js"></script>
 
Finally, horizontal lines