---
layout: post
comments: true
title:  "Markdown Styling"
date: 2024-03-11 22:00:00
---

> Note, this post is only for testing markdown styling for the blog elements.

## Heading 2
### Heading 3
#### Heading 4

Image and [link](../assets/flowers.jpg) to the image

```javascript
var clean_twitter = function(){
  var ugly = [];
  ugly.push('.action-reply-container');
  ugly.push('.action-rt-container');
  ugly.push('.action-del-container');
  ugly.push('.action-fav-container');
  ugly.push('.more-tweet-actions');

  for(var i=0;i&lt;ugly.length;i++) {
    var u = $(ugly[i]).find('b');
    u.text('');
  }
}
```

This is simple `bash` program that gets and sets some data in a file

```bash
#!/bin/bash

db_set() {
    echo "$1,$2" >> database
}

db_get() {
    grep "^$1," database | sed -e "s/^$1,//" | tail -n 1
}
```

#### Improving the quality of markdown
- Use good and minimal styling that shows character
- Use a good theme for code blocks
