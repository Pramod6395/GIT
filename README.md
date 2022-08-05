# GIT

- git is specific open-source version control system

#### Genarate Access Token:
- You can generate access token by going on GitHub - settings>Developer settings>Personal access token


#### Set Git Username and Password in GitBash:
By setting up this you will no need to enter manually username and token when you push/pull the repo to GitHub.

```bash
git config --global user.name "USERNAME"
git config --global user.email "EMAILID"
git config --global user.password "TOKEN"
git config --global credential.helper store

```
##### Validate the inputes:
```bash
git config --list --show-origin

```
Initialized Git
```bash
git init

```
Check Git Status
```bash
git status
git status –short
```
Add Files in stagging area:
```bash
git add <FileName>
Git add .

```
Commit the changes:
```bash
git commit -m "First Commit"

```
git add : takes a modified file in your working directory and places the modified version in a staging area. git commit takes everything from the staging area and makes a permanent snapshot of the current state of your repository that is associated with a unique identifier

Pushing files in a local repository to GitHub repository
```bash
git remote add origin https://github.com/user_name/Mytest.git
git push origin master
```
