---
layout: article
title: How to Use Obsidian
permalink: /tech_tutorials/Using-Obsidian
key: Obsidian
cover: assets/images/tutorial covers/obsidian.png
tags: 
- Obsidian
- Markdown
---

## Why Use Obsidian?

Obsidian is a software for note-taking that operates in Markdown files. It uses links to help organise and visualise your notes interactively with a variety of plugins. Another great tool is the Obsidian Canvas which bypasses the limitations or traditional note-taking.

One of the main reasons people like Obsidian is because it operates in Markdown format which is portable, so your notes aren't locked into Obsidian. Markdown syntax is simple to learn and can quickly format your text as you like. The Obsidian software itself is very simple to use and is highly customisable!

## Getting Started

1. Fist download Obsidian [here](https://obsidian.md)

When opening Obsidian you have a few options:

- Create new vault
- Open folder as vault
- Open vault from Obsidian Sync

A vault is basically where all your notes will be stored. If you have Markdown files already just make sure their all placed in the same folder.

![Obsidian Start](/assets/images/obsidian/startup.png)

2. If creating a new vault type in a name and browse for a location to create it. Here we will create a new vault named "Test Vault" which will be saved in the folder "Testing Vault"

![Create Vault](/assets/images/obsidian/create-vault.png)

3. Click "Create new file" and this will start a new note.

Here we have given it a heading of **Introduction** and you can see now that that the filename of the note matches our heading.

On the right you can see the preview mode icon this is used to toggle between editing and preview mode. Currently we are looking at the note in edit mode.

On the left you can see our options to either create a new note or create a sub-folder

![Note](/assets/images/obsidian/note.png)

## Creating Links

To link notes in Obsidian their defined by two encapsulating square brackets **[[]]** Above I've typed **[[Markdown]]** and clicking on the link will create the note Markdown for me.

When typing **[[]]** Obsidian will give you options to link to existing notes and also headings within that said note. As you're editing your links, Obsidian will population options that are available in your current vault.

![Note](/assets/images/obsidian/link.png)

## Split View for Editing

To help with editing and viewing your notes we can split the tabs either right or down.

1. Right click on the tab
2. Select either split right or split down
3. Change the other tab to the preview by clicking the toggle
4. Right click on this tab and click **link with tab...** and click back to the note you were editing

This will keep both tabs connected so when you go to edit a different note you don't have to open another tab.

![Split View](/assets/images/obsidian/split-view.gif)

## Viewing your links

Obsidian has a graph view to visualise all the connections you have made in your vault. To open your graph click the icon to open the view where now you can see the two notes we have linked.

![Graph View](/assets/images/obsidian/graph.png)

## Adding Media to Notes

You can attach images, audio or PDFs to your notes in three of the following ways:

- Copy and paste
- Drag and drop
- Download attachments to your vault folder

### Change Attachment Location

By default attachments will be saved in the root of your vault folder. You can either change this in **Settings>Files & Links>Default location for new attachments**

![Attachment Location](/assets/images/obsidian/attachment-location.png)

Alternatively, you can create a folder right click on it and select **Set as attachment folder**

![Set Attachments](/assets/images/obsidian/set-attachments.png)

So now if I drag and drop an image into my notes it will save within this folder.

![Drag & Drop](/assets/images/obsidian/drag-and-drop.png)

## Embed Internal Links

To embed a file type an exclamation mark following by two enclosed square brackets **![[]]** this can be a multitude of files such as:

- Images
- Notes
- Audio
- PDFs
- Lists (Needs a block identifier **^**)

## Embed External Links

Similar to internal links Obsidian also supports external embedded links in your notes by using Markdown syntax of an exclamation mark following a square enclosed bracket, then the URL of the webpage in enclosed round brackets **![](URL)**

![External Link](/assets/images/obsidian/external-link.png)

## Adding Plugins

Obsidian has a variety of both core and community plugins to enhance your note-taking space.

**To add core plugins:**

1. Click **Settings>Core Plugins** and here you can turn on any core plugins to your liking.

**To add community plugins:**

1. Click **Settings>Community Plugins**
2. Select Turn on community plugins
3. Turn off Restricted mode
4. Click **Browse** to list the ones avaliable

Some recommended plugins to explore if they suit your functionality:

- Calendar: Creates a calendar view
- Kanban: Create Markdwon Kanban boards
- Advanced Tables: Improved functionality of markdown tables
- Obsidian Git: Backup your vault to a Git repository
- Data View: turn your vault into queryable database
- Excalidraw: deeply connect Markdown and free-hand drawings
- Templater: Template language to insert variables and functions
- Advanced Slides: Embeds your notes into slides
- Tasks: Track and query tasks

The list is endless here...

## Help with Obsidian

[Official Obsidian Documentation](https://help.obsidian.md)

## Help with Markdown Syntax

[Markdown Guide](https://www.markdownguide.org)

[Markdown Starter Worksheet](/tech_tutorials/Markdown)