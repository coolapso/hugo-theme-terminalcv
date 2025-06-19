+++
title = "Hello World"
date = "2025-06-18"
category = "News"
author = "coolapso"
description = "Hello world, welcome to your temrinal cv with blogging skills!"
+++

# Creating posts!

This hugo theme supports posts, you can write your posts in markdown then they will be rendered in markdown and shown by the `cat <postname>`  command

## markdown elements

All markdown elements will be rendered to html by hugo

### How do I create a post? 

You can create a post by placing your post in `content/postname/index.md`, generate the website and your good to go, now the visitors of your website can then get your post by doing `cat yourpost` and the post will be shown in your terminal.



### How do users find available posts? 

With the command `posts` the command posts should list all the posts available for the users to `cat` 

{{< figure
  src="posts/examplepost/images/terminal.png"
  alt="terminal"
  link="posts/examplepost/images/terminal.png"
  caption="terminal image"
  width="200"
>}}

images are also supported, create a `images` dir inside your `postname` dir, and place the images there. To load the image it will work just like writing any markdown document, example: `
[![terminal](images/terminal.png)](images/terminal.png)`

or you  if you need more controle you can use hugo `figure` shortcode: 

```markdown
{{</* figure
  src="posts/examplepost/images/terminal.png"
  alt="terminal"
  link=posts/examplepost/images/terminal.png"
  caption="terminal image"
  width="200"
*/>}}
```

### Example 

You can always look at the exampleSite dir in the template repository where this post is located
