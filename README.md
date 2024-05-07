# Python Project Template
A low dependency and really simple to start project template for Python Projects.

See also

[Flask-Project-Template](https://github.com/rochacbruno/flask-project-template/) for a full feature Flask project including database, API, admin interface, etc.
[FastAPI-Project-Template](https://github.com/rochacbruno/fastapi-project-template/) The base to start an openapi project featuring: SQLModel, Typer, FastAPI, JWT Token Auth, Interactive Shell, Management Commands.
HOW TO USE THIS TEMPLATE
DO NOT FORK this is meant to be used from Use this template feature.

Click on Use this template
Give a name to your project
(e.g. my_awesome_project recommendation is to use all lowercase and underscores separation for repo names.)
Wait until the first run of CI finishes
(Github Actions will process the template and commit to your new repo)
If you want codecov Reports and Automatic Release to PyPI
On the new repository settings->secrets add your PYPI_API_TOKEN and CODECOV_TOKEN (get the tokens on respective websites)
Read the file CONTRIBUTING.md
Then clone your new project and happy coding!
NOTE: WAIT until first CI run on github actions before cloning your new project.

What is included on this template?
🖼️ Templates for starting multiple application types:
Basic low dependency Python program (default) use this template
Flask with database, admin interface, restapi and authentication use this template. or Run make init after cloning to generate a new project based on a template.
📦 A basic setup.py file to provide installation, packaging and distribution for your project.
Template uses setuptools because it's the de-facto standard for Python packages, you can run make switch-to-poetry later if you want.
🤖 A Makefile with the most useful commands to install, test, lint, format and release your project.
📃 Documentation structure using mkdocs
💬 Auto generation of change log using gitchangelog to keep a HISTORY.md file automatically based on your commit history on every release.
🐋 A simple Containerfile to build a container image for your project.
Containerfile is a more open standard for building container images than Dockerfile, you can use buildah or docker with this file.
🧪 Testing structure using pytest
✅ Code linting using flake8
📊 Code coverage reports using codecov
🛳️ Automatic release to PyPI using twine and github actions.
🎯 Entry points to execute your program using python -m <project_name> or $ project_name with basic CLI argument parsing.
🔄 Continuous integration using Github Actions with jobs to lint, test and release your project on Linux, Mac and Windows environments.
Curious about architectural decisions on this template? read ABOUT_THIS_TEMPLATE.md
If you want to contribute to this template please open an issue or fork and send a PULL REQUEST.