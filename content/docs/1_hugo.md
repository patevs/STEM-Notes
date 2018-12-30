---
date: 2018-12-29
lastmod: 2018-12-30
title: Hugo Framework
authors: ["patevs"]
categories:
  - Tutorial
  - Javascript
  - NodeJS
  - Frontend
tags:
  - engineering
  - introduction
  - installation
  - hugo
  - javascript
  - nodejs
  - npm
toc: false
---

# Hugo Static Site Generator

## Installing Hugo

First of all you will need to setup a Hugo site. You can follow the Hugo [Quick Start Guide](https://gohugo.io/getting-started/quick-start/) for that.

The next step is to install a theme. Instructions for doing so can be found in the Hugo [themes documentation](https://gohugo.io/themes/).

A list of all available themes can be browsed [here](https://themes.gohugo.io/).

The theme I have chosen to use for this website is cloned from: [`achary/engimo`](https://github.com/achary/engimo)

## Installing a Theme

There are two different ways you can install Engimo as a theme:

1. Clone repo:

```bash
git clone --depth 1 https://github.com/achary/engimo themes/engimo
```

2. As a submodule

```bash
git submodule add https://github.com/achary/engimo themes/engimo
```

This will add Engimo's repository as a submodule to your site's repository. Now, you will have to pull/update the theme:

```bash
git submodule init
git submodule update
```

_The second method is recommended._

That's all, Engimo is ready to be used.

----
