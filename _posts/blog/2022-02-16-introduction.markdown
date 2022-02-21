---
layout: post
title:  "Creating A Personal Website"
subtitle: "My first rendezvous with web development"
date:   2022-02-16 23:34:01
categories: [python, backend]
---

# Table of Contents
* TOC
{:toc}

# My prior experience with web development
Virtually none! I took a web development class during my undergraduate years, but it was incredibly
rudimentary. 4 years out of school, and I've mainly worked on back-end systems/services and data pipelines.
Somewhere along the lines of my journey as a Computer Science student, I realized a personal
website to host a portfolio would be necessary as every single software engineer job application has 
a field for a website, and I got tired of leaving it blank.

I also viewed this as a good opportunity to play around in HTML and CSS, and found myself getting obsessive with
making little tweaks and changes, as a website with my name on it will likely serve as a real impression
for folks that visit.

# Picking a framework
At first, I started going through a Django framework tutorial, because I figured my background with Python would
make learning web development easier to pick up on. I told a full-stack developer friend of mine, and he told me
that for what my goal is (simple interface, portfolio, blogging), I should use a static site generator, and
that he recommends Jekyll because of its blogging capabilities simplicity

# Getting Started
I did some searching and found a [minimal theme](https://github.com/kronik3r/daktilo) I enjoyed, cloned it,
and started hacking away.<br>
The easiest part was uploading a picture and linking it to the Home page.
Over time, I started finding the right css files to edit the theme for the overall website,
as well as the wonderful world of linked icons. There was an entire day I spent playing
around with different css selectors (specifically :hover) and amusing myself with the
seemingly endless world of CSS.<br>
Among the more interesting portions of this project was creating a separate
page for portfolio projects, and using the Liquid templating language to populate
a page with multiple portfolio projects that reside in their own directory.<br>
All of this is hosted on Github Pages, which I recommend to anybody who wants
to create a basic website without the hassle of hosting.

# Overall Thoughts
I'm glad I finally took the time to tackle this. If anything, it has made me
want to expand my knowledge on basic web development, and make this website
fully interactive, which is complete overkill, but when I have the itch...

# Notes
*I keep a small journal with me to jot down any thoughts/observations/revelations during coding sessions
These are straight from that journal.*
- Jekyll error messages are nicer than most
- Take a good look at included css classes before you add your own
- Group your .css classes in the file by 1) use, 2) alphabetically
- Organization of pages is especially important in Jekyll
- Make headers for MD files succinct and relevant