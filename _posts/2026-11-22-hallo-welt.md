---
layout: post
title: "Hello, World! My First Blog Post with ChatGPT and Codex"
description: "A personal experiment with ChatGPT, Codex, Jekyll, and GitHub Pages."
---

Hello, world! With this post, I want to see what blogging feels like with my new toolchain. Can I just tell ChatGPT what I want to write about and, a little later, read a draft that's already in the right format in my repository? That's what I'm testing here.

## What's under the hood

The content lives in Markdown files in my GitHub repository, `greenacid/greenacid.github.io`. Jekyll turns those files into a static website. The title and layout are set at the top of each file, and Jekyll inserts the text into the template. The same build generates the homepage with its list of posts and the RSS feed.

GitHub Pages builds and publishes the site from the `master` branch. The `CNAME` file sets the custom domain, `blog.3wfx.de`. The Jekyll configuration uses the blog's HTTPS address so the pages and the feed point to the same domain. GitHub Pages redirects HTTP requests to HTTPS.

## How an idea becomes a post

I start with an idea and explain it to ChatGPT, OpenAI's AI assistant. I tell it what the post should cover, which details to include, and how I want it to sound. That gives me a draft. Codex handles the repository work and saves the text as a Markdown file. I can take my time reading it and ask for changes before it goes live.

That's the process I used for this Hello World post. Once I'm happy with a draft, it can move into the `_posts` directory. When the change lands on `master`, GitHub Pages rebuilds the site. The post then appears on the blog and in the RSS feed.

## What's changed about writing

Writing has become incredibly easy for me this way. I can talk through my thoughts as they come to me. I don't have to type them out or work on sentence structure while I'm still explaining the idea. ChatGPT puts those thoughts in an order that's easy to follow, and when I read the draft, I decide whether it says what I meant.

It remains to be seen whether I'll turn this into a habit and publish good posts regularly. But it's already much easier to turn an idea into a post. For a Hello World post, that's a good start.
