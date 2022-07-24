# Creating your Website
Creating a [Jekyll](https://jekyllrb.com) website through [GitHub  Pages](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/creating-a-github-pages-site-with-jekyll) allows you to customise your site. This method I go through uses Git to handle changes and you can push the source to the master branch of your username.github.io repository.

Find a Jekyll theme you like, here are some different galleries to try:
- http://jekyllthemes.org
- https://jekyllthemes.io
- https://jamstackthemes.dev/ssg/jekyll/
- https://jekyll-themes.com

** Install the follwing:**
- [Jekyll on Windows](https://jekyllrb.com/docs/installation/windows/) Follow the instructions 
- [Visual Studio Code](https://code.visualstudio.com/download)
- [Git](https://git-scm.com/downloads)
- [GitHub Desktop](https://desktop.github.com)

## Creation Steps

### Initial Setup
1. Open the themes github resporitoy and create a new fork from it
2. Name the reporitory name as  `yourusername.github.io` and create repository from template
3. Open GitHub Desktop got to File and Clone a repository to a local path
4. You can now open this repository in Visual Studio Code (VS Code)
5. In your terminal window run this command: `$ gem installer bundler` 
6. Open the _Gemfile_ and add the following line `gem 'github-pages', group: :jekyll_plugins`
8. Follow the _README.md_ to ensure you customise the _config.yml_ file and setup the properties for your site as required. The _config.yml_ file is placed in the root directory
9. To see a local preview of your site run `bundle exec jekyll serve` then visit http://127.0.0.1:4000 to preview your site

### Build and Publish
Since we're hosting the site on GitHub pages we need to commit the changes you made in source control and push commits to the master branch of your username.github.io repository.

In the settings of your site repository on Github go to pages. We want to direct the source for our GitHub Pages site so as the branch select _master_ and for the folder select _/(root)_ and save your changes.

You can now visit your site on https://username.github.io, wait a few minutes for changes to be completed. Even though you can see that within the repository that your changes have been made, it does take the site several minutes later.

## Other Setup Resources
- [Build a Jekyll development environment with VS Code & Remote Containers](https://powers-hell.com/2021/07/25/build-a-jekyll-development-environment-with-vs-code-remote-containers/)

## Issue Related Resources 
- [GitHub Page Setup](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll#installing-jekyll)
 

 

 

 

 

 
