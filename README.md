# example-resume

An example resume built with GitHub Pages.

This is good way to manage your resume because it's:

 - **Easy to read** because the formatting is simple.
 - **Version controlled** because it's git.
 - **Easy to edit** because it's Markdown.
 - **Convertable to PDF** by printing it your browser.

See the [final product](https://auxesis.github.io/example-resume) in HTML.

Getting started
---------------

Ensure you have Ruby and Bundler installed, then:

``` bash
git clone https://github.com/auxesis/example-resume.git
cd example-resume
bundle
```

Edit `index.markdown`, then build with:

```
bundle exec jekyll serve --watch
```

Then [view the built product](http://localhost:4000/).

There are three bits to the resume
----------------------------------

 - `index.markdown` is the resume.
 - `_layouts/resume.html` is the layout.
 - `stylesheets/resume.css` in the stylesheet.

Then you make it your own
-------------------------

When you're ready to make it your own, [create a new repo](https://github.com/new), enable GitHub Pages, then push:

``` bash
git push origin master
```
