---
layout: post
title:  "Full Width Separator Lines in UITableView"
date:   2017-01-27 09:55:00 -0700
categories: ios
---
Set the following in your **tableView:cellForRowAtIndexPath:**

**Objective-C**
```
cell.preservesSuperviewLayoutMargins = NO;
cell.separatorInset = UIEdgeInsetsZero;
cell.layoutMargins = UIEdgeInsetsZero;
```
