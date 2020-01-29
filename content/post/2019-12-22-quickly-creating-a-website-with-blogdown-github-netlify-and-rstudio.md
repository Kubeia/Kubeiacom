---
title: Quickly creating a website with Blogdown, GitHub, Netlify and RStudio
author: Sam
date: '2019-12-22'
slug: quickly-creating-a-website-with-blogdown-github-netlify-and-rstudio
categories:
  - R
tags: []
draft: True
---

## The Challenge: Build a fully fledged website within one week

As I sit here a couple of days before Christmas I have set myself a goal of publishing a fully functioning website using Yihue's wonderful R package blogdown. I will update this page as I go along to offer some tips and tricks if you would like to do the same. 

## Why I am doing this
- Writing and publishing information is a wonderful way to collect my thoughts
- Done is better than perfect
- A good summary of [why to create a blog by mathrachel] (https://medium.com/@racheltho/why-you-yes-you-should-blog-7d2544ac1045)

## The Stack
The idea is to get the website up and running as easily as possible. I already own the domain kubeia.com so that part is already done.
- Blogdown. As a data scientist I use R more often than any other language. Blogdown allows me two do two things that are not as easy in other solutions. The first is the ability to write R code and insert the output in Rmarkdown documents. The second is the ability to write mathematics using `$\LaTeX$`.  The great part about blogdown is that is uses Hugo to render the pages. In effect the website is produced by Hugo and then uploaded to my host. The host doesn't require any server side processing, as the site is static. Therefore I don't need to worry about maintaining the security of a server.
- Netlify. Netlify has free hosting, Hugo rendering, connections to GitHub and continuous integration. So ideally, I should be able to edit my website in RStudio, then push it to GitHub and Netlify will do the rest.


## Getting Started, and my Minimum Viable Product

Ok, so first I want to create a minimum viable product. Let's see, what do I need?
- I have R, RStudio and Git installed on my laptop
- blogdown and all its dependencies are installed
- I have signed up to Github and Netlify
- Create my Github repository
- Start a blogdown project
- Configure the blogdown site and edit the About page
- Write a couple of posts
- Push to Github and publish
- Added Google analytics to see if anyone is visiting my site and Disqus to allow visitors to comment
- Done

Because this is an MVP I am skipping a few steps such as spending time with Hugo Themes. I have found in the past that this is a rabbit hole that I can waste so much time. The website is designed to publish my writing and code. The base theme used in blogdown is perfectly serviceable for this. Future iterations of the website may use the Academic theme which produces very clean and extensible websites

## Another option

Jermey Howard has shared a way of building websites using GitHub pages. This is even simpler than the method I have used.

## Resources

Blogdown

## Now for some posts

I have some code that I worked on a few month's ago on Bairstow's Method which will make a good post. View the source here. It will allow me to practice blogdown, and inserting R code and LaTeX into my posts. The post is now live here

## Blogdown workflow