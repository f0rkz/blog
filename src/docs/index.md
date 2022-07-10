# Project Homepage

## f0rkz in cyberspace (welcome)

Welcome to Nick the Gray static pages. I hope to fill this repository out with projects and ideas as I develop my DevOps engineering skills. I also want to catalogue my personal thoughts and ideas in the form of a dynamic blog hosted within github pages with mkdocs-material as the engine behind it. After all, markdown is a second language to us all.

## Deployment

Deployment for this project is handled by GitHub Actions workflows built-in to GitHub Pages.

### Workflow

<https://github.com/f0rkz/f0rkz.github.io/actions>

### Static Page

<https://f0rkz.github.io/>

## Local Development

Development on this repository can be done using `mkdocs-material`: <https://squidfunk.github.io/mkdocs-material/>

### Create Virtual Environment

Ensure `python3` and `python3-pip` are installed:

``` bash
sudo apt update
sudo apt install -y python3 python3-pip
```

Use pip3 to install the `virtualenv` package:

``` bash
sudo pip3 install virtualenv
```

Create your virtualenv:

``` bash
virtualenv venv
```

Install mkdocs-material:

``` bash
source venv/bin/activate
pip3 install mkdocs-material
```

### serve localhost webserver

``` bash
source venv/bin/activate
cd src && mkdocs serve
```
