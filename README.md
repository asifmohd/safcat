safcat (beta)
=============
A simple Safari extension that uploads a gif open in the current tab to gfycat and plays it back on said site.

While visiting a third-world country with very slow Internet, I was tired of uploading gifs manually to gfycat to view them smoothly and I saw that there was no such extension for Safari. **I made this extension to learn JavaScript, browser extensions, JSON parsing and the Safari extensions API.**

I have never done anything in JavaScript before and I am certainly new to writing browser add-ons. I am sure I have not followed many best-practices and my code is quite messy. But it is simple and it works with negligible extra load on the browser (pretty sure).

I would appreciate any pointers, tips and improvements to this extension.

Download
--------
Download the extension file here: http://ge.tt/96Wxqnl1/v/0

This is the same file as the one in this repository.

Ways to contribute
------------------
Clone the repository, fork it and create a pull request.
We need to implement an async request to the gfycat.

Changelog
------------------
1.2.0
Added validation for url so that the extension is only enabled on tabs with gif content

1.1.0
Added the ability to notify the user when the extension is updated
