---
author: Philippe Audebaud
title: Site creation
excerpt: Construction of the site
layout: post
categories: 
  - Colophon
tags: 
  - colophon
published: true
---

This is a *dynamic* site, instead of [Jekyll][] sites, from which it borrows some ideas.
It aims at running on servers running **PHP** and no much more.

### Components

- Page edition through [prose][];
- Page rendering with [php-markdown][];
- Page templeting with [h2o-php][];
- Routing, API and more with [slim][].

[prose]: http://prose.io/ (A content editor for GitHub)
[slim]: http://www.slimframework.com/ (PHP micro framework)
[h2o-php]: http://h2o-template.org/ (A beautiful template markup for PHP in django style...)
[php-markdown]: https://github.com/wolfie/php-markdown (PHP engine for Markdown)
[Jekyll]: http://jekyllrb.com/ (Jekyll - Simple, blog-aware, static sites builder)