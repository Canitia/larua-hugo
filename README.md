## larua-hugo
![License](https://img.shields.io/github/license/pixelateddeveloper/larua-hugo?style=flat-square)
[![CodeFactor](https://www.codefactor.io/repository/github/pixelateddeveloper/larua-hugo-theme/badge)](https://www.codefactor.io/repository/github/pixelateddeveloper/larua-hugo-theme)

A spinoff of [Larua](https://github.com/pixelateddeveloper/larua-ghost-theme) for the [Hugo](https://gohugo.io/) static site generator. 

# Main Features
- UI optimised for different form factors (phone/tablet/pc)
- Ability to set your own publication icon and publication logo.
- Set cover- and featured-post images in config.
- Navigation configurable via config.
- Author section at the bottom of each post includes avatar, user bio and socials.
- Shows related posts (by primary tag) below a post.

![Larua](https://github.com/pixelateddeveloper/larua/raw/master/assets/screenshot-desktop.png)

## Prerequisites
- Step 1: Install [Hugo](https://gohugo.io/getting-started/installing)
- Step 2: Clone Larua-Hugo's repository in your Hugo's **themes** directory.

``` git clone https://github.com/pixelateddeveloper/larua-hugo-theme```

# Larua-Hugo's base
Larua uses the following libraries;
- Bootstrap 4
- JQuery (3.1.x)
- Font Awesome 5
- Webfontloader 1.6.28


## Config.toml sample
```
baseURL = "https://larua-hugo.mydomain.com/"
languageCode = "nl"
title = "Larua for Hugo"
theme = "larua-hugo"
contentdir = "content"
layoutdir = "layouts"
publishdir = "public"
canonifyurls = true

[[menu.main]]
    name = "Home"
    weight = 1
    url = "/"
[[menu.main]]
    name = "Github repo"
    weight = 2
    url  = "https://github.com/pixelateddeveloper/larua-hugo-theme"
[[menu.main]]
    name = "About Michael Boumann"
    weight = 3
    url  = "https://michaelboumann.com"

[params]
    logo = "/images/logo.png"
    bgpattern = "/images/bgpattern.png"
    header = "/images/header/header.jpg"

    avatar = "/images/avatar/avatar.jpg"
    authorbio = "This is my biography. It's amazing really."

[taxonomies]
   tag = "tags"
   category = "categories"
```

## Content sample
Create your .md files with the following format and place them in the content folder. 

```
---
title: "My First Post"
date: 2019-06-07T16:25:53+02:00
draft: false
author: "John Doe"
featured: /images/posts/post1.jpg
type: post
categories: [cat1,cat3]
tags: [new,content,tags]
---

Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.
```