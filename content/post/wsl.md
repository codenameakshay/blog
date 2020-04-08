---
title: "How to install Linux ON Windows?"
date: 2020-04-08T12:01:51+05:30
hero: /images/hero-10.png
excerpt:
draft: false
authors:
  - Akshay Maurya
layout: "ghostwriter"
---
Most people (devs) that use windows sometimes feel that if they had linux it would have been a lot easier. But due to the list of Apps on Windows, its features or just the complication of process of switching to Linux hold them back to do so. But recently Windows 10 released an update which allows to install Linux on Windows (Windows Subsystem for Linux). Today we will install WSL and see how to use it.

## Steps to install WSL

First open command line and type this
```
Enable-WindowsOptionalFeature -Online -FeatureName Microsoft-Windows-Subsystem-Linux
```
Then it will prompt to reboot the system, so do so.

Then you need to search for Linux in the Windows store.

![](/images/a1.png)

In the Windows Store download Ubuntu, or any other distro that comes.

![](/images/a2.png)

Then after it gets downloaded, simplhy go to the Powershell and type `ubuntu` and press <kbd>Enter</kbd>.

It will install Ubuntu, in your System and now you just need to download `Windows Terminal (Preview)` from the Windows Store. 

![](/images/a3.png)

It has some good features like multiple tab based terminals and more. Then after it gets installed you simply just need to open it and the click on dropdown menu beside new tab button and select Ubuntu there.

![](/images/a4.png)

Now linux is installed and you can install programs here. If you install VSCode here in linux you can open it to do more things like viewing the folders in Linux and more.