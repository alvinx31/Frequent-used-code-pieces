# Hello World
The demo to show usage of Github.

**Setup the username and email**
```
git config [--global] user.name "alvinx31"
git config [--global] user.email "alvinx31[at]outlook.com"
```
After that you can check if the setting is success or not by
```
git config [--global] user.name 
```
and 
```
git config [--global] user.email
```

**Gain the push permission to the repository**
```
git remote set-url origin https://alvinx31:<password>@github.com/alvinx31/helloworld.git
```

**Two most uesful git shortcut in .bash_profile**
```
# Git add and commit altogether.
alias gcm='git commit -am'
# Pretty and concise git versions history in graph format.
alias glog='git log --oneline --graph --decorate'
```
