# LinuxCheatsheet
Commands I frequently use but forget and have to google


##### Push ssh-key to server
```
ssh-copy-id -i ~/.ssh/mykey user@host
```
##### After reinstallation of ssh on server
```
ssh-keygen -R [server ip]
ssh-keygen -R [server dns]
```

Markdown link, for editing this page.
https://help.github.com/en/articles/basic-writing-and-formatting-syntax

#### GIT create new repo on linux server to sync to
```
git init --bare ~/projectname.git
```
https://linuxize.com/post/how-to-setup-a-git-server/
