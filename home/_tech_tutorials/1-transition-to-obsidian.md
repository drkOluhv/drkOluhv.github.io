---
layout: article
title: Transitioning from OneNote to Obsidian
permalink: /tech_tutorials/OneNote-to-Obsidian
key: OneNote-Obsidian
---

I've now started to transisiton from OneNote to Obsidian to store all notes as plan text Markdown files. <!--more--> This was going to help me create the posts to the website easier and something that would allow me to customise my writing and organizing. Much of my snippets are also code which is easier to integrate with Markdown files. First issue was to bring accross my notes in OneNote which means converting them to plain text to open into Obsidian.

---

There are a few things you will need to convert your notebook to plain text. You will have to have you to have the Notebook locally, so export as required from your online files. There are two methods of compeleting the conversion either using Python or Powershell. I recommend the Python Version, and if you aren't familiar with using Python yet [Get Started Here.](https://github.com/drkOluhv/drkOluhv.github.io) Otherwise if you'd like to follow the PowerShell Vesion read [PageKey Tech's Post](https://pagekeytech.com/blog/misc/onenote-to-markdown/) as I only go through the Python method here.

## Python Version

1. Install [Pandoc](https://pandoc.org/installing.html)

2. Check that it's installed by running the follwing in cmd:

  ```cmd
pandoc --version
```

3. Clone the PageKey Tech's reporitory [onenote-to-markdown](https://github.com/pagekeysolutions/onenote-to-markdown)

4. Open the Folder in VS code and open convert.py

5. In terminal, run the following

```bash
  pip install -r requirements.txt
```

6. Make sure that OneNote is open

7. Run the code by pressing F5 or typing `python convert.py` into the terminal

The .md files will be converted and exported to Desktop\OneNoteExport which can be placed into you Obsidian Vault folder.

Special thanks to PageKey Tech for the great repository to make this conversion easy, feel free to checkout [PageKey Tech's Blog](https://pagekeytech.com)