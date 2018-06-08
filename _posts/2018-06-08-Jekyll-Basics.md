---
layout: post
title: Getting started with Jekyll
---

# Jekyll

* Jekyll is a ruby jem developed on Ruby.
* It turns your markdown files in to html.
* You can create websites and blogs using GitHub pages with Jekyll.
* Jekyll treats all files or folders starting with `_` differently.

## Creating a blog using Jekyll

* Create a sample repository with a default README.md
* Create a `_config.yml` file. Below is the sample config file
* For more information about the minima theme we are using to [https://github.com/jekyll/minima](https://github.com/jekyll/minima)
* Create a new file `about.md` in the repository

### _config.yml file

```yml
# Sampel comment
title: Sample title
author: Teja
email: sample@example.org
description: Sample site
twitter_username: teja463
github_username: teja463

# Build settings
markdown: kramdown
theme: minima
```

### about.md file

* That first lines in side three dashes `---` are called Yaml front matter. Then you can start writing markdown

```yfm
---
layout: page
title: About
---

This is about page about this site

Markdown:
- Hello
- Sampel
```

## Creating posts

* Create a directory with name `_posts`
* Post file names must start with a Date. Dont have any spaces in your file name.
* Create a file with naming conventions `YYYY-MM-DD-postname.md` e.g. `2018-06-08-post1.md`.
* Crete an Yaml front matter and create the content. If you dont give a title by default it will take the file name.

```
---
layout: post
title: Sample Post
---

This is a sample post

```
