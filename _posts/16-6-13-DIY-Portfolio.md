---
layout: post
title:  DIY Portfolio
date:   2016-6-13
---
![Jekyll Logo](/assets/img/jekyll.png)

As a designer in the modern age you’ll be faced with a dilemma at some point: should I use a portfolio builder or code my own site? If you have any web programming experience I would highly recommend the latter. It’s quite simple to do, and not too monotonous if you use the correct development environment. It will distinguish your brand from the hundreds hosted on sites like ArtStation, Squarespace, or Carbonmade. Also you can cater the experience to exactly what your work represents. Above all though you’ll force yourself to learn some new techniques in design and you most definitely will have to think critically about your audience and the best environment to showcase your life’s work.

So where to start?

If you’re new or just need a refresher, just check out some web design courses over at [Codecademy](https://www.codecademy.com/){:target="_blank"}. If you already know the basics I recommend using [Sass](http://sass-lang.com/){:target="_blank"} to simplify and clean up your CSS. It makes wide-range changes to colors, values, and settings easy, as it revolves around using variables and leverages the strengths of object oriented programming (even has its own set of custom functions).

If you want to simplify the entire process you can even pick up [Jekyll](http://jekyllrb.com/){:target="_blank"} which has automatic sass compiling and a lot of nifty plugins to help out. Using Jekyll, you can deploy your site for free onto GitHub Pages, which is a huge plus since you only have to keep a single repository that GH-Pages references directly, making site updates simpler and safer than using an FTP. Also Jekyll’s affinity for blogs makes it perfect for adding new pages and iterating without much hassle. Finally your site will be static, which means no one can mess with it, unlike a WordPress site which is full of holes and needs to be updated religiously.

Here’s some pointers:

- Make full use of collections, your _posts folder, layouts and includes. Usually, the more modular you make the site, the faster you can create it and keep it up to date.

- Always remember to check your site for responsiveness using the inspector in whatever browser you’re using.

- Keep values consistent using Sass variables.

- Don’t reinvent the wheel if possible, look for JavaScript plugins and customize them to your needs (photo galleries for example).

- Put the site through it’s paces and make sure non of your code breaks down under unusual situations (old browsers, bad connections).

Check out Travis Neilson’s [YouTube](https://www.youtube.com/user/DevTipsForDesigners){:target="_blank"} and you can learn a whole lot more than what’s in this post.
