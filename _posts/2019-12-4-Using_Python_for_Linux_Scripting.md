---
layout: post
title: Using Python for Linux Scripting
---

I like to use linux at home. It's very convenient. I like being able to customize every single thing about my computer, down to the shape of the taskbar. Sure, good software is hard to find, but I like the programs that *are* on there. 

The only issue I have is scripting. I'm not saying that scripting is easy on Windows or OSX, but I *am* saying that it is still difficult on most Linux systems. 

I use zsh with [Oh My Zsh!](https://ohmyz.sh/) for beauty, but I am still able to write scripts in basic bash. My terminal is highly customized, so I almost never have to script anything. But when I do, it's a hassle. Bash syntax is totally foreign to me, and it looks more like BASIC than a real language. But I found out that some people use python for scripting. 

Python is super simple, and it almost looks like psuedo-code. For example:

```python
foo = 3
if foo % 2 is 0:
  print("foo is even!")
else:
  print("foo is odd!")
```

This is super easy to read, maybe even if you've never coded. And because python comes with modules designed to interface with the operating system, it's totally feasible to use it for system scripting. Sadly, I haven't found much information on starting to use python as the dedicated scripting language or any tools that are useful for doing so. 

I'm going to try using python to write scripts and I'll report back my findings. 

In the meantime, good luck debugging!

*--Ramiro Rocha*
