## Intro

This is an online one-page bio with information about myself, experience, downloadable résumé and portfolio. Was based on Chuckgroom's one and it's a really good tool and easy to use for people who wants to create a personal website.

## Demo

To view this in action, go [here](https://rodrigoabb.github.io/bio/)

## Instructions

If you want to base your own One Page Bio on this one, you just have to:

- Install a full Ruby development environment
- Install Jekyll and bundler gems
```sh
$ gem install jekyll bundler
```
- Create a new Jekyll site at ./myblog
```sh
$ jekyll new myblog
```
- Change into your new directory
```sh
cd myblog
```
- Build the site and make it available on a local server
```sh
bundle exec jekyll serve
```
- Now browse to http://localhost:4000

(Check [here](https://jekyllrb.com/docs/))

For more details on Jekyll, read the [documentation](http://jekyllrb.com/).

## How to use

 - Place your photo in `/img/profile.png`
 - (Optional) Update the favicon `/img/icon.png`
 - Edit `_config.yml` to give your name, email address, social media contacts, etc. You can also update the color scheme.
 - Edit content in `/_includes/about_me.html` and `/_includes/interests.html`


## Special thanks

This is based on [One Page Bio](https://github.com/chuckgroom/onepage-bio) from Chuckgroom, so thanks to him!!
