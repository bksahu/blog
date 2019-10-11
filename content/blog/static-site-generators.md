---
title: "Static Site Generators"
date: 2019-10-11T19:36:45+05:30
draft: false
---

This is the third iteration of my blog. In the past I had built it with [Jekyll](https://jekyllrb.com/) and [Pelican](https://blog.getpelican.com/) but didn't end up liking any of them. This time I am using [Hugo](https://gohugo.io/), a open-source static site generators created using go and plan to stay with it. 

So far, I like Hugo because it is [faster then Jekyll](https://forestry.io/blog/hugo-vs-jekyll-benchmark/) and pelican. Also, the Hugo CLI is very efficient and has good [offical documentation](https://gohugo.io/getting-started/quick-start/). Pelican on the other hand also has good documentation but have a relatively smaller community. Jekyll has huge community but it raises a lot of dependency error. I hope they have fixed it by now.

Following is quick hugo cheatsheet. I strongly recommend to go through the [offical docs](https://gohugo.io/getting-started/quick-start/).

```console
# 1.1 Install on Arch Linux
$ sudo pacman -S hugo 

# 1.2 Install on any other Linux
$ sudo snap i hugo

# 2.  Create a new site
$ hugo new site <site-name>

# 3. Add new theme
$ echo 'theme = "<theme-name>"' >> config.toml

# 4. Create new content
$ hugo new posts/<post-name>.md

# 5.1 Build site
$ hugo serve

# 5.2 Build devserver
$ hugo server -D

# 6 Publish to github.¹²
$ sh deploy.sh
```

¹ Read about how to create `deploy.sh` [here](https://gohugo.io/hosting-and-deployment/hosting-on-github/#put-it-into-a-script).


² Read step by step instructions on how to set up hugo with gh pages [here](https://gohugo.io/hosting-and-deployment/hosting-on-github/#step-by-step-instructions) 


:raising_hand: