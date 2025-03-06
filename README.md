# Formatting and Hosting a Static Site for a Resume

## Purpose

This document will instruct readers on how to format and host a resume on a website using Pelican and GitHub. This is intended for those with little knowledge in the afformentioned but who have basic computer skills.

## Prerequisites

Readers should know how to execute commands and change directories in the command line/terminal (CMD) and should have introductory Markdown skills. Readers should also be farmillair with installing applications via executables and creating accounts on websites.

## Instructions

### Installing Dependencies

Your computer will need extra software that will enable straightforward website creation. You will first need to install *Python* and then *Pelican*.

#### Python

Python is a popular programming language that is used by Pelican to create websites.  You can download an installer for the latest version from [the Python website](https://www.python.org/downloads/). 

Once you have downloaded the installer, run it, and use all the default options that may be presented to you. Depending on the version installed, you may be prompted to add Python to the PATH system environment variable. You will want Python added to PATH, so once you have allowed this Python will be ready to use on your computer. You will not need to program any Python to host a resume on a website; it is only used by Pelican to make the website for you.

#### Pelican

Pelican is a *static site generator*. It generates websites that do not change once the site is created (hence the term "static"). All the content (text, images, articles, etc.) of your website will are created from Markdown files you write. Your resume will be written in Markdown and then you can give Pelican that Markdown file to render as a page on the website.

To install Pelican, open your command prompt (being in any director is okay), and run the following command:

`python -m pip install "pelican[markdown]"`

Now, you can create a folder where you can create and keep resume website.



### Setting Up a Pelican Project

### Commiting and Pushing to a GitHub Repository

### Creating a Resume in Markdown

### Adding the Markdown Resume to Pelican

### Rendering and Launching a Pelican Website with the Resume

### Setting Up a GitHub Repository

### Adding your Pelican Project into a GitHub Repository

### Hosting the Pelican Resume Website with GitHub Pages




## Further Resources/Readings

Please consult the following tutorials and references to broaden your knowledge on the processes covered in this document:

- [Git tutorial](https://www.w3schools.com/git/)
- [Pelican Quickstart](https://getpelican.com/#quickstart)
- [Interactive Markdown Tutorial](https://www.markdowntutorial.com/)
- [GitHub Pages Quickstart](https://docs.github.com/en/pages/quickstart)

## FAQ


## Credits

Written by Elan Gabor

Thanks to Andre and Will for the peer feedback!

[Bootstrap2-dark](https://github.com/getpelican/pelican-themes/tree/master/bootstrap2-dark) theme provided by the pelican team in their themes repository.
