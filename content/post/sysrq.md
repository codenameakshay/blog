---
title: "Why is there sysrq key on my keyboard?"
date: 2020-08-27T10:18:41+05:30
hero: /images/hero-7.jpg
excerpt: "The answer to this question lies further back in time. Let's begin first by looking what is SysRq."
draft: false
authors:
  - Akshay Maurya
---
The answer to this question lies further back in time. Let's begin first by looking what is SysRq.

# What is SysRq?
The magic SysRq key is a key combination understood by the Linux kernel, which allows the user to perform various low-level commands regardless of the system's state. It is often used to recover from freezes, or to reboot a computer without corrupting the filesystem. Its effect is similar to the computer's hardware reset button (or power switch) but with many more options and much more control.
This key combination provides access to powerful features for software development and disaster recovery. In this sense, it can be considered a form of escape sequence. Principal among the offered commands are means to forcibly unmount file systems, kill processes, recover keyboard state, and write unwritten data to disk. With respect to these tasks, this feature serves as a tool of last resort.

So this was what is SysRq. You now know it is called magic key, and it stands for System Rescue, but what can it do?

# What can SysRq do?
The key combination consists of Alt+SysRq (for Linux Mint, the combination is Ctrl+Alt+SysRq ) and another key, which controls the command issued. SysRq may be released before pressing the command key, as long as Alt remains held down.
Here is the list of commands on the basis of key pressed - 

![](/images/sysrq/cmd.jpg)

# Conclusion

So this is why there is a SysRq key present on your keyboard. It was anciently used for rebooting system during freezes or crashes, and more. Nowadays it is occasionally used to safe reboot Linux computers.