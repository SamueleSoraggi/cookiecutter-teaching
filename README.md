## Cookiecutter template for online teaching material in health data science

This repository contains a basic structure to organize a course or research training in health data science. The template is downloaded through the ` python` package `cookiecutter` simply with the command

`https://github.com/hdsSandbox/cookiecutter-teaching.git `

This require the installation of the [package cookiecutter](https://cookiecutter.readthedocs.io/). Once you run the command, you are presented with a few questions, such as course name and author. Once those are inserted, you will get a folder structure that contains the following subfolders:

*  Assignments
* Data
* develop
* Environments
* Notebooks
* Notes
* Script
* Slides

Here you can organize your course material and package requirements to run the course material correctly. It is of course possible to add, remove and modify subfolders as needed.

## Course webpage and documentation

The folder ` develop` is dedicated to the course web/documentation page. This is realized through the package `mkdocs` and is written in the easy-to-use [Markdown language](https://commonmark.org/help/). Example pages are organized into the folder `develop` and the website structure is exemplified in the configuration file `mkdocs.yml` . 

The package needed to install are `mkdocs`, `mkdocs-material`, and `mkdocs-material-extensions` . This can be easily done through the `conda` package manager with

```shell
conda install -c conda-forge mkdocs
conda install -c conda-forge mkdocs-material
conda install -c conda-forge mkdocs-material-extensions
```

or with `pip` through

```shell
pip install mkdocs
pip install mkdocs-material
pip install mkdocs-material-extensions
```

### Compile the webpage

Open as text the file `mkdocs.yml`. Here you will see various settings, which are mostly ready-to-use. You will need eventually to change the following:

*  `site_name:` Here the name of the webpage is given by default following your course name given to `cookiecutter`, but you can write something else.
* `nav:` this setting lists the `markdown` documents you want to use as webpages, and which name they have when they appear on the webpage menu.
* `theme:` this option contains the possibility of choosing a picture as logo for your webpage with the option `logo:`. Here there is one by default that you can change.

To test your webpage, start the terminal on your computer, and from the course folder use the command

`mkdocs serve`.

You will get a link to visualize the webpage on your browser. Use the command `mkdocs build` to compile your webpage. A new folder called `docs` will appear into your cookiecutter folder. This contains the webpages in `html` format. If you put your course material on a `github` repository, the course material can be visualized as webpage. To do this, go into the repository and in the menu `settings ---> pages`, and choose those settings:

![](/home/samuele/cookiecutter-teaching/screenshot.png) 

Then press save. In short time you will be able to see the webpage at the address course_name.github.io. If you have a free `github` account, then this can be done **only** if your repository is **public**.

