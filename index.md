---
layout: default
title: Getting Started
quote: The essential part of creativity is not being afraid to fail.
cite: Edwin H. Land
---

This example is just meant to get you started and show you a little of what's
possible with GitHub Pages. In just 3 simple steps, you will have your own
website.

1. [Create a Github account](https://github.com/join)
2. [Fork this repository](https://github.com/chesshacker/tamuhack/fork)
3. Edit the `_config.yml` file

{% highlight yaml %}
title: {{ site.title }}
description: >
  {{ site.description | rstrip }}
baseurl: "{{ site.baseurl }}" # the subpath of your site
url: "{{ site.url }}"
email: {{ site.email }}
github_username:  {{ site.github_username }}
linkedin_username: {{ site.linkedin_username }}
twitter_username: {{ site.twitter_username }}
{% endhighlight %}

That's it! You should now have a website of your own.

https://`your github username`.github.io/tamuhack/

There's so much more you can do with GitHub Pages, so don't stop here.
Explore the code in this project and start making it your own.
Continue on to the [Resources]({{ "/resources" | prepend: site.baseurl }})
section to learn more about GitHub Pages and other handy tools.

If you have questions, please look for me at the hackathon. I am here to help!
