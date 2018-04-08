# BoulderDSA.org

The source files for the [website of the Boulder DSA](https://boulderdsa.org).  Currently not yet live.

Deployed to GitHub Pages using Jekyll, and styled using Bootstrap 3.

To test locally, install [Jekyll](https://jekyllrb.com/docs/quickstart/) and Bundler, clone a local copy of the repository, and run `bundle exec jekyll serve` to build the site and serve it at http://127.0.0.1:4000.

Changes can be suggested on the [#cmte-website](https://boulderdsa.slack.com/messages/C9V8MMPFT/) channel on the Boulder DSA Slack, provided as edited files on Slack, or even as a pull request from a forked repository (if you know what you're doing).

News posts should be [Markdown formatted files](https://www.markdownguide.org) ([cheat sheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)) in the `_posts` folder, with the filename format `YYY-MM-DD-post-title.md`.  They should start with 

````
---
title: News Post Title Here
author: Author's name (unless if anonymous/by "Boulder DSA")
tags: space-separated-categories
---

<text of the blog entry here.  First paragraph (separated by a black line) is taken as the exerpt.>
````

With images specified as `![Description of image](/images/news/image-name.jpg){:.img-responsive}`.
