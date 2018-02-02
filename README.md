# Choosing How to Connect Your Project to the Web

The goal of this short workshop is not to teach you how to use a web framework -- that's just not something you can do in an hour! Instead, we will discuss the distinctions between dynamic and static web development using two commonly used tools, Flask and Jekyll.

Do you want your webapp to retrieve data stored on a server or do you want more of the app to live inside your user's browser?

## What is Flask?

[Flask](http://flask.pocoo.org/) is a "micro-framework" built in Python that allows you to flexibly stitch together templates (in this case [Jinja2](http://jinja.pocoo.org/)), your own Python, a database, and a system of "routes".

To use the code in this repository, you can use the following commands:

- clone this repository and change directories into this new directory
- `conda env create -f environment.yml`
- `source activate learning-flask`
- *Note* to deactivate the virtual enveloper: `source deactivate`
- `python routes.py`
- you should be able to open a browser and point to `localhost://5000`

Check out how this simple app uses [SQLite3](https://sqlite.org/), sessions and authentication, cool calls to a Wikipedia API to get ideas on how all this stuff sticks together.

The sample code in this repo is based on [Lalith Polepeddi's great tutorial](https://github.com/lpolepeddi/learning-flask).

## What is Jekyll?

[Jekyll](https://jekyllrb.com/) is a static site generator written in Ruby. It is lovely (and sometimes infuriarating) tool for helping simplify the process of rendering html that isn't going to update very often.

One of the great benefits of Jekyll is that it is built into GitHub, and by virtue of this, every GitHub repository. This service is called [GitHub Pages](https://pages.github.com/). [Here's more info](https://help.github.com/articles/using-jekyll-as-a-static-site-generator-with-github-pages/) on how to set customize GitHub Pages instances from GitHub itself.

