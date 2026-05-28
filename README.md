# TheTylerN Blog README

## Overview

TheTylerN is a blog that currently has one "Publication" (group of articles),
[Tyler N’s Snippets of Experiences, Knowledge, and Code](https://tyleruploads.github.io/thetylern/snippets/).
The purpose of this publication is to share articles about my experiences, articles that explain things, and articles that explain my code.

The main site is accessable at [this link](https://tyleruploads.github.io/thetylern/),
and the main publication, Tyler N’s Snippets of Experiences, Knowledge, and Code, is accessable [here](https://tyleruploads.github.io/thetylern/snippets/).


## What Powers my Blog

My blog is powered [Hugo](https://gohugo.io/), a static site generator written in Go.
My blog uses the [PaperMod Theme](https://github.com/adityatelange/hugo-PaperMod/), which is fast, clean, and responsive.
If you like how my Hugo site looks and you want to make one yourself, I highly recommend using the [PaperMod Theme](https://github.com/adityatelange/hugo-PaperMod/).
The code in this repository is the code for my Hugo site, which includes Markdown files of all of my articles.

My Hugo site uses [GitHub Actions](https://github.com/features/actions) to compile my site and host it to [GitHub Pages](https://docs.github.com/en/pages).

Also, I recently created the profile picture for my GitHub and platforms I plan to also put my articles on using [Inkscape](https://inkscape.org/about/).

---

## How to locally host my blog

While you can definately read my blog on my [GitHub Pages site](https://tyleruploads.github.io/thetylern/),
you can also host it locally if you are intrested!

Before hosting my blog, make sure you have [Hugo](https://gohugo.io/installation/) installed.

### Cloning the repository
Navigate to where you want my blog to live on your computer in your terminal, and run the following command to clone the repository:

```bash
git clone --recursive https://github.com/tyleruploads/thetylern.git
```

Then, nagivate into the repository

```bash
cd thetylern
```

### Running the server
To run the server, run:

```bash
hugo server
```

(Add the `-d` flag if you want to see articles of mine that are still drafts!)


---
## Links

* My GitHub profile: [https://github.com/tyleruploads](https://github.com/tyleruploads)
* This GitHub repository: [thetylern](https://github.com/tyleruploads)
* My dev.to account: [thetylern](https://dev.to/thetylern)
* My personal contact form: [Tyler N Contact Google Form](https://forms.gle/iNfeJ66Ws3XUmeDaA)

## LICENSE

This repository contains a mix of different types of content. Different licenses exist for different types of content as defined below.

### 1. Code & Configuration
All programmatic code, automation scripts, theme overrides, and configuration files
(including `hugo.yaml` and files inside the `layouts/` directory) are licensed under the MIT license.

> **MIT License**
>
> Copyright 2026 Tyler N
>
> Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:
>
> The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.
>
> THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.


### 2. Articles, Written Content, Media, & Assets

All written articles (including but not limited to written pieces categorized under 'publications'),
essays, original media, and custom graphics found within this repository are licensed under the 
Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0) license.
Any embedded third-party media or stock imagery remains under the native license of the respective creator or platform.

To view a copy of the license, please visit: [Creative Commons CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)

#### Summary of CC BY-NC-SA 4.0 license:

*   **Attribution** — You must give appropriate credit, provide a link to the license, and indicate if changes were made. You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.
*   **NonCommercial** — You may not use the material for commercial purposes.
*   **ShareAlike** — If you remix, transform, or build upon the material, you must distribute your contributions under the same license as the original.
*   **No additional restrictions** — You may not apply legal terms or technological measures that legally restrict others from doing anything the license permits.
