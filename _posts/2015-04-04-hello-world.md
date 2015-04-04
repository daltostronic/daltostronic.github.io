---
layout: post
title: Hello World!
description: "Just some welcome post."
tags: [hello world]
image:
  feature: abstract-7.jpg
  credit: dargadgetz
  creditlink: http://www.dargadgetz.com/ios-7-abstract-wallpaper-pack-for-iphone-5-and-ipod-touch-retina/
---

Here be a sample post with a custom background image. To utilize this "feature" just add the following YAML to a post's front matter.

{% highlight cpp %}
void main()
{
	printf("Hello World!");
}
{% endhighlight %}

This little bit of YAML makes the assumption that your background image asset is in the `/images` folder. If you place it somewhere else or are hotlinking from the web, just include the full http(s):// URL. Either way you should have a background image that is tiled.

If you want to set a background image for the entire site just add `background: filename.png` to your `_config.yml` and BOOM --- background images on every page!
