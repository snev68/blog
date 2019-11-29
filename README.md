# blog

This repository contains the source for the [Nu Blog](http://blog.nushell.sh/). The website is hosted on GitHub Pages and uses the static site generator [jekyll](https://jekyllrb.com/).

## Posts

Information needed for a post in the Front Matter:

* **title**: title of the post
* **author**: Name of the author or it will be set by default to `nushell`
* **author_site**: Website of the author or it will be set by default to the nushell GitHub-page
* **author_image**: link to a image in `https://www.nushell.sh/blog/images/*.png` or it will be set to `default.png`

# Test it locally

## Install jekyll

You need to install `jekyll` and `bundler`. There is a detailed description on how to get them for different operating systems on the [jekyll website](https://jekyllrb.com/docs/installation/).

## Build

The easiest way to build the site is to run

```shell
> bundle exec jekyll  serve
```

in your local folder of the repo. This will run a local web server and you can view the website at [http://localhost:4000](http://localhost:4000).

The website will also be automatically recompiled every time you make changes.


# License

The website is made available under MIT license. The [original theme](https://github.com/pages-themes/midnight) is released under CC0.
