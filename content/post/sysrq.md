---
title: "Why is there sysrq key on my keyboard?"
date: 2020-08-27T10:18:41+05:30
hero: /images/hero-7.jpg
excerpt:
draft: true
authors:
  - Akshay Maurya
---
The answer to this question lies further back in time. Let's begin first by looking what is SysRq.

# What is sysrq?
The magic SysRq key is a key combination understood by the Linux kernel, which allows the user to perform various low-level commands regardless of the system's state. It is often used to recover from freezes, or to reboot a computer without corrupting the filesystem. Its effect is similar to the computer's hardware reset button (or power switch) but with many more options and much more control.
This key combination provides access to powerful features for software development and disaster recovery. In this sense, it can be considered a form of escape sequence. Principal among the offered commands are means to forcibly unmount file systems, kill processes, recover keyboard state, and write unwritten data to disk. With respect to these tasks, this feature serves as a tool of last resort.