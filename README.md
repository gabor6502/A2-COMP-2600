# Formatting and Hosting a Static Site for a Resume

## Purpose

This document will instruct readers on how to format and host a resume on a website using Pelican and GitHub. This is intended for those with little knowledge in the aforementioned but who have basic computer skills. This is intended for users with a Windows operating system.

>*Etter's Principles*: 

## Prerequisites

You should be familiar with how to execute commands and change directories in the command line/terminal (CMD) and should have introductory Markdown skills. Readers should also be familiar with installing applications via executables and creating accounts on websites. You will also need Python, Git, and GitHub (and its CLI).

#### Python

Python is a popular programming language that is used by Pelican to create websites. Get started with the following steps:

1. Download the installer for the latest Windows version of Python 3 from [the Python downloads website](https://www.python.org/downloads/).
2. Run the installer and follow this [tutorial](https://phoenixnap.com/kb/how-to-install-python-3-windows) which will walk you through the installation sequence for Windows.

You will not need to learn how to program in Python for this document's purpose. 

>*Etter's Principles*: 

#### Git

Git is a distributed version control system. This will be used to interact with a repository where we can store the website files. A repository can allow for other users to view your website's code and collaborate if desired. Follow the three steps listed on GitHub's [getting started website](https://docs.github.com/en/get-started/git-basics/set-up-git#setting-up-git). 

Note that when this article tells you to open Bash, they mean open the command line or terminal. The commands of their operating system are equivalent in yours.

>*Etter's Principles*: 

### GitHub and GitHub CLI

[GitHub](https://github.com) is a website that will allow you to create and interact with a repository that you will create for your website. You must [sign up and create an account](https://github.com/signup) with GitHub. It is recommended that you use the same email and/or username that you configured git with for your github account.

You will also need the GitHub CLI. *CLI* stands for "Command line interface", so we will interface with GitHub with this program. You can download it from the [GitHub CLI website](https://cli.github.com/). Now that you are signed up for GitHub, you can sign into GitHub through the CLI. This will make sure that when you use Git, it can access and alter your repositories stored on GitHub. Perform the sign in process by entering the following command:

`gh auth login`

>*Etter's Principles*: 

## Instructions

### Setting Up a Pelican Project

Pelican is a *static site generator*. It generates websites that do not change once the site is created (hence the term "static"). All the content (text, images, articles, etc.) of your website will are created from Markdown files you write. Your resume will be written in Markdown and then you can give Pelican that Markdown file to render as a page on the website.

Follow the instructions listed on the [Pelican Quickstart website](https://getpelican.com/#quickstart) to get started using Pelican. For this tutorial, it is necessary to select the following options when prompted during setup:

![Pelican Setup Screenshot](pelican_setup_image.png)

When you run your first Pelican website, you will notice that your command line will tell you that the website is serving (hosting) the site at `http://127.0.0.1:8000`, but the  tutorial asks you to navigate to `https://localhost:8000/` in your browser. 

![Pelican Serving Message](pelican_serving_image.png)

These web addresses are the same thing. Your computer is hosting the website (providing the website resources for a browser to view it) for you and you only, locally. Furthermore, as mentioned in the image and in your command prompt, you may type Ctrl+C to stop the hosting and regain use of your terminal.

>*Etter's Principles*: 

### Setting Up a GitHub Repository

Now that you have your Pelican project setup as a folder on your computer, it's time to set up a repository for said files. Navigate to the GitHub website and follow [this GitHub repository creation tutorial](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-new-repository#creating-a-new-repository-from-the-web-ui) to create an empty repository.

>*Etter's Principles*: 

### Adding your Pelican Project into a GitHub Repository

Open you command prompt and navigate to the directory that holds your Pelican project. Enter the following commands:

1. `git init` - this will initialize a new repository (to be sent to GitHub) within your Pelican project
2. 

>*Etter's Principles*: 

### Commiting and Pushing to a GitHub Repository

>*Etter's Principles*: 

### Creating a Resume in Markdown

>*Etter's Principles*: 

### Adding the Markdown Resume to Pelican

>*Etter's Principles*: 

### Rendering and Launching a Pelican Website with the Resume

>*Etter's Principles*: 

### Hosting the Pelican Resume Website with GitHub Pages

>*Etter's Principles*: 

## Further Resources/Readings

Please consult the following tutorials and references to broaden your knowledge on the processes covered in this document:

- [What is Git?](https://git-scm.com/book/en/v2/Getting-Started-What-is-Git%3F)
- [`git` documentation](https://git-scm.com/docs/gittutorial)
- [Interactive Markdown Tutorial](https://www.markdowntutorial.com/)
- [GitHub Pages Quickstart](https://docs.github.com/en/pages/quickstart)

>*Etter's Principles*: 

## FAQ


## Credits

README and Resume written by Elan Gabor.

Thanks to Andre and Will for the peer feedback!

[Bootstrap2-dark](https://github.com/getpelican/pelican-themes/tree/master/bootstrap2-dark) theme provided by the pelican team in their themes repository.
