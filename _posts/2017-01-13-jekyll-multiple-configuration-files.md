---
layout: post
title:  "Jekyll With Multiple Configuration Files"
date:   2017-01-13 11:07:00 -0700
categories: jekyll
---
By default, the Jekyll configuration goes in your **_config.yml** file.  You can create a second configuration file.  For example, **_second.yml**.

To use both configuration files at the same time, run either of the following commands:
```
$ jekyll build --config _config.yml,_second.yml
$ jekyll serve --config _config.yml,_second.yml
```