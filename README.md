#Hosting a Resume Online

## Purpose 
Have you ever wanted to take your resume to the next level? Andrew Etter describes a simple process to put your resume online in his book *Modern Technical Writing*. This readme will provide a detailed explanation on how to do just that, while making reference to related concepts in Etter's book.

![Final Product](https://media.giphy.com/media/XIrTo38GTZjMNAKCe5/giphy.gif)

### Prerequisites
**Github Account:** Before anything else, you will need to start a Github account, which can be done [here](https://github.com/).

**Git:** This guide will be shown using command line git commands. (If you are using a Windows machine and have never done this, it can be accomplished by downloading git [here](https://git-scm.com/downloads)).

**Markdown:** Andrew Etter highly recommends using a lightwight markup language to format your resume. Markdown is by far the most popular language and will be used in this guide. In case you are unfamiliar with using Markdown, [here](https://www.markdowntutorial.com/) is a simple tutorial to get you familiar with the in-line formatting process.

### Instructions
1. Make sure you have completed all pre-requisites, that is, you:
	* Have a Github account
	* Downloaded git and have your command-line git open.
	* Formatted your existing resume into Markdown.

2. Name your resume file to "**index.md**":
	* Github Pages requires this to be the name. Once your repository is being hosted, it will look for an "index" file to display.

3. Create a respository in Github, **exactly matching your Github username**:
	* For example, my username is EvanMarshallj. Therefore, my respository is named **EvanMarshallj.github.io**.
	* The repository and username must match, this is how Github knows which respository to host on pages, since you are only allowed one domain per Github account.

4. Clone your repository using the command:
	> git clone https://github.com/username/username.github.io
	* This makes a copy of your newly made repository on your machine.
	* The repository will now be seen as a folder in "File Explorer".

5. Place your "**index.md**" file into your newly made "**Usename.github.io**" folder.
	* Now your copy of the repository contains your resume file.

github pages IS made using jekyll

talk about how using a static site generator (Jekyll) is an amazing tool.

related to andrew etters book because he recommends using a distributed collaboration software

step: talk about jekyll themes

##### *Why is Markdown better than a word processor?* 
Markdown is versatile and will look great everywhere. Have you ever tried to copy paste your Microsoft Word resume into a textbox, or other text editor? Word processors do not translate very well to anything but their own suite. This makes distributing your resume a nightmare when potential employers request different document types. However, Markdown keeps your formatting in-line, allowing it to be easily translated to other formats.

##### *Why is my resume not showing up?*
There are many reasons that could cause your website to not show up, all stemming from not following the above instructions precisely. During my first attempt, I had forgotten to name the markdown resume in my repository "**index.md"**. Another common issue could be that your repository is named incorrectly (it must exaxctly match your github account name).
