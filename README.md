# Introduction

This is an online one-page bio with information about myself, experience, downloadable résumé and portfolio. It's based on Chuckgroom's project (details below) and it's a really good tool and easy to implement!

It's made with Jekyll (Ruby) and hosted on Github Pages. Again, it's a really amazing way for people to create a personal website.

## Live Demo

To view this in action, go [here](https://rodrigoabb.github.io/bio/)

## Instructions

If you want to base your own One Page Bio on this one, you just have to:

1) Install a full Ruby development environment
2) Install Jekyll and bundler gems
```sh
    gem install jekyll bundler
```
3) Create a new Jekyll site at ./myblog
```sh
    jekyll new myblog
```
4) Change into your new directory
```sh
    cd myblog
```
5) Build the site and make it available on a local server
```sh
    bundle exec jekyll serve
```
6) Now browse to http://localhost:4000

(Check [here](https://jekyllrb.com/docs/))

For more details on Jekyll, read the [documentation](http://jekyllrb.com/).

## How to use

 - Place your photo in `/img/profile.png`
 - (Optional) Update the favicon `/img/icon.png`
 - Edit `_config.yml` to give your name, email address, social media contacts, etc. You can also update the color scheme.
 - Edit content in `/_includes/about_me.html` and `/_includes/interests.html`


## Special thanks

This is based on [One Page Bio](https://github.com/chuckgroom/onepage-bio) from Chuckgroom, so thanks to him!!
