# Cambridge Software Craftsmanship Community blog

This blog is open-source, and community-editable. I guess it's a bit like a wiki, but in blog format; maybe a [bliki](http://www.martinfowler.com/bliki/WhatIsaBliki.html). It is built on [Octopress](http://octopress.org/), which, in turn, is built on the [Jekyll blogging engine](http://jekyllrb.com). Octopress is ["built for hackers"](http://octopress.org/docs/setup/), so you will need to be comfortable in a command-line environment. 

## Pre-requisites

0. Fork the repository on GitHub.
1. Install Ruby 1.9.3 or higher. (1.9.3 is recommended on Windows).
2. Ensure you can run `gem` and `rake` from the command line.

## Getting started

1. Clone your fork of the repository to your local machine
2. To install the necessary dependencies for Octopress, run `gem install bundler` followed by `bundle install`
3. Run `rake install` to build Octopress
4. Run `rake setup_github_pages` to configure your local environment for GitHub pages.
Ensure you supply https://github.com/camswcraft/camswcraft.github.io.git as the URL.

## Writing a post

1. At the console, type `rake new_post["Post title"]`.
2. Edit the generated file in your editor of choice.