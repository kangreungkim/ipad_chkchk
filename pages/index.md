---
layout: page
title: 2023년 3월 아이패드 비교/ 최저가
permalink: /
---

# 2023년 아이패드  요약정리

| 분류       | 해당기종                                       | 요약                                        |
| ---------- | ---------------------------------------------- | ------------------------------------------- |
| 보급형입문 | 아이패드10세대                                 | 조금 아쉽지만 저렴<br />인강용으로 손색없음 |
| 중급형     | 미니 6세대<br />**에어 5세대**                 | 갖출건 다 갖춘 베스트 셀러                  |
| 고급형     | 프로 11인치 4세대<br />**프로 12.9인치 6세대** | 더 다양한 기능과 압도적인 성능 

![assets/img/docsy-jekyll.png](assets/img/docsy-jekyll.png)

## Purpose

GitHub pages uses Jekyll natively, so when I make documentation, I typically
look for Jekyll templates. Why? Using Jekyll means that I can use markdown,
and allow for users to easily contribute, and build automatically just by
way of pushing to a master branch (or general GitHub pages).
I found Docsy, a beautiful Hugo template, but it requires hugo with GoLang
which doesn't render natively on GitHub pages. For this reason, I've spent
some time creating a custom Jekyll template that is (almost) as beautiful,
and includes all the features that I might want.

## Features

What are these features? You should see the {% include doc.html name="Getting Started" path="getting-started" %}
guide for a complete summary. Briefly:

 - *User interaction* including consistent permalinks, links to ask questions via GitHub issues, and edit the file on GitHub directly.
 - *Search* across posts, documentation, and other site pages, with an ability to exclude from search.
 - *External Search* meaning an ability to link any page tag to trigger an external search.
 - *Documentation* A documentation collection that was easy to organize on the filesystem, render with nested headings for the user, and refer to in markdown.
 - *Pages* A separate folder for more traditional pages (e.g, about).
 - *Navigation*: Control over the main navigation on the left of the page, and automatic generation of table of contents for each page on the right.
 - *News* A posts feed for news and updates, along with an archive (organized by year).
 - *Templates* or specifically, "includes" that make it easy to create an alert, documentation link, or other content.
 - *Continuous Integration* recipes to preview the site


For features, getting started with development, see the {% include doc.html name="Getting Started" path="getting-started" %} page. Would you like to request a feature or contribute?
[Open an issue]({{ site.repo }}/issues)
