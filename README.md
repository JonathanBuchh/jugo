# Jonathan's Hugo Theme

A simple theme inspired by [lugo](https://github.com/lukesmithxyz/lugo).

I frequently make simple websites based on [hugo](https://gohugo.io/) and found myself copying some of my old websites and deleting the bits I didn't need, so I thought I could make a baseline theme with the bare essentials.

Preview: https://buchh.fun/jugo

TODO list features
TODO add content to sample homepage

## Steps to get up and running

1. Clone this repository and delete the `.git` directory
    - TODO create bash script to clone, delete, and let you name the
2. Set the base URL in `config.toml`
3. Give your site a title and first page a description in `content/_index.md`
4. Set the title in the navigation bar and set links in `layouts/partials/nav.html`
5. Set the title in `layouts/partials/head.html`

## How to work on your site

1. [Install hugo](https://gohugo.io/getting-started/installing/)
2. Make edits and view locally: `$ make serve`
