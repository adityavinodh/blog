---
title: "How to Create a Blog or Website using Hugo"
date: 2021-05-06T15:20:51+05:30
draft: false
tags: ["tutorial", "hugo", "programming", "guide", "get started", "website", "blog"]
---

# What is Hugo?

![Hugo Logo!](/hugo-logo-wide.svg)

Hugo is a static-site generator that helps you generate and build static files like HTML, CSS, and JavaScript ahead of time. It is an opensource project built with Go and boasts impressive build times that seems incomparable.

# What does it do?

It helps you convert markdown files (the files you will be writing your articles or blog posts in) to the static files that will be served later. 

# How is it different?

This is different to traditional methods like a wordpress site, that has a dedicated database and a web server that needs to respond to requests, communicate with the Databse, and serve the files on every request. It is much more slower than using a static-site generator like Hugo as nothing is dynamic; we know that the content is not going to change. HTTP web servers are extremely good and fast at just serving static content. Users ask for a file, and the server just has to give it. There is no other processing involved.

# The Benefits

Your website can be deployed and hosted anywhere (On GCP cloud storage, AWS S3, Netlfify, Firebase, etc.), and can be deployed to a CDN (Content Delivery Network) so that it can be cached on a global edge network and significantly improve the performance and speed of page loads. This is especially important with poor internet connections, and for SEO (Search Engine Optimization).

# Caveats

However, that does not mean Hugo can not be used for anything dynamic. If your use case if very complex such as involving user input, you might not be able to use Hugo. Using a regular website, or single-page-application with React, Angular, Vue, or Svelte might be a better option. But if all you need is a simple blog, with a few extra features, like an option for users to provide comments, Hugo has everything you need.

# Get Started

The [Hugo Documentation](https://gohugo.io/documentation/) is very helpful and elaborate. It is the first place to check in case of references or issues.

## Installation

Hugo is available in all platforms (Windows, MacOS, and Linux), as a binary that you can install, or via a package manager. If you have a compatible package manager, that is the recommended way as it is the easiest and has the least amount of work to maintain

### Install using the Binaries

Availabe from their GitHub [Releases](https://github.com/gohugoio/hugo/releases) page. (Choose the appropriate platform and type of file). Make sure to install it in a location that is somewhere in your `PATH`. `usr/local/bin` is the best place for Linux. Otherwise, append the location to your `PATH` variable.

### Install using a Package Manager

**On Windows**

	choco install hugo -confirm

or

	scoop install hugo

---

**On Linux and MacOS** (Using Homebrew)

	brew install hugo

---

To verify that the installation occurred successfully, run the following command.

	hugo version

There should not be any errors.


## Creating the Site

Change directories into the location you want to create your project. Then run the following command with your project's name. This will create folder that contains all the files that you need to get started.

	# Creates a new site and project called 'firstblog'
	hugo new site firstblog

Change directories into the project directory that was created.

	cd firstblog

You will notice a similar folder structure. The `config.toml` file is where all the variables and settings for your projects live. You will be able to setup and configure most of your website from that one file.

	.
	├── archetypes
	├── config.toml
	├── content
	├── data
	├── layouts
	├── static
	└── themes

If you want to change the file type for your configurations, you can change it to YAML or JSON depending on your preference. You can copy and paste the contents of the file using a tool like [ConvertSimple](https://www.convertsimple.com/convert-toml-to-yaml/) to convert the format and syntax.

All of the actual content that you write as markdown files lives inside the `content` directory. You can organize the content in folders, and subfolders, and Hugo will automatically take care of organizing the posts as categories or subcategories.

Use the following command to create a blank markdown file. You can specify where you want to store this file. If the file name alone is provided, then it is directly placed in the `content` directory.

	hugo create first-post.md

or try the following to place it in `content/posts`:

	hugo create posts/first-post.md

---

### Front Matter

Every markdown file that is created and used for your website has a section on the top that is unique to Hugo. It starts and ends with `---`. The syntax used in this is `TOML` by default. You can change this default setting with the following command:

	# To convert to YML
	hugo convert toYAML

In the front matter, you can set options for the specific page, meta data, and other configuration that is specific to this particular page. Check out the documentation of [Front Matter](https://gohugo.io/content-management/front-matter/) to learn the different options available.

### Install a Theme

One of the powers of Hugo is to utilize one of the many themes created by the community. Check out the [Complete List](https://themes.gohugo.io/) and choose one of the themes. Read the documentation and install the theme. This process is very straightforward. Mostly, you will have to download the code, either manually, or using Git, and place it in the `themes` folder, then inside another folder with the name of the theme you chose.

Then make sure to go to the `config` file and update the theme variable with the name of the theme you have chosen.

### Running the Site

Hugo has an in-built web server that helps you view the site locally, and automatically watches your files for changes, and re-runs when the changes occur.

	hugo server -D

## Deployment

With the following command, Hugo builds your site and outputs the final static content to the `public` directory by default. That can be modified in the `config` file if needed. The contents of this file needs to be deployed with whatever hosting provider you chose to use.

	hugo -D

# Bonus content

## Hosting

Hugo is very feature-rich, and is an amazing product if used wisely. You could set up a CI/CD Pipeline to run every time you make changes and deploy to your hosting provider of choice.

I have setup this blog using GitHub Actions and Firebase. Every time code is merged, a commit is made to the main branch, or a Pull Request is merged, a Firebase workflow runs on GitHub in the cloud that deploys the content of the `public` directory to Firebase Hosting.

## Comments

You can add a comments or discussion section to all of your pages (or select ones) easily using [Disqus](https://disqus.com/). Instructions and setup is very straightforward and simple.

---

That's all for this post and tutorial. I hoped this has helped you and given you an idea of how things work. You can read all my posts on Medium and Dev also.

