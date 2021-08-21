---
title: Starting a New Python Project
subtitle: tools and settings to consider
---
Every time I go to start a new project, I have to try and remember all the
common tools and settings that I usually use. This page is a list of things to
think about when setting up a new project in PyCharm.

* GitHub repository options: usually a Python `.gitignore` and MIT license.
* Clone from GitHub, then install dependencies with pipenv.
* In PyCharm settings, configure Python interpreter.
* In PyCharm settings, configure Version Control: Commit, inspections.
* Install pytest with `--dev`.
* Add GitHub Actions workflow, including pytest.
* Add coverage and push results to coverage.io.
* Configure Dependabot.
* Mypy to verify type hints? Add it to GitHub Actions and PyCharm pytest.
* GitHub Pages? Add `docs` folder and configure on GitHub.
