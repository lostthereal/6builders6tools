---
sidebar_position: 2
sidebar_label: 'How contributing works'
title: 'How contributing works'
tags:
  - Contributing
  - Getting Started
---

# How this works
This website was built in such a way that creating a markdown file in the docs folder will create a new entry in the sidebar. Making a new folder makes a new dropdown in the sidebar and making a new markdown file in that folder makes an entry in that folder's dropdown. You can modify folders and files by cloning the [GitHub](https://github.com/therealrealguy/6b6twiki/) repository.

## What are markdown files?
Markdown files are a type of website editing file, ending in the extension **.md**. Markdown files are very similar to HTML as it lets you edit the way text looks, along with other aspects of the website. For example, you can make a text **bold**, *italic,* <ins>underlined</ins>, and much more. Learn more about markdown files in [this tutorial](https://www.youtube.com/watch?v=_PPWWRV6gbA&t=60s)

## I have made changes to a file locally, then what?
After you've made changes in your *own* repository, make a pull request to the [GitHub repository](https://github.com/therealrealguy/6b6twiki/). If it gets accepted it will get merged with the project and if the build is sufficient and doesn't have any errors, automatically build itself and deploy on Vercel. However if your pull request gets rejected, it doesn't get merged with the project.

## How can I view the changes I made?
You can run `npm install` (to make sure all packages are installed) and `npm run start` to run the website locally and go to the address in the console. The website automatically restarts when a file changes so you do not need to restart it manually.
**NOTE:** The website you are looking at is only accessible to people connected to your network
