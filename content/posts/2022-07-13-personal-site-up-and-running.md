---
title: Personal site up and running!
date: 2022-07-13T20:27:19.656Z
author: Mohammad Khan
cover: images/uploads/hugo_netlifycms_netlify_logos.png
description: Finally have my personal site up using Hugo and Netlifycms running on Netlify
---
It took me a while, but I finally got around to getting my personal website up and running once again. I have gone through many iterations and domains in the past and mostly using WordPress. WordPress generally tends to be the easiest and fastest to get up and running if you are using a hosting provider. Most hosting providers generally offer a dedicated WordPress site from the start, which makes it simple to get going.


I took a different approach this time around and chose to use something I have never played around with before. I was looking for something lean and straight forward or in other words performant and barebones. I had heard about static site generators which do away with necessarily using any database or complex backend and just use basic file-based storage.

Upon bringing this up a while back to some of my fellow colleagues someone pointed me to [Hugo](https://gohugo.io/) which I found fairly intriguing, and I wanted to dive into something new anyways. Hugo is based on Go Lang which I know nothing about at the time of this writing, but I have heard of it. I didn't want to spend time on the design side of things, so I looked up some free Hugo themes and I decided on something simple that you see here by [panr](https://github.com/panr/hugo-theme-hello-friend).


On my journey towards building this out I also came across something called [netlifycms](https://www.netlifycms.org/) which is an open-source content management system for your git workflow. As my plan was to use GitHub anyways this was a perfect combination as it gave me some amount of comfort of a CMS but nothing overly bloated. Combining this with [Netlify](https://www.netlify.com/) as my CI/CD and hosting solution was a no brainer.

It did take some work in getting the theme to work with netlifycms as this is not something available out of the box but that's the fun part of working on personal projects. I may go into that in another post.