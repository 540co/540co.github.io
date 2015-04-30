---
layout: post
title:  "How to write a post!"
date:   2015-04-21 15:20:15
author: George Washington
tags:   
excerpt: "Add a small excerpt to show a preview of the post from the list of news/posts"
image: /assets/540-logo.png
---

###Creating a post

###Metadata, explained

Begin the new markdown file by adding "YAML front-matter." This is where the post's title, authors, tags, and excerpt/description live.

Here each required field:

* title - The plain-text title of your post. Surround with quotation marks. This will be displayed prominently above the post, will show up in browser tabs, and will be included in "share text" when the link appears on Twitter, Facebook, and other social media platforms.

* image - The main image of your post. A relative link, with a leading /. This will appear in social media platforms when the post is shared. It can be a different image than those which appear embedded in your post.

* description - A short plain-text description of your post. Surround with quotation marks. No Markdown or HTML allowed. This does not need to be an excerpt, but instead can be a sentence or two that you feel represents your post well. It may appear next to your post on social media and other places which fetch article metadata.

* excerpt - A short plain-text snippet of the post to use as the "nut graf" that appears on the home page.

* authors - A list of handles of teammates involved in authoring the post. They must all be lowercase, and must match a name that appears in _data/team.yml They do not necessarily have to be the same teammates that appear in the post's byline.

* tags - A list of tags to associate with the post. These will appear, linked, next to the post and will take readers to other posts that have this tag. Sentences (e.g. "how we work") are fine — there is no need to jam phrases into one word