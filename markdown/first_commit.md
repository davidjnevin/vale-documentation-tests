---
title: "First Commit"
date: 2022-06-14T21:01:56+02:00
draft: false
showthedate: true
showlastmod: true
showtoc: true
showbreadcrumbs: false
description: "C# so far - critique wheel"
tags: ["First"]
---

## Start here

As of today, I've been re-experimenting with programming for 13 months.

This is the first blog post on the topic of my coding experiences. I've no doubt this layout will develop and mature as I add content.

I hope it serves as a useful resource for anyone that stumbles across it.

## This site

This site itself is built using [Hugo](https://gohugo.io/about/what-is-hugo/), a static site generator written in [Go](https://go.dev/). I don't know _Go_ and Hugo doesn't require any deep programming skills. The documentation and community is great and it's free.

This site uses a neat trick of a [git submodule](https://dev.to/aormsby/how-to-set-up-a-hugo-site-on-github-pages-with-git-submodules-106p) to continuously update the live version wth any changes.

It also uses [SASS via gulp](https://www.youtube.com/watch?v=nI0BfXFjI1I), which is really useful to have running with a live preview of any CSS changes.

[My biggest programming project to date]({{<relref "code/critique_wheel_csharp.md" >}}) has been the Critique Wheel written in C#. Once the site is redone, I think I'll be looking at integrating C# and python into some project.

note: The above internal link in Hugo uses the following code to create a relative link to another page:

```
[My biggest programming project to date]({{<relref "code/critique_wheel_csharp.md" >}})
```
