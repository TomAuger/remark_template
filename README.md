Class Notes
============

Notes slides for XXX

## Usage

To view these slides, download the repository and then run on a local web server, or configure Google Chrome to allow local file cross-origin access.

### With node.js

1. If you haven't already installed `http-server`, then `npm install http-server -g` (don't forget -g global flag)
2. Navigate to local folder
3. `http-server -o` Opens that folder in browser and looks for `index.html`.

### With Python (esp Mac)

1. Instructions to follow.

### Simplified usage

Alternatively, just navigate to the individual day's `.md` file (eg: [Day 3](https://github.com/TomAuger/gmd304-notes/blob/master/day3/day3.md)) in GitHub and enjoy the GitHub Markdown version of the slide deck.

## Build details

This slide deck was built entirely in HTML + SCSS + Markdown using [Remark.js](http://remarkjs.com/).

---

# Cloning and Building

These instructions apply to creating new notes using this template as a starting point.

1. Create a new local folder
2. Open a git shell in that folder
3. `git init`
4. `git remote add -f origin https://github.com/TomAuger/remark_template.git`

## Sparse Checkout

If you want to grab everything (including this README.md file and the HTML template file), then just `git pull origin master`.

Otherwise, you want a __sparse checkout__ of just the `_remark` folder

1. `git config core.sparseCheckout true`
2. `echo "_remark" >> .git/info/sparse-checkout`
3. `git pull origin master`