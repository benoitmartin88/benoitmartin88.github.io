---
title: "My first post !"
summary: "This is my first post using Hugo and the Blowfish theme."
categories: [post]
tags: [hugo, github pages, jerkyll, tree]
#externalUrl: ""
showSummary: true
date: 2023-01-21
draft: false
authors:
  - benoitmartin
---


This is my first post. Yay !!

I finally took the time to set this website up. I plan on using this space to document my projects as well as ramble about a few random things.

Before writing anything else, I'll start by explaining how this site is built. First of all, I have no need for any dynamic content. Everything on this site is static, so I opted for a static website generator. Furthermore, I love using Obsidian to manage and write in markdown. I'll probably write a post about obsidian in a near future.
Anyhow, this website is generated from markdown using Hugo and the Blowfish theme ❤️.

## Hugo
[Hugo](https://gohugo.io/) is a static site generator written in Go. Its lightweight, super fast and easy to use. An alternative to Hugo is [Jekyll](https://jekyllrb.com) which is natively supported on Github pages, but I didn't feel like having any kind of Ruby on my laptop.

To start things off, I mostly followed the quick start guide from the official Hugo website: https://gohugo.io/getting-started/quick-start.
From my project directory, I first initialized an empty Hugo site using the `hugo new site site` command. This creates a `site` directory in which the default Hugo file structure is created.
This is what file structure looks like using the `tree -L 2` command from my project root folder. (I guess I'll also write a post about the different tools that I like to use.)

```bash
.
└── site
    ├── archetypes
    ├── assets
    ├── content
    ├── data
    ├── layouts
    ├── resources
    ├── static
    └── themes
```



## Blowfish
The next step is installing a theme. For this, I headed to https://themes.gohugo.io and I selected [Blowfish](https://themes.gohugo.io/themes/blowfish/).
I chose to install this theme using the git submodule method which I find simple to setup and easy to update. 
The following commands got me setup with a git repo and the git submodule.

```bash
git init
git submodule add -b main https://github.com/nunocoracao/blowfish.git site/themes/blowfish
```

I then headed to the [theme's documentation](https://nunocoracao.github.io/blowfish/docs) to set things up as I wanted. Blowfish is very configurable and I didn't know exactly what I wanted to change, so I decided to take inspiration from the [lowkey](https://nunocoracao.github.io/blowfish_lowkey) setup. I very much like its simplicity.

## Github pages
All that is left is to host this site. I chose Github pages as its free and my code is versioned there anyways. 
I first started by creating a public repo that has the same name as my Github user. I then wanted to use Github actions to generate my static site when ever I pushed a new version on the `master` branch. [Hugo setup](https://github.com/marketplace/actions/hugo-setup) is what I used. I basically sets up a workflow which builds Hugo and deploys the generated static site to the `gh-pages` branch. Nice!
All that was left to do was setting up my domain name and the repo's page settings.


## Final thoughts

Overall, the process took a couple of hours. Which in my books, is a short amount of time for any IT related endeavour. I'm stoked !




