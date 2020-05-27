---
title: 推荐栏目rem布局比例
date: 2019-12-26 17:38:26
tags:
    - javaScript
---

推荐栏目rem布局，iphone6下貌似是18.75px
<!-- more -->

```
function resize () {
  let fontSize = window.innerWidth >= 640 ? 32 : window.innerWidth / 20
  document.getElementsByTagName('html')[0].style.fontSize = fontSize + 'px'
  fontSize = null
}
resize()
window.onresize = resize
```
