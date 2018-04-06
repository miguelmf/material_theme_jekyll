---
layout: post
title:  "Changes I made to the default material theme"
date:   2018-04-06 00:00:00 +0000
tags: ['theme', 'jekyll']
author: "miguelmf"
---

Hey there,

I've been looking for an easy to use theme for a personal site (which I will most likely not actively use) and I came across a jekyll theme called *material*. Jekyll is a pretty nice and easy to use static site generator. Another alternative to jekyll is *hugo*, which is also great. You can't go wrong with either one. 

So, the material theme is made by lukas-h and is hosted on github (https://github.com/lukas-h/material-theme). It is MIT licensed. 

I've made some changes to it in order to use it as my own personal site. Here's what I changed:

1. Disabled google-analytics (I'm pretty averse to tracking and I effectively use browser add-ons in order to safely browse the internet. It would be pretty hypocrite of me to have GA on my own website);
2. Changed to a dark/night mode (I usually prefer dark background in pretty much everything I do on the computer. Helps with vision and hides the annoying dead pixels);
3. Increased paragraph's width (I find the default width to be too narrow);
4. Added support for mathjax (I come from a background where math is often used. Having support for latex is a must);
5. Added an **about** page (The content of this page is, however, directly written in the .html file. I would like to have an about.md on the root directory instead, but I couldn't make it work. If you know how, please let me know);
6. Several changes to the Posts menu (removed the small paragraph below each post, brought the titles closer together, added "»»" for eye guidance, etc);
7. Changed coloring of the buttons, when active and when inactive;
8. Hid the bottom bar (I'd rather add those links in the about page);

And that is all I can remember. Please check out the original theme in [https://github.com/lukas-h/material-theme](https://github.com/lukas-h/material-theme). [lukas-h](https://github.com/lukas-h) did great here and he also has other nice themes. Check him out.

If you want to use a dark version of lukas' material theme, with a few other changes, you can either edit lukas' theme, as I did, or you can fork/clone my repo. Be aware, however, that I know nothing of html and css and so the code (my part) is probably a mess.
