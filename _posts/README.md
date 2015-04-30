#540 Blogging Guide

This document describes 540's blogging process (both policy and technical). 540's blog is at https://news.540.co, and is part of the overall 540 website at https://540.co.

Our blog uses Jekyll as a blogging framework which runs on GitHub Pages.

#How to write a blog/news post

Please use this process as guidence when planning, drafting and deploying posts.

### Working with drafts

Drafts are posts without a date. They’re posts you’re still working on and don’t want to publish yet. Simply write your draft in markdown format and post it to the `_drafts` folder with just the `title.md`.

Once the draft if reviewed and approved it is ready to be published. Follow the below steps to finalize a draft post.

### Working with final posts

To create a new post, all you need to do is create a new file in the `_posts` directory. How you name files in this folder is important. Jekyll requires blog post files to be named according to the following format:

```
    YYYY-MM-DD-title-of-your-post.md
```

###Content Formats

All blog post files must begin with YAML Front Matter. After that, it’s simply a matter of deciding which format you prefer. Jekyll supports Markdown out of the box. For a more detail example you can simply copy the `how-to-write-a-post.md` file from the `_drafts` folder and start writing.

Begin the new markdown file by adding "YAML front-matter" above. This is where the post's title, authors, picture, and excerpt/description live. 

###Example YAML Front Matter
```
---
layout: post
title:  "How to write a post!"
date:   2015-04-21 15:20:15
author: George Washington
author_image: name.jpg
excerpt: "Add a small excerpt to show a preview of the post from the list of news/posts"
---
```

###Metadata, explained

* `title` - The plain-text title of your post. Surround with quotation marks. This will be displayed prominently above the post, will show up in browser tabs, and will be included in "share text" when the link appears on Twitter, Facebook, and other social media platforms.

* `date` - The date of the post is going to be deployed. Must be in the "YYYY-MM-DD" format.

* `author` - A team member involved in authoring the post.

* `author_image` - The profile picture for the post. Just use the file name of the picture that is located in the "assets/images/team" folder.

* `excerpt` - A short plain-text snippet of the post to use as the "nut graf" that appears on the home page.

* `image` (optional) - The main image of your post. A relative link, with a leading /. This will appear in social media platforms when the post is shared. It can be a different image than those which appear embedded in your post.

* `description` (optional) - A short plain-text description of your post. Surround with quotation marks. No Markdown or HTML allowed. This does not need to be an excerpt, but instead can be a sentence or two that you feel represents your post well. It may appear next to your post on social media and other places which fetch article metadata.



###Link blog post assets

Blog post resources should be committed to this repository. This includes images, JavaScript, additional CSS, wtc.

This helps keep everything in one location for easy use.

If your blog post uses assets, then:

Make a new asset directory in the `assets/blog/` directory, like this:
    
    assets/blog/title-of-blog-post/

Put images and assets into this directory, like so:

    assets/blog/title-of-blog-post/blog-header.jpg

Use relative links in posts, with a leading slash and a title attribute, like this:
    
    ![photo name](/assets/blog/title-of-blog-post/blog-header.jpg)

or in HTML:

    <img src="/assets/blog/title-in-blog-post/blog-header.jpg" title="blog header" />
