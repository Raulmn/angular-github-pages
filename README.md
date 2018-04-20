# GithubPages

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.6.5.

## Download app and config repository

Run `git clone https://<repository-url>` in prefer folder to download project.
Run `git remote set-url origin https://raulmn:pass@github.com/Raulmn/angular-github-pages.git` in prefer folder to download project.


## Change branch

On github web go to Source and click in branch, insert name of branch and click in create branch.
And then run `git checkout <name-of-branch>`


## Create app

Run `ng new appName --routing --skip-git --directory ./`
- Creating app in root directory.
- Creating routes.
- Creating whitout `git init`


## App Server

Run `ng serve -o` to up server of aplication.


## Instal angular-cli-ghpages

Run `npm install -g angular-cli-ghpages`


## Compiler app and Deploy in Github Pages

Run `ng build --base-href https://Raulmn.github.io/<name-repository>/`
Run ` ngh --name="Raulmn" --email=raul11930@gmail.com --no-silent --branch=gh-pages`
Go to url https://Raulmn.github.io/<name-repository> in browser.
