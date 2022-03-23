---
layout: default
title: Introduction
nav_order: 1
description: "Just the Docs is a responsive Jekyll theme with built-in search that is easily customizable and hosted on GitHub Pages."
permalink: /
---

# **Problem?** :trollface:

# :bookmark_tabs: Introduction

Hello! The purpose of this document is to guide you on how to set up a static Node.js web application using Express.js version 4.17.2 that works for both Mac and Windows machines. We will divide the fundamentals of how the software works into smaller building blocks that form the basic structure of complex projects.

Express.js is one of the most popular Node.js back-end web application frameworks that was released as a free and open-source software. It provides many useful features to provide server-side logic for web and mobile applications in a simple and flexible way. It also improves the development work flow for faster back end set-up and easier front-end integration.

---

## :trollface: Intended Users

Regardless of where you are in your development journey, this documentation will provide clear guidance on the basic concepts of Express.js. This guide will be particularly useful for:

* Beginner developers that have basic front-end and back-end knowledge.
* Development teams that want to save time on back-end set up.

## Software Versions

Please have the following installed before proceeding:

* Node.js version 14.17.6 or later
* Visual Studio Code
* Npm Package manager version 6 or later

## Prerequisites

This document requires the following knowledge:

* Working knowledge of the Visual Studio Code terminal
* Basic knowledge of Javascript(ES6), HTML, and CSS to create a static web page
* Working knowledge of the Node.js package manager npm

## Procedures Overview

1. Install the Ruby Gem
  ```bash
  $ gem install just-the-docs
  ```
  ```yaml
  # .. or add it to your your Jekyll site’s Gemfile
  gem "just-the-docs"
  ```

2. Add Just the Docs to your Jekyll site’s `_config.yml`
  ```yaml
  theme: "just-the-docs"
  ```

3. _Optional:_ Initialize search data (creates `search-data.json`)
  ```bash
  $ bundle exec just-the-docs rake search:init
  ```

3. Run you local Jekyll server
  ```bash
  $ jekyll serve
  ```
  ```bash
  # .. or if you're using a Gemfile (bundler)
  $ bundle exec jekyll serve
  ```

4. Point your web browser to [http://localhost:4000](http://localhost:4000)

If you're hosting your site on GitHub Pages, [set up GitHub Pages and Jekyll locally](https://help.github.com/en/articles/setting-up-your-github-pages-site-locally-with-jekyll) so that you can more easily work in your development environment.

## Conclusion

- [See configuration options]({{ site.baseurl }}{% link docs/configuration.md %})

---

## About the project

Just the Docs is &copy; 2017-{{ "now" | date: "%Y" }} by [Patrick Marsceill](http://patrickmarsceill.com).

### License

Just the Docs is distributed by an [MIT license](https://github.com/just-the-docs/just-the-docs/tree/main/LICENSE.txt).

### Contributing

When contributing to this repository, please first discuss the change you wish to make via issue,
email, or any other method with the owners of this repository before making a change. Read more about becoming a contributor in [our GitHub repo](https://github.com/just-the-docs/just-the-docs#contributing).

#### Thank you to the contributors of Just the Docs!

<ul class="list-style-none">
{% for contributor in site.github.contributors %}
  <li class="d-inline-block mr-1">
     <a href="{{ contributor.html_url }}"><img src="{{ contributor.avatar_url }}" width="32" height="32" alt="{{ contributor.login }}"/></a>
  </li>
{% endfor %}
</ul>

### Code of Conduct

Just the Docs is committed to fostering a welcoming community.

[View our Code of Conduct](https://github.com/just-the-docs/just-the-docs/tree/main/CODE_OF_CONDUCT.md) on our GitHub repository.
