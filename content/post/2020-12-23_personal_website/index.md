---
title: How to make a personal academic website with R markdown?
subtitle: A step-by-step tutorial to build and deploy a personal website using R, hugo, and github.

# Summary for listings and search engines
summary: A step-by-step tutorial to build and deploy a personal website using R, hugo, and github.

# Link this post with a project
projects: []

# Date published
date: "2020-12-23T08:00:00Z"

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
Whether one needs a personal website for professional growth is out of question. Of course, we need it. Rather the main question is - how attractive and elegant is the website? Being a Ph.D. student, it's not a surprise that I like an academic-theme website. Developing a nice website from the scratch needs huge time and efforts. Luckily, there are open source templates. While these templates are fairly simple, we need to know how to customize them.

I recently developed <a href="https://alorchhota.github.io/" target="_blank">my website</a> using R, hugo and github. A blurred screenshot is shown in the above picture. What I like about the website are:
- It is simple in design, attractive in appearance, and elegant in presentation.
- Easy to customize.
- The code is maintained as a repository in Github. As a result, it's easy to edit or update the site.
- The site has been deployed in Github, no need to buy a domain name. It is also easy to deploy the site in a custom domain name.
- It offers a simple and powerful personal blogging feature.
- Seamlessly rendered in computer, cell-phone, iPad, and other devices.

Before I started developing the website, I looked into the blog posts by [Alison Hill](https://alison.rbind.io/post/2017-06-12-up-and-running-with-blogdown/), [Leslie Myint](https://lmyint.github.io/post/hugo-academic-tips/), and  [Ming Tang](https://divingintogeneticsandgenomics.rbind.io/post/hugo-academic-theme-blog-down-deployment-some-details/). While each of these blogs was helpful, the actual development was a bit different, because the hugo theme and the templates have changed (improved). Here I share how I customized the website.

## Resources
Before I started, I looked at the blogs by 

## Installation

## 

## Overview

1. The Wowchemy website builder for Hugo, along with its starter templates, is designed for professional creators, educators, and teams/organizations - although it can be used to create any kind of site
2. The template can be modified and customised to suit your needs. It's a good platform for anyone looking to take control of their data and online identity whilst having the convenience to start off with a **no-code solution (write in Markdown and customize with YAML parameters)** and having **flexibility to later add even deeper personalization with HTML and CSS**
3. You can work with all your favourite tools and apps with hundreds of plugins and integrations to speed up your workflows, interact with your readers, and much more

{{< figure src="https://raw.githubusercontent.com/wowchemy/wowchemy-hugo-modules/master/academic.png" title="The template is mobile first with a responsive design to ensure that your site looks stunning on every device." >}}

## Get Started

- 👉 [**Create a new site**](https://wowchemy.com/templates/)
- 📚 [**Personalize your site**](https://wowchemy.com/docs/)
- 💬 [Chat with the **Wowchemy community**](https://discord.gg/z8wNYzb) or [**Hugo community**](https://discourse.gohugo.io)
- 🐦 Twitter: [@wowchemy](https://twitter.com/wowchemy) [@GeorgeCushen](https://twitter.com/GeorgeCushen) [#MadeWithWowchemy](https://twitter.com/search?q=(%23MadeWithWowchemy%20OR%20%23MadeWithAcademic)&src=typed_query)
- 💡 [Request a **feature** or report a **bug** for _Wowchemy_](https://github.com/wowchemy/wowchemy-hugo-modules/issues)
- ⬆️ **Updating Wowchemy?** View the [Update Guide](https://wowchemy.com/docs/update/) and [Release Notes](https://wowchemy.com/updates/)

## Crowd-funded open-source software

To help us develop this template and software sustainably under the MIT license, we ask all individuals and businesses that use it to help support its ongoing maintenance and development via sponsorship.

### [❤️ Click here to become a sponsor and help support Wowchemy's future ❤️](https://wowchemy.com/plans/)

As a token of appreciation for sponsoring, you can **unlock [these](https://wowchemy.com/plans/) awesome rewards and extra features 🦄✨**

## Ecosystem

* **[Wowchemy Admin](https://github.com/wowchemy/wowchemy-admin/):** An admin tool to automatically import publications from BibTeX

## Inspiration

[Check out the latest **demo**](https://academic-demo.netlify.com/) of what you'll get in less than 10 minutes, or [view the **showcase**](https://wowchemy.com/user-stories/) of personal, project, and business sites.

## Features

- **Page builder** - Create *anything* with [**widgets**](https://wowchemy.com/docs/page-builder/) and [**elements**](https://wowchemy.com/docs/writing-markdown-latex/)
- **Edit any type of content** - Blog posts, publications, talks, slides, projects, and more!
- **Create content** in [**Markdown**](https://wowchemy.com/docs/writing-markdown-latex/), [**Jupyter**](https://wowchemy.com/docs/import/jupyter/), or [**RStudio**](https://wowchemy.com/docs/install-locally/)
- **Plugin System** - Fully customizable [**color** and **font themes**](https://wowchemy.com/docs/customization/)
- **Display Code and Math** - Code highlighting and [LaTeX math](https://en.wikibooks.org/wiki/LaTeX/Mathematics) supported
- **Integrations** - [Google Analytics](https://analytics.google.com), [Disqus commenting](https://disqus.com), Maps, Contact Forms, and more!
- **Beautiful Site** - Simple and refreshing one page design
- **Industry-Leading SEO** - Help get your website found on search engines and social media
- **Media Galleries** - Display your images and videos with captions in a customizable gallery
- **Mobile Friendly** - Look amazing on every screen with a mobile friendly version of your site
- **Multi-language** - 34+ language packs including English, 中文, and Português
- **Multi-user** - Each author gets their own profile page
- **Privacy Pack** - Assists with GDPR
- **Stand Out** - Bring your site to life with animation, parallax backgrounds, and scroll effects
- **One-Click Deployment** - No servers. No databases. Only files.

## Themes

Wowchemy and its templates come with **automatic day (light) and night (dark) mode** built-in. Alternatively, visitors can choose their preferred mode - click the moon icon in the top right of the [Demo](https://academic-demo.netlify.com/) to see it in action! Day/night mode can also be disabled by the site admin in `params.toml`.

[Choose a stunning **theme** and **font**](https://wowchemy.com/docs/customization) for your site. Themes are fully customizable.

## License

Copyright 2016-present [George Cushen](https://georgecushen.com).

Released under the [MIT](https://github.com/wowchemy/wowchemy-hugo-modules/blob/master/LICENSE.md) license.
