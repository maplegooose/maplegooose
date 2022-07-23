---
Title: "Rock Paper Scissors Development"
Author: "Tyler Truong"
Category: "Coding"
Tags: [coding, html, css, websites, games, githubpages]
comments_disable: true
date: 2022-07-20 15:22
meta_modify_date: 2022-07-21 22:28
---

## 7/20/2022

I decided to dedicate my time now to start learning how to code a little game on a website. It was a bit daunting since I didn't know how to transfer that onto a website, but I decided that I should still continue to take any initiatives I can. Using this [tutorial](https://www.youtube.com/watch?v=j59qQ7YWLxw), I was able to get a basic outline on how to do that. I ran into a bigger problem after that, however. Besides needing to understand how to create different elements on HTML, I needed to understand how CSS works since I wanted to create a website from scratch. To do that, I decided to use [CodeAcademy](https://www.codecademy.com) to learn how to do CSS. I don't know how long it'll take me, but it seems simple so far. I'll update my progress on it the next day. I also need to learn how to integrate JavaScript with HTML. That isn't as scary since I've had my fair share of JavaScript using Google Sheets, but hopefully I can make it work and adapt super easily.

## 7/21/2022

Today, I finished the online course from [CodeAcademy](https://www.codecademy.com) for CSS. It went pretty well, and I'm pretty confident in how to code in CSS. The biggest issue I ran into, however, is the fact that when I tried to create my next project, my CSS file would not connect to my HTML file. I was honestly very confused, as I did everything I could to figure it out. It took me several hours until I was browsing on this [thread](https://stackoverflow.com/questions/29576858/css-stylesheet-not-loading) and copied and pasted this line of code:

```css
<link rel="stylesheet" type="text/css" href="css/layout.css" />
```

Somehow...? It all worked. Honestly, I have no idea why it worked. I have two ideas. The first idea could be because I had the formatting wrong and forgot to include `type="text/css"`, or it couldve been the fact I forgot the `/` at the very end. I have no idea, but I'm over it now. All that matters to me is that I finally SOLVED IT. Anyways, now I can actually make some progress in creating a new website to play Rock Paper Scissors against an "AI." I hate coding.

After I finished the painful task of figuring out my small mistake, I went straight to work focusing on just building a simple interface for my small web game. I had difficulty alligning the buttons on the same row, so I had to search it up and figured out that I needed to configure the layout of my buttons to be in a [grid](https://www.youtube.com/watch?v=9zBsdzdE4sM). I feel pretty good about this whole thing now that I'm over that stupid mistake.

## 7/23/2022

Today felt like I made a lot of progress. I was able to code in the entire game. I'm a bit rusty of JavaScript, but I think I did good. My coding could definitely be improved since I had a lot of elif statements that could've been shortened down, but I could always work on that another day. My main issue today is figuring out how to host it on this website. Apparently, we can't have a different Github page for separate repositories, only your main one, so I will be figuring out how to achieve that tomorrow. Honestly, it might be easier than I think. I just have to copy the folder into this and provide a link to my HTML file, which in turn should grab all of the files it needs from its root folder, but I don't think it'll go that smoothly.
