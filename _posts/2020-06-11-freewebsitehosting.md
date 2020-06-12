---
layout: posts
title: How I hosted this website for free
type: general
---
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;In this I will explain how to host a static website for free.We use jekyll static site generator an excellent tool for generating static sites which is supported by github pages.If your are a student I have a way to host it in your own domain. Let's get started

## choosing where to host

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;When it comes to hosting a free static site, github pages is the best thing out there.It is easy to work with and is being used largely in the market.It supports jekyll static site generator and it has custom domain facility.So I went with Github pages.Deploying into github pages is as very easy, infact you need not do anything just pushing to your repository reflects the changes in the website.

## What is jekyll and why jekyll

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; While writing a static pages from scratch we must have to repeat ourselves many times. For example we have to write navigation bar logic in each and every page.We all know this is not a good principle.we programmers must follow [DRY](https://en.wikipedia.org/wiki/Don%27t_repeat_yourself) for many reasons.

![img]({{site.base_url}}/assets/images/DontRepeatYourself.png)

### So what jekyll does

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Jekyll is a static site generator. It supports markup languages so we need not write html files each time.We can just set layout and it renders our markdown files according to the layout specified using yaml at the top.We will have acces to `control-flow` instructions like `if else`and looping `for`.[This step by step tutorial helps more to get better intuition.](https://jekyllrb.com/docs/step-by-step/01-setup/).

I feel better to write everytime in markup language instead of writing in html.

### There are many static site generators why jekyll?

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Github pages supports jekyll so I went with jekyll


#### [`star my repository to show some love`](https://github.com/prudhvi-hack/myblog).

## Domain name

### Github Student Developer pack
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;I hope everyone knows about [Github student developer pack](https://education.github.com/pack).If you are not go with that link.In that `name.com` provides one year free domain name. Go and register your domain in [name.com](https://name.com) . It is pretty easy .we just need to search for domain and buy for free.

### Custom domain
#### name.com
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[This article from name.com does the simple step of adding A records](https://www.name.com/blog/how-tos/2016/07/using-custom-domain-github-project-pages/).After completion of this step in your Manage Dns section of name.com you should see four ip addresses added as A entry.
#### In Github
1. Go to settings page of your repository
2. Scroll down to githuhb pages section
3. Under source select branch you want to make as a github pages(I will recommend to create a branch with name gh-pages)
4. under custom domain enter your registered domain & click save
5. It will create a CNAME file in your repo and your blog will be live at your domain

#### Adding CNAME entry in name.com
Add a cname record pointing to your github page .

my cname record looks like this.

<img src="{{site.base_url}}/assets/images/cname.png" height="300px" width="1000px">

That's it your static site is ready at your domain name.

#### Thank you for reading this far.

[Please raise a issue in my github page if any corrections](https://github.com/prudhvi-hack/myblog).

[Star my repo if you liked my blog](https://github.com/prudhvi-hack/myblog).
