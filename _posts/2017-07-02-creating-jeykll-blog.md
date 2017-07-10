---
layout: post
title:  "Creating your Jekyll blog"
date:   2017-07-09
categories:
---
[See this on Github](https://github.com/yuvsc/yuvsc.github.io)

Hello, and welcome to my blog!
In this first post, I am writing about how and why I set up this blog. This includes links to reviews on Jekyll blogs in general, and how or why they can benefit you.

---

Idea
---

I wanted to have a way to document and share my projects. As I began to look into the different ways to do this, I realized that I wanted something that was simple, but also for me to be able to have full controll over how it all worked. So I ran into [Jekyll](https://jekyllrb.com/), a blog-aware static site generator.

---

Execution
---

Getting right into it, super excited to relive the projects I have previously done and document them, I started out with the Jekyll installation [requirements](https://jekyllrb.com/docs/installation/#requirements), then the [quick start guide](https://jekyllrb.com/docs/quickstart/), as well as a [starting point](https://www.smashingmagazine.com/2014/08/build-blog-jekyll-github-pages/#lets-try-it-out).

As I continued to learn about [jekyll usage](http://jekyllrb.com/docs/usage/) and how it all works, I discovered that this is really awesome and simple. Here are some of the reasons why: 
* Jekyll posts can be written in any language. This one, for example, is written in markdown.
* Jekyll doesn't need a backend. It is a static site generator that uses layouts and pre-processed CSS for Jeykyll to make a web page.
* Jekyll is simply integratable with GitHub pages. Since GitHub Pages are powered by Jekyll, you can easily deploy your site using GitHub for free. All you have to do is upload your Jekyll project, and it will run the site generator for you.

---

Summary
---

Jekyll is a super easy to set up static site generator, which you can host your static site on GitHub. So for anyone just looking to set all of this up quickly (aka future me), these should be the steps that will get you there:

First make sure you have these requirements:
* GNU/Linux, Unix, or macOS
* Ruby version 2.1 or above, including all development headers
* RubyGems
* GCC and Make

Then install Jekyll

```sh
gem install jekyll bundler
```

Create a new Jekyll site at ./myblog
```sh
jekyll new myblog
```

Change into your new directory
```sh
cd myblog
```

Build the site on the preview server
```sh
bundle exec jekyll serve

# or if you want it to track your changes use
jekyll serve --force_polling
```

Now you can see your site on [http://localhost:4000](http://localhost:4000)

Goodluck and enjoy!
