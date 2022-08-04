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
Validate the inputes:
```bash
git config --list --show-origin

```


