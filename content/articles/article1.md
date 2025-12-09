---
title: "Article 1: Reversing an Array in JavaScript"
description: "One of my first programming walkthroughs for this class."
omit_header_text: true
featured_image: "https://www.designyourway.net/blog/wp-content/uploads/2018/01/cool-desktop-wallpaper-wallpapers-backgrounds-images-art-photos-pictures-free-best-1920x1080_coolwallpaper_good-wallpaper-ideas-house-entrance-design-hand-coat-hooks-7-princip.jpg"
summary: "A simple breakdown of how to reverse an array without using built-in shortcuts."
type: page
weight: 2
---

## Introduction

For this article, I wanted to take something simple in JavaScript and break down **how it actually works behind the scenes**.  
A basic example of this is reversing an array. Yes—JavaScript has a built-in `.reverse()` method, but the point here is to understand *how* the logic works, not just let the computer do it for us.

Reversing an array by hand is a great way to practice loops, indexing, and thinking through each step of a problem.

---

## The Goal

Given an array like:

```js
[1, 2, 3, 4, 5]
