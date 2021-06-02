---
title: "Create Your own Editor | But Should You?"
date: 2021-05-20T15:53:56+05:30
draft: false
tags: ["editor", "web", "development", "quill", "text"]
summary: "How to add a Text Editor to your Site? What options do you have? Things to consider."
editPost:
  URL: "https://github.com/adityavinodh/blog/tree/main/content"
  Text: "Suggest Changes"
  appendFilePath: true
---

# When do you need an editor?

Nowadays, the trend seems to be leaning towards web development and web apps rather than native alternatives. Along with this trend, even simple applications require more complex feature sets and are built with a mobile-first design in mind, as well as a dynamic/responsive site. Any application that requires user input as text, images, or other multimedia content, will require some sort of an editor to implement. Even a simple website where you display articles or blogs, might require users to submit comments. But users are rarely satisfied with simple text and emojis. They might prefer to add an image, make the text bold or italic, embed a YouTube video, etc. These features require developers to implement an editor of some sort into their web apps.

# How to get Started

### Drop-in solution

![Quill Screenshot](/quill-screenshot.png)

There are quite a few options available to consider when implementing a text editor in your website. The first and most straight forward option is to use something like [Quill](https://quilljs.com/). This allows you to drop in the editor into your existing website with minor configuration and modification. You can pick a design or layout from one of the few existing options, and apply it to the website. This works for most web apps, with minor additional work arounds for frameworks like React. The video below shows an implementation to create a Google Docs clone.

[Video by Web Dev Simplified - Google Docs Clone](https://www.youtube.com/watch?v=iRaelG7v0OU)

### Create your own

![SideTracked Editor Screenshot](/sidetracked-editor-screenshot.png)

This is something that I do not recommend, unless you think you want to completely customize the behaviour. In my case, I wanted to explore and try it out, so I decided to make it as portable as possible, and prioritize features that are important to my app.

Decide the features that are most important. In the case of a blogging or article publishing site, there are not going to be too much of formatting required. Blocks of text or media that follow a consistent style or format has been the trend, and is also visually more pleasing. So, you can set the style before hand, and then allow users to add sections of text or media from a list of options that you provide. You can allow a title, a subtitle, a smaller heading, a standard paragraph, a quote, an image, a video (maybe a YouTube embed), etc. You can style and theme the page appropriately for these formats. Make sure you can export the content with the actual data (links in the case of images, or actual links) and the meta data to style it. JSON is a good idea. The issue that you might run into is to make certain parts of a section, like certain words, italics, bold, or underlined. This is not too important, but might be something to consider.

This data can now be converted and stored in any database.

# Bonus (Community Comments)

If you just want to implement a comment section for your website, you can use a service like [Disqus](https://disqus.com/). This is used on my blog that you are reading right now. You can check it out at the bottom of the blog. (No affiliation with Disqus)

These features can get quite advanced and distracts you from the main focus of your app. Disqus makes it dead-simple to drop it in to your app, with their simple editor for users to submit comments, reply to other comments, and react to your posts. It even includes moderation.
