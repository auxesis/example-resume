# example-resume

An example resume, built with GitHub Pages.

Managing your resume with git, Markdown, and [GitHub Pages](https://pages.github.com/) is good because it's:

 - **Easy to read** because the formatting is simple.
 - **Version controlled** because it's git.
 - **Easy to edit** because it's Markdown.
 - **Convertable to PDF** by printing it your browser.

The [final product](https://auxesis.github.io/example-resume) is HTML.

Get started with Jekyll locally
-------------------------------

Ensure you have git, Ruby, and Bundler installed, then:

``` bash
git clone https://github.com/auxesis/example-resume.git
cd example-resume
bundle
```

Edit `index.markdown`, then build with:

```
bundle exec jekyll serve --watch
```

Then [view the resume](http://localhost:4000/) locally.

There are three parts to the resume
-----------------------------------

 1. `index.markdown` is the resume.
 2. `_layouts/resume.html` is the layout.
 3. `stylesheets/resume.css` in the stylesheet.

Unless you want to change the presentation significantly, just edit the resume in `index.markdown`.

Then you make it your own
-------------------------

When you're ready to make the resume your own, [create a new repo](https://github.com/new), enable [GitHub Pages](https://help.github.com/articles/configuring-a-publishing-source-for-github-pages/) (just use `master` as it's the simplest), then push:

``` bash
git push origin master
```
