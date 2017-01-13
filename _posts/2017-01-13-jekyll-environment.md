---
layout: post
title:  "Jekyll Environment"
date:   2017-01-13 11:01:00 -0700
categories: jekyll
---
When you run either of the two commands below, by default, the **Development** environment is used:
```
$ jekyll build
$ jekyll serve
```

To use the **Production** environment, set the **JEKYLL_ENV** parameter.  For example:
```
$ JEKYLL_ENV=production jekyll build
$ JEKYLL_ENV=production jekyll serve
```


