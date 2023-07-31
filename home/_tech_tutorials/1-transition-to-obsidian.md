---
layout: article
title: Transitioning from OneNote to Obsidian
permalink: /tech_tutorials/OneNote-to-Obsidian
key: OneNote-Obsidian
cover: assets/images/tutorial covers/OneNote-Obsidian.PNG
tags: 
- OneNote
- Obsidian
---

I've now started to transition from OneNote to Obsidian to store all notes as plan text Markdown files. <!--more--> This was going to help me create the posts to the website easier and something that would allow me to customise my writing and organizing.

Much of my snippets are also code which is easier to integrate with Markdown files. First issue was to bring across my notes in OneNote which means converting them to plain text to open into Obsidian.

---

There are a few things you will need to convert your notebook to plain text. You will have to have the Notebook stored locally, so export as required from your online files. 

There are two methods of completing the conversion either using Python or Powershell. I recommend the Python Version, and if you aren't familiar with using Python yet [Get Started Here.](/programming/python).

Otherwise if you'd like to follow the PowerShell Version read [PageKey Tech's Post](https://pagekeytech.com/blog/misc/onenote-to-markdown/) as I only go through the Python method here.

## Python Version

1. Install [Pandoc](https://pandoc.org/installing.html)

2. Check that it's installed by running the following in command prompt:

```text
pandoc --version
```

3. Clone the PageKey Tech's repository [onenote-to-markdown](https://github.com/pagekeysolutions/onenote-to-markdown)

![CloneOneNote](/assets/images/clone-snippet.png)

4. Clone the repository in GitHub Desktop somewhere locally and open **convert.py** in visual studio code

![CloneLocal](/assets/images/clone-repo.png)


5. In the terminal, run the following

```bash
  pip install -r requirements.txt
```
![installRequirements](/assets/images/install-req.png)

6. Make sure that OneNote is open on your computer

7. Run the code by pressing F5 or typing `python convert.py` into the terminal

The .md files will be converted and exported to Desktop\OneNoteExport which can be placed into you Obsidian Vault folder.

Special thanks to PageKey Tech for the great repository to make this conversion easy, feel free to checkout [PageKey Tech's Blog](https://pagekeytech.com)


## Learn How to Use Obsidian

[Tech Tutorial Guide - How To Use Obsidian](/tech_tutorials/using-obsidian)