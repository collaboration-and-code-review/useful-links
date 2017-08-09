# Useful Resources

GitHub
* [GitHub](https://github.com)

Getting Set Up
* [Set Up Git](https://help.github.com/articles/set-up-git)
* [Getting Started Installing Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
* [Homebrew Git Formula](http://braumeister.org/formula/git)

Git Official 
* [Git Homepage](https://git-scm.com)
* [Git Doc (Docs and Pro Git Book](https://git-scm.com/doc)
* [Git Documentation](https://git-scm.com/documentation)
* [Git Pro Git Book](https://git-scm.com/book/en/v2)

Glossaries and Cheatsheets
* [GitHub Glossary](https://help.github.com/articles/github-glossary)
* [Git Cheatsheet](https://services.github.com/on-demand/downloads/github-git-cheat-sheet.pdf)
* [GitHub Git Cheatsheet](https://help.github.com/articles/git-cheatsheet)

GitHub Help and Training
* [GitHub Help](https://help.github.com)
* [GitHub Guides](https://guides.github.com)
* [GitHub Training Guides YouTube](https://www.youtube.com/githubguides)

GitHub Try
* [Try Git](https://try.github.io)
* [GitHub Bootcamp](https://help.github.com/categories/bootcamp) 
* [GitHub Hello World Tutorial](https://guides.github.com/activities/hello-world)

GitHub Learning Resources
* [Git and GitHub Learning Resources](https://help.github.com/articles/git-and-github-learning-resources)

GitHub Open Source Guides
* [Open Source Guides](https://opensource.guide)
* [A Checklist Before You Contribute](https://opensource.guide/how-to-contribute/#a-checklist-before-you-contribute)

Collaborative Development Models and Permission Levels
* [About Collaborative Development Models](https://help.github.com/articles/about-collaborative-development-models)
* [Types of Collaborative Development Models](https://help.github.com/enterprise/2.7/user/articles/types-of-collaborative-development-models)
* [Permission Levels for an Organization](https://help.github.com/articles/permission-levels-for-an-organization)
* [Repository Permission Levels for an Organization](https://help.github.com/articles/repository-permission-levels-for-an-organization)

Documentation
* [DjangoCon US Website README.md](https://github.com/djangocon/2017.djangocon.us/blob/master/README.md)
* [DjangoCon US Website LICENSE](https://github.com/djangocon/2017.djangocon.us/blob/master/LICENSE)
* [DjangoCon US Website CODE_OF_CONDUCT.md](https://github.com/djangocon/2017.djangocon.us/blob/master/CODE_OF_CONDUCT.md)
* [DjangoCon US Website CONTRIBUTING.md](https://github.com/djangocon/2017.djangocon.us/blob/master/CONTRIBUTING.md)

Recovering a Deleted Branch
* [Can I Recover Branch After its Deletion in Git?](https://stackoverflow.com/questions/3640764/can-i-recover-branch-after-its-deletion-in-git)

## Bash Commands

Go to the home directory

```bash
$ cd
```

Change directory

```bash
$ cd <folder-name>
```

List the folders and files in a directory

```bash
$ ls
```

Move back a directory

```bash
$ cd ..
```

## Local Development

```bash
$ git clone <repo-url>
$ cd <repo-name>
$ git branch
$ git checkout -b <branch-name>
$ git add .
$ git commit -m "Your note"
$ git push origin <branch-name>
```

## Review Shared Repo Pull Request

```bash
$ git fetch origin
$ git checkout -b <local-branch-name> origin/<branch-name>
$ git merge master
```

```bash
$ git push origin <branch-name> 
```

## Review Forked Repo Pull Request

```bash
$ git checkout -b <local-branch-name> master
$ git pull https://github.com/<user-name>/<repo-name> <branch-name>
```

```bash
$ git push https://github.com/<user-name>/<repo-name> <branch-name>
```

## Merge Pull Request Locally and Push to Master Branch

```bash
$ git checkout master
$ git merge --no-ff <local-branch-name>
$ git push origin master
```
