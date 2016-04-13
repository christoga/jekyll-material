---
layout: post
title: Get dropdown value in javascript
date: 2016-03-05
categories: tips-tricks
author: Andre Christoga
header_image: img/dropdown.png
---

So.. The project that I have been working on is called "Cepat Sembuh", <br>
The project have a form that use a dropdown to get the value / select option

I try to use this code <br>
```
var input = $('#input').val();
if (input == 'first') {
  window.location.href = 'first.html';
}
else {
  alert('Error');
}
```
<br>

Because this code doesnt work, so I try to ask somebody in [Stack Overflow](https://stackoverflow.com) and I also search for it in [Google](https://google.com)<br>
But, none of it actually help me with my problem

Finally, I try to solve it with my own knowledge of javascript <br>
```
var input = $('#input').val();
var link;

switch (input) {
  case first:
    window.location.href = 'first.html';
    break;
  case last:
    window.location.href = 'last.html';
    break;  
}
```
<br>

I actually think this code only available for text input, it actually works on dropdown too!
I'm going to explain the code down below:👇

## Documentation
Rather than using `if` and `else`, I use `switch` and `case`,<br>
I'm using jquery to get the input value: `var input = $('#input').val();`
<br>
`case` in the switch code is like if, you can create a lot of them using only `case`.<br>
U didn't need to use `else if` or new `if` condition
<br>
Hoping the tutorial will help you!😀
