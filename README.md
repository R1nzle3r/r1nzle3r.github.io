[![CI](https://img.shields.io/badge/Github%20Pages-passing-gold.svg?logo=github)](ci)
[![License: MIT](https://img.shields.io/badge/License-MIT-orange.svg)](https://opensource.org/licenses/MIT)
[![Jekyll](https://img.shields.io/badge/jekyll-%3E%3D%204.3.2-green.svg)](https://jekyllrb.com/)
[![Jekyll](https://img.shields.io/badge/gem%20version-3.2.33-blue.svg)](gem)

# Satellite🛰️ - Jekyll blog theme
An emotional and adorable blog theme powered by ***Jekyll***. Live demo is available here: [https://byanko55.github.io](https://byanko55.github.io)

![Demo Page](https://i.ibb.co/h1QF06V/demo.webp)

### Light Mode
![Demo Page-light](https://i.ibb.co/PtTbM1V/image-4.webp)

### Dark Mode
![Demo Page-dark](https://i.ibb.co/cY6hwG4/image-5.webp)

### Fresh and Attractive Design
<p>
<img src="https://i.ibb.co/4NwrTyj/image-2.webp" height="400px" align="center"/>
<img src="https://i.ibb.co/WvyBzkL/Animation.gif" height="400px" align="center"/>
</p>

## Features

* Comment System using *giscus*
* Copy contents of Code Block
* Dark/Light Theme
* Google Analytics
* Hierarchical Categorization
* Mobile friendly design
* Related Posts
* RSS/Sitemap support
* Search Post by Title or Tags
* Syntax Highlighter (*highlight.js*)
* Table of Contents
* Visitor Counter (*goatcounter*)

## Installation

There are two way to setup this theme:

### Method 1: Build from source (Recommended)
Fork this repository or download the [source](https://github.com/byanko55/jekyll-theme-satellite/releases) as a zip. 

If you use as destination a repository named USERNAME.github.io then your url will be https://USERNAME.github.io/.


### Method 2: Utilize Gem package
Create a clean site directory (Follow the **Instruction 1~4** described in [here](https://jekyllrb.com/docs/)).

The following materials are redundant, so remove them.
* index.markdown
* about.markdown
* 404.html

Then, add this line to your Jekyll site's `Gemfile`:

```
gem "jekyll-theme-satellite"
```

You need to replace the initial `_config.yml` file with the [prepared one](https://github.com/byanko55/jekyll-theme-satellite/docs/_config.yml).

### Modify your site setting

Now fill in the **site variable** such as blog name, profile image, and social accounts in `_config.yml`.

```
title: Example.com
description: "Satellite - jekyll blog theme"
logo_img: "/assets/img/favicon.webp"
profile_img: "/assets/img/profile.jpg"

# Social Links
email: example@gmail.com
github_username: github
twitter_username: twitter
instagram_username: instagram
linkedin_username: linkedin
facebook_username: facebook
```

### Run site locally

From the site root directory, install the dependencies:

```
bundle install
```

Start a Jekyll service.

```
bundle exec jekyll serve
```

Now open [http://localhost:4000](http://localhost:4000) in your browser.

## Customizing

You can find useful manuals for customizing your site from the below table:

|||
|---|---|
|Posting guidelines|[link](https://github.com/byanko55/jekyll-theme-satellite/docs/Posting%20guide.md)|
|Enabling ***comment system***|[link](https://github.com/byanko55/jekyll-theme-satellite/docs/Comment%20system.md)|
|Enabling ***Visitor counter***|[link](https://github.com/byanko55/jekyll-theme-satellite/docs/Visitor%20counter.md)|

## Contribution
If you would like to report a bug, or request a new feature, please open [an issue](https://github.com/byanko55/jekyll-theme-satellite/docs/Contribution%20Guidelines.md) We are open to any kind of feedback or collaboration.

## License
© 2024 *Yankos*. This theme is available as open source under the terms of the [MIT License](https://opensource.org/license/mit/).