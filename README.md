# Cambridge Software Craftsmanship Community blog

This blog is open-source, and community-editable. I guess it's a bit like a wiki, but in blog format; maybe a [bliki](http://www.martinfowler.com/bliki/WhatIsaBliki.html). It is built on [Octopress](http://octopress.org/), which, in turn, is built on the [Jekyll blogging engine](http://jekyllrb.com). Octopress is ["built for hackers"](http://octopress.org/docs/setup/), so you will need to be comfortable in a command-line environment. 

## Pre-requisites

0. [Fork this repository](https://github.com/camswcraft/camswcraft.github.io/fork) on GitHub.
1. Install Ruby 1.9.3 or higher. (1.9.3 is recommended if you're [running Ruby on Windows](http://rubyinstaller.org/downloads/)).
2. Ensure you can run `gem` and `rake` from the command line.

## Getting started

1. Clone your fork of the repository to your local machine
2. To install the necessary dependencies for Octopress, run `gem install bundler` followed by `bundle install`
3. Run `rake install` to build Octopress

## Writing a post

1. At the console, type `rake new_post["Post title"]`.
2. Edit the generated file in your editor of choice.
3. Include your name as the author of the post in the [YAML front matter](http://jekyllrb.com/docs/frontmatter/)
4. Write your post! :smile:

Also be sure to check out the [Blogging Basics](http://octopress.org/docs/blogging/) page on Octopress's documentation.

## Contributing your post

1. Create a pull request from the `source` branch on your fork to the `source` branch on the parent repository.
***Note:** you will need to set the destination branch manually when creating the pull request, as `source` is not the
default branch on the repository.