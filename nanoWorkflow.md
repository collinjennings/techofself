---
layout: page
title: Basic Nano Workflow 
permalink: /nano/
categories: ['Technical']
---
Here's the step-by-step workflow: 

### Logging in and Opening a Post
1. Log into the virtual machine at [54.226.207.212](http://54.226.207.212)
You are now in your "root" folder that is the folder that corresponds to your uniqueID. 

2. Navigate to your `_posts` folder using the `cd` (change directory) command:
	- Either: `cd www' then cd `_posts`
	- Or: `cd www/_posts`

3. Open an older post in `nano` to work from. For example,
`nano 2017-09-08-welcome-to-jekyll.markdown`

### Creating a New Post
4. Update the heading and save as a new post:
![screen4]({{site.baseurl}}/assets/nano1.png)

5. Delete the old text: 
![screen4]({{site.baseurl}}/assets/nano2.png)

6. Add new text and formatting:
![screen4]({{site.baseurl}}/assets/nano3.png)

### Building the Website with the new post
7. Save the post (`Control + O`) and exit `nano` `Control + X`

8. Move up to the `www` folder. The easiest way is `cd ..` (that's with a space), which moves you up one folder in the system. 

9. Run the build command: `jekyll build -- destination ../public_html` 

If you want to build the website without exiting `nano`, you can always open two windows and have `nano` open in one and just the terminal in the other, then write in one, save, and build the website in the other folder. 

If you have want to delete a post, you can go into the `_posts` folder then run the remove command: `rm filename`. That will delete the file -- be careful, you can't get it back! And remember that if you just want to list the folder contents: `ls` (which is the list command).


