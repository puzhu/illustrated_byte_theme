---
title: "Function syntax"
date: 2021-09-05T12:27:11+06:00
image: "assets/functions_syntax.gif"
# description
description: "This is meta description"
tags: ["programming"]
draft: false
---
In an earlier [post](https://www.illustratedbytes.com/blog/series_intro_to_r/02-second_post/) we saw how we could save a series of programming commands in a script and then source that script whenever we needed to execute the same sequence without having to type it all out again.

Functions are a similar concept in programming but with a key added feature. Instead of simply running the sequence of commands, you can specify additional parameters that the can be used within those commands.

For instance, consider the following function `sum(32, 15)`. `sum` is the name of the function and 32 and 15 are the arguments that were passed to the function. If we executed this function we would expect it to `return` the value 47. If we changed the values of the arguments to some other numbers then the output of the sum function would change accordingly. In programming terminology, whenever we use a function in our code it is referred to as being called with its arguments. Here we call the function print with the argument "Hello World".

![](assets/functions_syntax.gif)<!-- -->