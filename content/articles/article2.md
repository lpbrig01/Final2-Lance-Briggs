---
title: "Article 2: Running Code in the Browser"
description: ""
omit_header_text: true
featured_image: "https://www.designyourway.net/blog/wp-content/uploads/2018/01/cool-desktop-wallpaper-wallpapers-backgrounds-images-art-photos-pictures-free-best-1920x1080_coolwallpaper_good-wallpaper-ideas-house-entrance-design-hand-coat-hooks-7-princip.jpg"
summary: "Using JavaScript in the browser to read a file and process data."
type: page
weight: 3
---

## Overview

For this article, I wanted to take the idea from Advent of Code and try it in a different place — the **browser**.  
Instead of running everything with Node, the browser lets you upload a file and process it right on the page using JavaScript.

This is a simple example, but it shows how websites can read user-provided files and run logic on them behind the scenes.

---

## How It Works

The idea is straightforward:

1. You upload a text file with numbers (one number per line).  
2. Blank lines separate groups, just like in Advent of Code.  
3. The browser reads your file, processes each “pack,” and finds the pack with the highest total.  
4. The result appears instantly on the page.

That’s it — no server, no backend, just JavaScript running in your browser.

---

## Try It Yourself

Choose a file formatted like this:

