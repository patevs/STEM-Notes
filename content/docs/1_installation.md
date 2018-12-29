---
date: 2018-12-29
lastmod: 2018-12-29
title: Hugo Framework
authors: ["patevs"]
categories:
  - Tutorial
tags:
  - engineering
  - introduction
  - installation
  - hugo-framework
toc: true
---
First of all you will need to setup a Hugo site. You can follow the [Hugo's Quick Start Guide](https://gohugo.io/getting-started/quick-start/) for that.

After you're done with that, it's time for installing Engimo!

## Installing Engimo

There are two different ways you can install Engimo:

1. As clone
```sh
git clone --depth 1 https://github.com/achary/engimo themes/engimo
```
2. As submodule
```sh
git submodule add https://github.com/achary/engimo themes/engimo
```
This will add Engimo's repository as a submodule to your site's repository. Now, you will have to pull the theme:

```sh
git submodule init
git submodule update
```

_The second method is recommended._

That's all, Engimo is ready to be used.

----
