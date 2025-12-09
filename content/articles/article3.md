---
title: "More!"
description: ""
omit_header_text: true
featured_image: "https://www.designyourway.net/blog/wp-content/uploads/2018/01/cool-desktop-wallpaper-wallpapers-backgrounds-images-art-photos-pictures-free-best-1920x1080_coolwallpaper_good-wallpaper-ideas-house-entrance-design-hand-coat-hooks-7-princip.jpg"
summary: "Trying out another small browser-based example."
type: page
weight: 4
---

## A Quick Extra Example

This is another simple browser experiment based on the Advent of Code Day 1 problem.  
Nothing too fancy — just another way to take a text file, upload it in the browser, and let JavaScript process it instantly.

The setup is the same:  
Your file should have one number per line, and blank lines separate different groups. Once you upload it, the page calculates which group has the highest total.

---

## Try It Out


<input id="fileInput" type="file" name="file" />

<p id="result">Your highest total will show up here after choosing a file.</p>


---

## Behind the Scenes

The JavaScript that powers this little demo lives here:

- **`/js/advent-in-action.js`**

If you open your browser’s Inspect tools, you can see exactly how the script grabs the file input and updates the page. It's a small but helpful example of how frontend JavaScript interacts with HTML elements.

---

## Quick Note

This isn’t a required assignment or anything — I just wanted to test out what it looks like to read files directly in the browser. It’s a good skill to know when working with client-side apps.


<script src="/js/advent-in-action.js"></script>

