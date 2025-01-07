# CONTRIBUTING.md

Thanks for your interest to project ! How to contribute efficiently is explained below.

## Changes proposals

It is an open source project and proposals for changes are welcome.

Every registered user on github repository can submit changes using issues.

Issue will be delt by upstream maintainer (repository owner) with a positive or negative answer, with or without corrections.

One issue can be split into several issues.

Documentation and commented test input and output data make best quality issues.

## Localization

Documentation is written in two main languages in Markdown files : english (to be preferred) and french.

Other languages translations are welcome.

Mkdocs and mkdocs-material are used to handle language content.

## Forking and pulling requests

Forks of repository are authorized under licences conditions.

1. **Fork main repository** :
    - Click on "Fork" button top right of GitHub page.
2. **Clone it** :
    ```bash
    git clone https://github.com/votre-utilisateur/meteo-data-hub.git
    cd meteo-data-hub
    ```
3. **Create new branch** :
    - Create one branch for each new feature.
    ```bash
    git checkout -b nouvelle-fonctionnalite
    ```
4. **Code feature in right way** :
    - Add docstrings at begging of Python module and include Licence file.
	- Write test code or test data
5. **Pull your code changes** :
    - Go to "Pull Requests" (PR) menu in main repository and submit your PR.
    - Comment why you made changes and how (which files mainly).

---

## Code writing directives
- **Style** : Follow PEP 8 conventions for Python files.
- **Tests** : Add tests to check your changes before submitting your PR.
- **Documentation** : Add documentation (Markdown,..) to explain about your work.

---
