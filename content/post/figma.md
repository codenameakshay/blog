---
title: "Going from Figma to Flutter in just 5 minutes"
date: 2020-05-13T14:34:44+05:30
hero: /images/hero-7.jpg
excerpt:
draft: false
authors:
  - Akshay Maurya
---

![](/images/figma/hero.jpg)

When I started developing apps with Flutter, there was this thing that one has to develop UI only using **code**. This makes it quite hard to visualise how the app will look beforehand. To solve this problem, **Figma** comes to the rescue. Using it, one can design beautiful UIs and assets for there application and then export them as images, which then can be used in Flutter using *`Image.asset`* objects. But there is one limitation to this that, even for like changing the color of button, you have to again export the image, import it into assets, and then rebuild the app to include those assets. But, today I will show you one trick to convert Figma components and Frames directly to Flutter code whic then uses **`Custom Painter`** to draw those things in the application. So, if you need to change the properties of the asset, you can simply change them in the code.

So, let's get started.

# Step-1 Get Figma API key

For this step, first open you figma account on a browser, then click on your account name.
![](/images/figma/1.jpg)
This will take you to the Account page. Then click the settings tab, to go the settings page.
![](/images/figma/2.jpg)
Then in the Personal Access Token section click on `Create a new personal token`.
![](/images/figma/3.jpg)
Then generate your API key and make sure to copy it in a safe location because this is the last time Figma is letting you see it. We need it later on in this tutorial.

# Step-2 Design your assets or UI in Figma

![](/images/figma/Frame1.png)
In this step, you just need to draw the assets that you need. I am going to draw a button for demo purposes.

![](/images/figma/6.jpg)

# Step-3 Open Figma to Flutter app

Now after you have designed all your assets and converted them into **`components`**, just go to [https://aloisdeniel.github.io/figma-to-flutter/](https://aloisdeniel.github.io/figma-to-flutter/). Now in this website simply type up your *`API key`* in the `authentication token` section.
![](/images/figma/4.jpg)

# Step-4 Getting your file code

Now go to the file in Figma in which you have drawn your asset,

![](/images/figma/6.jpg)

then go to the address bar and copy the highlighted text between the slashes.

![](/images/figma/5.jpg)
This is your *`file_key`*.
Now enter this *`file_key`* in the given section, in the Figma to Flutter app.
![](/images/figma/7.jpg)

# Step-5 Generating component code

Now click *`Load components`* and then select the components from the list that pops up below, which you wanna import.
![](/images/figma/9.jpg)
Then click generate Dart code, to load the code in the code tab.
![](/images/figma/8.jpg)
Now just click copy to clipboard, to copy this code.
![](/images/figma/10.jpg)

# Step-6 Importing code into Flutter

Now, open your Flutter project in your editor and then create a new file in your `lib` folder, named *`button.dart`*.
![](/images/figma/11.jpg)
Then simply paste your code into this file and save it. Now you just need to import this file in your *`main.dart`*, or wherever, you want to use it, in this case it's *`main.dart`*. Then simply import the component widget by it's name like I have in the code below.

{{< gist codenameakshay e13721ac6b77c3d85335791ff2bf42a8 >}}

{{< gist codenameakshay c933eed0e783357705847f1a9ac0e0c3 >}}

>Note - You may also need to include images that you used in Figma, in your assets in Flutter.
>![](/images/figma/12.jpg)

# Step-7 Build your app

![](/images/figma/13.jpg)

Now, as you can see this is the result.

{{< figure src="https://media.giphy.com/media/dpnfPvaCIHBrW/giphy-downsized.gif">}}

This looks far from perfect, but it was an easy and fast way to simply import assets from Figma into Flutter, and with a little bit of tweaking here and there, it will be perfect.