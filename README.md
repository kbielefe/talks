# Talks

This is the source code for https://kbielefe.github.io/talks, a [Jekyll](https://jekyllrb.com) and [Reveal.js](https://revealjs.com) site to hold the
slides and other content for various talks I have given.

## To install or upgrade build dependencies:

Set up rbenv using [these instructions](https://github.com/rbenv/rbenv#installation).

```
bundle update
npm install
```

## To run a server on [localhost:4000/talks/](http://localhost:4000/talks/) for development:

```
bundle exec jekyll serve
```

Add `--future` to see post-dated stories.

## To build the site for publishing to GitHub pages or elsewhere:

```
bundle exec jekyll build
```

## To create a new talk:

Copy a file in the _posts directory. Create a 280x200 image with 5px inner
boundaries in the assets/header-images directory and set the optimized_image
front matter to its url. Use the 'slides' category for reveal.js slides.
