---
layout: post
title:      "YLSNED: PRY and print page.html"
date:       2018-03-24 21:56:26 +0000
permalink:  ylsned_pry_and_print_page_html
---


Most of my time is figuring out why something that seems to be working on the web is not working in the spec tests. 99% of the time, it's syntax - missing carats, percent signs, a combo of both, the list goes on. I've wondered how I can troubleshoot those errors, but could never find anything. Let me introduce you to: print page.html.

This command comes in very handy when you need to view the html page during the spec test. All you need to do is put your pry command after the "visit xxx" capybara command, run the tests and then at the break command line, type: print page.html. Now you will be able to see what the page should look like.

I've found this very helpful when trying to figure out if the spec tests want<ul> vs <li>, etc.

HTH!
