---
title: "An app to track Coronavirus and show Country-based Stats"
date: 2020-04-16T00:38:14+05:30
hero: /images/hero-7.jpg
excerpt:
draft: false
authors:
  - Akshay Maurya
---
Today, I am going to share an app which I made using Flutter to show that stats for COVID-19 or as people commonly call it the CoronaVirus.

# Stay Safe Coronavirus Tracker

This app basically tracks the total cases of infected persons (real-time data), in all countries with total deaths and recovered cases too.
It features beautiful UI with custom animations. It has charts, global info, symtomps and other COVID-19 related info and much more stuff.

You can download the app from [GitHub](https://github.com/codenameakshay/stay-safe-flutter-app).


## Demo

![](/images/examples/demo.gif)

![](/images/examples/1.jpg)

![](/images/examples/2.jpg)

![](/images/examples/3.jpg)

![](/images/examples/4.jpg)

![](/images/examples/5.jpg)

![](/images/examples/6.jpg)

![](/images/examples/7.jpg)

![](/images/examples/8.jpg)

## Usage

Simply download the apk-release.apk from `examples/` directory and install it.
Or if you want to use this in your App simply clone the repo. I also have two much lighter build in the branches `gui` and `updated_gui`. If you want to implement this app inside your app then consider those as they have bare components needed.

If you need API it's this [API.](https://pomber.github.io/covid19/timeseries.json)

UI Design inspired by these links - [Dribble](https://dribbble.com/shots/10765598/attachments/2434179?mode=media), [Dribble](https://dribbble.com/shots/10847147-Coronavirus-Covid-19-Dashboard/attachments/2500286?mode=media).

## Things to do

- [ ] Implement pull to refresh efficiently
- [ ] Show top countries in a list on Info page
- [ ] Improve the Bottom Nav Bar with animations
- [ ] Change tabs by swiping between them
- [ ] Chnage countries by swiping between them on ResultPage
- [ ] Include Dark mode
