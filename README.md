# Formatting and Hosting a Static Site for a Resume

## Purpose

This document will instruct readers on how to format and host a resume on a website using Pelican and GitHub. This is intended for those with little knowledge in the aforementioned but who have basic computer skills. This is intended for users with a Windows operating system.

>*Etter's Principles*: Identified audience and technical level.

## Prerequisites

You should be familiar with how to execute commands and change directories in the command line/terminal (CMD) and should have introductory Markdown skills. Readers should also be familiar with installing applications via executables and creating accounts on websites. You will also need Python, Git, and GitHub (and its CLI).

#### Python

Python is a popular programming language that is used by Pelican to create websites. Get started with the following steps:

1. Download the installer for the latest Windows version of Python 3 from [the Python downloads website](https://www.python.org/downloads/).
2. Run the installer and follow this [tutorial](https://phoenixnap.com/kb/how-to-install-python-3-windows) which will walk you through the installation sequence for Windows.

You will not need to learn how to program in Python for this document's purpose. 

#### Git

Git is a distributed version control system. This will be used to interact with a repository where we can store the website files. A repository can allow for other users to view your website's code and collaborate if desired. Follow the three steps listed on GitHub's [getting started website](https://docs.github.com/en/get-started/git-basics/set-up-git#setting-up-git). 

Note that when this article tells you to open Bash, they mean open the command line or terminal. The commands of their operating system are equivalent in yours.

### GitHub and GitHub CLI

[GitHub](https://github.com) is a website that will allow you to create and interact with a repository that you will create for your website. You must [sign up and create an account](https://github.com/signup) with GitHub. It is recommended that you use the same email and/or username that you configured git with for your github account.

You will also need the GitHub CLI. *CLI* stands for "Command line interface", so we will interface with GitHub with this program. You can download it from the [GitHub CLI website](https://cli.github.com/). Now that you are signed up for GitHub, you can sign into GitHub through the CLI. This will make sure that when you use Git, it can access and alter your repositories stored on GitHub. Perform the sign in process by entering the following command:

`gh auth login`

>*Etter's Principles*: Single sourcing with links and use of subheadings to encourage scannablility and readablility. Promoting Git and GitHub also encourages distributed version control and all the benefits that come from it.

## Instructions

### Setting Up a Pelican Project

Pelican is a *static site generator*. It generates websites that do not change once the site is created (hence the term "static"). All the content (text, images, articles, etc.) of your website will are created from Markdown files you write. Your resume will be written in Markdown and then you can give Pelican that Markdown file to render as a page on the website.

Follow the instructions listed on the [Pelican Quickstart website](https://getpelican.com/#quickstart) to get started using Pelican. For this tutorial, it is necessary to select the following options when prompted during setup:

![Pelican Setup Screenshot](pelican_setup_image.png)

When you run your first Pelican website, you will notice that your command line will tell you that the website is serving (hosting) the site at `http://127.0.0.1:8000`, but the  tutorial asks you to navigate to `https://localhost:8000/` in your browser. 

![Pelican Serving Message](pelican_serving_image.png)

These web addresses are the same thing. Your computer is hosting the website (providing the website resources for a browser to view it) for you and you only, locally. Furthermore, as mentioned in the image and in your command prompt, you may type Ctrl+C to stop the hosting and regain use of your terminal.

>*Etter's Principles*: Images used to enhance content, understanding, and navigation.

### Setting Up a GitHub Repository and Adding Content

Now that you have your Pelican project setup as a folder on your computer, it's time to set up a repository for said files. Navigate to the GitHub website and follow [this GitHub repository creation tutorial](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-new-repository#creating-a-new-repository-from-the-web-ui) to create an empty repository.

Open you command prompt and navigate to the directory that holds your Pelican project. Follow [the tutorial here](https://www.datacamp.com/tutorial/git-push-pull) to add your Pelican website to the git repository.

### Creating and Hosting your Resume Website

Create or adapt your current resume into Markdown, taking advantage of its organizational features (headers, lists, etc.) and applying the Pelican specific, `Author`, `Date`, and `Category` attributes at the top of this file. Put this Markdown file in the `content` folder of your Pelican project, and use the command line to preview your website.

### Hosting the Pelican Resume Website with GitHub Pages

Follow the [tutorial here](https://antonellocalamea.medium.com/step-by-step-guide-to-setup-a-web-site-using-pelican-and-gitpages-5de976ae44cb) to host your website on GitHub pages.

>*Etter's Principles*: By now the user has a website to allowed easy access for anyone to view the information they provide, collaborate if needed, and update said info when ready. Single sourcing used again.

## Further Resources/Readings

Please consult the following tutorials and references to broaden your knowledge on the processes covered in this document:

- [What is Git?](https://git-scm.com/book/en/v2/Getting-Started-What-is-Git%3F)
- [`git` documentation](https://git-scm.com/docs/gittutorial)
- [Interactive Markdown Tutorial](https://www.markdowntutorial.com/)
- [GitHub Pages Quickstart](https://docs.github.com/en/pages/quickstart)

>*Etter's Principles*: Relevant further readings to increase reader's knowledge on the topics discussed.

## FAQ

Q: Why is Markdown better than writing raw HTML?
A: Markdown is great for organizing text into readable content, whereas HTML has more functionality than just that, so we don't need all the features that HTML provides, which makes rendering webpages with Markdown faster and easier. Furthermore Markdown has shorter/concise syntax where as HTML tags can clutter a document.

Q: I changed the Markdown version of my resume, so why don’t I see the changes when I refresh the website in my browser?
A: If you are waiting for the website hosted by the forge to change, then this is because you must commit and push your changes to the repository so the website the browser is looking at actually changes. If you don't see the changes from a Pelican preview, it may be because of cached data on browser, and hitting Ctrl+F5 will refresh the page with the changes. Also make sure that when you are expecting the changes, the Pelican preview is indeed live. 

## Credits

README and Resume written by Elan Gabor.

Thanks to Andre and Will for the peer feedback!

[Bootstrap2-dark](https://github.com/getpelican/pelican-themes/tree/master/bootstrap2-dark) theme provided by the pelican team in their themes repository.
