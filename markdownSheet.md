---
layout: page
title: Using Markdown to Write Webpages
permalink: /markdown/
categories: ['Technical']
---

**Markdown** is a formatting language like HTML but much simpler. It allows you to use simple symbols to produce website elements like links, headings, and embedded images. 

Below is a cheatsheet for the most common markdown elements that you'll use. For this formatting to work on your website you need to make sure you include the header found on the sample blog post, you need to save additional posts in the `_posts` folder, and you need to save them as `.md` files: 

###Headings
To make a line a heading place a # immediately before a word. Using more #s will produce smaller headings. So
#Largest Heading
##Second Largest Heading
###Third Largest Heading

###Formatting Words 
*word* will italicize a word

**word** will bold a word 

`word` will render a word or chunk of words as code. For multiple lines use 3 of these marks: 

```
code code 
code code 
code code 
```

To set apart text as a blockquote just put an `>` in front: 

> I want this line to stand out. 

### Lists 
**Bulleted lists**

+ Use plus signs for bullets
+ Like this 

**Numbered lists**

1. Just numbers
2. Like so

If a list isn't rendering properly, you probably need to add a a blank line before it. 

###Inserting Links and Media 

**Link** - Here is how to do a link to the [Miami](https://www.miamioh.edu/) homepage. Brackets around the text and parentheses around the destination link. 

**Image** - I can embed an image with similar formatting -- I just add an ! in front. Here's a Leonardo da Vinci's notebook: 
![notebook](https://i.pinimg.com/originals/70/21/be/7021bed25819ee35494703a53299be69.jpg)

If I want to change the size of the image, I can use the typical HTML formatting: 
<img src="https://i.pinimg.com/originals/70/21/be/7021bed25819ee35494703a53299be69.jpg" width="100">

**Video** - For video, you can just copy and paste the `embed` link for a video (typically this is in a `<iframe` tag. 

<iframe width="560" height="315" src="https://www.youtube.com/embed/ioPT8oDoG_I" frameborder="0" allowfullscreen></iframe>

There are many more things you can do. Just [google](https://www.google.com/search?q=markdown+formatting&oq=markdown+formatting&aqs=chrome..69i57j69i60j0l4.3563j0j7&sourceid=chrome&ie=UTF-8) markdown formatting!

