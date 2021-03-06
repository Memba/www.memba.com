---
category: Miscellaneous
description: The Memba website is online and it constitutes a prototype for deploying Kidoju, which is coming soom.
icon: environment_network
keywords: Memba, blog, online, amazon, web, services, aws, cloud, prototype, nodeJS, expressJS, docker, nginx, kendo ui, wordpress, blogger, ghost, jekyll, octopress, markdown, github
language: en
title: We are online!
uuid: 80c1b6e0-0ab7-11e5-a5fc-0bc8f37470e1
author: jlchereau
author_url: https://github.com/jlchereau
avatar_url: https://avatars.githubusercontent.com/u/2556751?v=3
creation_date: 2015-05-29T17:12:25Z
edit_url: https://github.com/Memba/www.memba.com/blob/master/en/posts/2015/online.md
site_url: https://www.memba.com/en/posts/2015/05/online
---
We already had a web site but this replaces it.

This is great news and we are really excited about it because:

1. Our new [blog software](https://github.com/Memba/Memba-Blog) is a minimal version of the Kidoju [MEAN architecture](https://www.memba.com/en/posts/2014/12/mean).
2. It is deployed on [Amazon AWS](https://aws.amazon.com/), with multiple [docker](https://www.docker.com/) containers, [nginx](http://nginx.org/) proxies and an AWS load balancer.

In other words, we have turned this web site into a test lab to bullet proof our Kidoju architecture and deployment before release.

![We are online!](https://raw.githubusercontent.com/Memba/www.memba.com/master/en/posts/2015/online.jpg)

Apart from the benefits of such test lab, we have built a new blog software for several reasons:

1. Considering our extensive use of [Kendo UI widgets](http://www.telerik.com/kendo-ui), customizing [WordPress](https://www.wordpress.com/), [Blogger](https://www.blogger.com) or [Ghost](https://ghost.org/fr/) to our UI design guidelines was not an easy task;
2. Although [Jekyll](https://jekyllrb.com/) and [Octopress](http://octopress.org/) are very neat, we feel that rebuilding and redeploying each time content changes is too constraining.
3. We enjoy [markdown](https://en.wikipedia.org/wiki/Markdown) and [Github](https://github.com/) offers a great environment to write and version markdown files. 

We have made our [blog software](https://github.com/Memba/Memba-Blog) free to use for everyone.
It uses Kendo UI, it reads markdown and automatically pulls new content from Github each time a change is detected.