---
layout: article
title: Build A Website with Jekyll and GitHub Pages
permalink: /tech_tutorials/jekyll-website
key: Jekyll-webstie
cover: assets/images/tutorial covers/jekyll-website.PNG
tags:
- Jekyll
- Website
- GitHub Pages
---

Creating a [Jekyll](https://jekyllrb.com) website through [GitHub  Pages](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/creating-a-github-pages-site-with-jekyll) allows you to customise your site. This method I go through uses Git to handle changes and you can push the source to the master branch of your username.github.io repository. To be able to work thorugh this tutorial you should have a handle on working withing the space of GitHub and Visual Studio Code (VS Code).

The great thing about building a website with Jekyll is that you don't have to start from scratch but also have the flexibility to customise as you like! A Jekyll theme is basically the foundation of your site, it has the structure, look and features inbuilt depending on the theme you choose. Once you get started you can add your content and edit the website from this foundation.

First find a Jekyll theme you like, here are some different galleries to try:

- <http://jekyllthemes.org>

- <https://jekyllthemes.io>

- <https://jamstackthemes.dev/ssg/jekyll/>

- <https://jekyll-themes.com>

To be able to compelete this tutorial you'll need to install some software on your computer, these are needed to get the website started and allow you customise your content.

**Install the follwing:**

- [Jekyll and Ruby on Windows](https://jekyllrb.com/docs/installation/windows/)

- [Visual Studio Code](https://code.visualstudio.com/download)

- [Git](https://git-scm.com/downloads)

- [GitHub Desktop](https://desktop.github.com)

## Creation Steps

### Initial Setup

1. Open the themes github repository and create a new fork from it
2. Name the repository name as  `yourusername.github.io` and create repository from template
![Create repository](/assets/images/jekyll/create-repository-owner.png)

3. Open GitHub Desktop got to File and Clone a repository to a local path
4. You can now open this repository in Visual Studio Code (VS Code)
5. In your terminal window run this command:

```shell
$ gem installer bundler
```

6. Open the _Gemfile_ and add the following line 

```md
gem 'github-pages', group: :jekyll_plugins
```
7. Follow the _README.md_ to ensure you customise the _config.yml_ file and setup the properties for your site as required. The _config.yml_ file is placed in the root directory
8. To see a local preview of your site run `bundle exec jekyll serve` then visit <http://127.0.0.1:4000> to preview your site

### Build and Publish

Since we're hosting the site on GitHub pages we need to commit the changes you made in source control and push commits to the master branch of your username.github.io repository.

In the settings of your site repository on Github go to Pages. We want to direct the source for our GitHub Pages site so as the branch select _master_ and for the folder select _/(root)_ and save your changes.

![Build and Development](/assets/images/jekyll/build-development.png)

You can now visit your site on <https://username.github.io>, wait a few minutes for changes to be completed. Even though you can see that within the repository that your changes have been made, it does take the site several minutes later.

### Other Setup Resources

This website is also another great resource [Build a Jekyll development environment with VS Code & Remote Containers.](https://powers-hell.com/2021/07/25/build-a-jekyll-development-environment-with-vs-code-remote-containers/)

### Issue Related Resources

[GitHub Page Setup](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll#installing-jekyll)