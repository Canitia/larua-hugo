## larua-hugo
![License](https://img.shields.io/github/license/Canitia/larua-hugo?style=flat-square)
[![CodeFactor](https://www.codefactor.io/repository/github/canitia/larua-hugo/badge)](https://www.codefactor.io/repository/github/canitia/larua-hugo)

A spinoff of [Larua for Ghost](https://github.com/Canitia/larua) for the [Hugo](https://gohugo.io/) static site generator. 

## Progress
Currently in heavy development. Things to do include:
- ~~Pagination~~ **added in 0.2.0**
- ~~Adding categories~~ **added in 0.4.0**
- ~~Adding related posts~~ **added in 0.3.0**
- ~~Adding tags~~ **added in basic form - 0.5.0**
- Probably more i'm missing but need to check ;)

## Prerequisites
- Step 1: Install [Hugo](https://gohugo.io/getting-started/installing)
- Step 2: Clone/extract theme in themes directory

## Content sample
Create your .md files with the following format and place them in the content folder. 

```
---
title: "My First Post"
date: 2019-06-07T16:25:53+02:00
draft: false
author: "Michael Boumann"
featured: /images/posts/post1.jpg
type: post
categories: [cat1,cat3]
tags: [new,content,tags]
---

Lorem Ipsum is slechts een proeftekst uit het drukkerij- en zetterijwezen. Lorem Ipsum is de standaard proeftekst in deze bedrijfstak sinds de 16e eeuw, toen een onbekende drukker een zethaak met letters nam en ze door elkaar husselde om een font-catalogus te maken. Het heeft niet alleen vijf eeuwen overleefd maar is ook, vrijwel onveranderd, overgenomen in elektronische letterzetting. Het is in de jaren '60 populair geworden met de introductie van Letraset vellen met Lorem Ipsum passages en meer recentelijk door desktop publishing software zoals Aldus PageMaker die versies van Lorem Ipsum bevatten.
```