---
layout: post
title:  "Delegate Conforming to Multiple Protocols in Swift 3"
date:   2017-01-11 14:41:00 -0700
categories: ios
---
Delegates in Swift can conform to multiple protocols by using the **&** operator.  For example:


```
protocol AbcDelegate {
}

protocol XyzDelegate {
}

class Sample {
  var delegate: AbcDelegate & XyzDelegate
 
  init(delegate: AbcDelegate & XyzDelegate) {
    self.delegate = delegate
  }
}

class MyViewController: UIViewController, AbcDelegate, XyzDelegate {

  func doSomething() {
    let sample = Sample(self)
  }
}
```