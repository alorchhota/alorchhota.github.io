---
title: How I made an academic-theme personal website with R markdown
subtitle: A step-by-step description to build and deploy a personal website using R, hugo, and github.

# Summary for listings and search engines
summary: A step-by-step description to build and deploy a personal website using R, hugo, and github.

# Link this post with a project
projects: []

# Date published
date: "2025-12-23T08:00:00Z"

# Date updated
lastmod: "2020-12-23T08:00:00Z"

# Is this an unpublished draft?
draft: true

# Show this page in the Featured widget?
featured: false

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  caption: 'Blurred screenshot of the website'
  focal_point: ""
  placement: 2
  preview_only: false

authors:
- admin

tags:
- Academic
- Website
- How to

categories:
- Tutorial

---
Whether one needs a personal website for professional growth is out of question. Of course, we need it. Instead, the question is - how attractive and elegant is the website? Being a Ph.D. student, it's not a surprise that I find an academic-theme website very attractive. Developing such a website from the scratch needs huge time and efforts. Luckily, there are open source templates. I recently developed <a href="https://alorchhota.github.io/" target="_blank">my website</a> using such a template. A blurred screenshot is shown in the above picture. What I like about the website are:

- It is simple in design, attractive in appearance, and elegant in presentation.
- Easy to customize (if you know R).
- The code is maintained as a repository in Github. As a result, it's easy to edit or update the site.
- The site has been deployed in Github, no need to buy a domain name. It is also easy to deploy the site in a custom domain name.
- It offers a simple and powerful personal blogging feature.
- Seamlessly rendered in computer, cell-phone, iPad, and other devices.

While the template was fairly simple, I had to figure out how to customize it. I started by looking into the blog posts by [Alison Hill](https://alison.rbind.io/post/2017-06-12-up-and-running-with-blogdown/), [Leslie Myint](https://lmyint.github.io/post/hugo-academic-tips/), and  [Ming Tang](https://divingintogeneticsandgenomics.rbind.io/post/hugo-academic-theme-blog-down-deployment-some-details/). While each of these blogs was helpful, the actual development was a bit different, because things have changed. Here I share how I customized the website.

## Requirements
Following things are necessary for deveoping this website.
* [R](https://www.r-project.org/) and [RStudio](https://rstudio.com/) installed in the computer. Working knowledge of R coding is necessary.
* [blogdown](https://cran.r-project.org/web/packages/blogdown/index.html) package installed in R. The book [blogdown: Creating Websites with R Markdown](https://bookdown.org/yihui/blogdown/) is a good resource to know the basics related to this website development.
* [GO language](https://golang.org) installed in the computer.
* A [github](https://github.com/) account and related working knowledge.


## Steps to create the website
1. I forked the [starter-academic repository](https://github.com/wowchemy/starter-academic) on my github account. [[How to fork a github repository]((https://docs.github.com/en/github/getting-started-with-github/fork-a-repo))]
2. Renamed the repository to _alorchhota.github.io_ [format: **myaccountid**.github.io] from Settings. Renaming would be useful later to deploy the website as [https://alorchhota.github.io/](https://alorchhota.github.io/). Here is my repository:[https://github.com/alorchhota/alorchhota.github.io](https://github.com/alorchhota/alorchhota.github.io). [[How to rename a github repository](https://docs.github.com/en/github/administering-a-repository/renaming-a-repository)].
3. Cloned the repository on my local computer using terminal.
```{bash}
git clone https://github.com/alorchhota/alorchhota.github.io # remember to use your repository
```
4. Opened the repository in RStudio as a new package from existing folder. There I loaded the blogdown package, build the template website, and start the server.
```{r}
library(blogdown)
build_site()
serve_site()
```

