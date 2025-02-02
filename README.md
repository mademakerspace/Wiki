# reMade association wiki

The guide is available at [https://remade-association.readthedocs.io/].


This repository contains the (Markdown)[https://www.markdownguide.org/] files hosted on ReadTheDocs.
The documentation uses (MKDocs)[https://www.mkdocs.org/] to compile the Markdown files to static web pages.

## Contributing

To contribute to the wiki, first create a fork of the repository and create a new branch to work on. You can then edit the contents of the (`docs`)[./docs] folder directly in Github using the markdown wysiwyg editor, or using your favorite editor.

Then open a pull request against this repo, and after a few short minutes of building you should be able to see the results of your pull request directly on the ReadTheDocs website.
Go to your pull request, and at the bottom of the page expand the automated checks to find a link to the preview docs with the text "docs/readthedocs.org:bookbrainz-user-guide".

## Local development
If you prefer to preview your modifications in your local development environment instead, you can do so by:
1. installing python
2. runnning `pip install -r requirements.txt`
3. running `mkdocs serve`
4. you should see some output in your console pointing you to `http://127.0.0.1:8000/`

Live reload is enabled by default, so any changes you make to the docs files will be automatically reflected in your browser without requiring a page reload.


### Historical Wiki

The historical wiki is available at, for reference only:
https://github.com/mademakerspace/Wiki/wiki
