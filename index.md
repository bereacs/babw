---
title: Hello, World
date: 2012 11 05
layout: minimal
---

# November 17, 2012

It would be nice to have a combination of tags and/or plugins that automate some of the formatting surrounding homework and labs. Because the main page should really just be the homework/lab listing, we might as well have tags that make it quick-and-easy to flow things together.

## This Isn't It

At the moment, this isn't how I would actually format a post. I want the index.md to be a script, basically. It should be parameterized over the date (so that we render everything up-to the date), or perhaps a list of entries and/or tags. For example:

**render-hw(2012-11-17, spring-2012)**

This might be a script called 'render-hw' where we pass a date (setting the first filter/threshold for the rendering limit) and a tag (eg. 'spring-2012'). This way, we can keep all the content in the repository from one semester to the next, but tag the new copies differently. Flipping just the tag on the index will make sure that we don't accidentally publish something from the previous year.

## How do we do this?

I found a nice tutorial on this subject here:

[Jekyll Post Series Lists](http://realjenius.com/2012/11/03/jekyll-series-list/)

This is, roughly, what I want to do. Given my Ruby-Fu is a bit weak, this will get me started.