# Gitfool

Gitfool (or Gitfull) is a shell command for you to fulfill your git commit log.

This is the easiest way to make you a [Rockstar](https://github.com/avinassh/rockstar) Programmer ! 😅

**Update**

For your convenience, you can be gitfooled just exceute this command in you repository directory:

```bash
curl -s https://raw.githubusercontent.com/Jaggle/Gitfool/master/gitfool| sh -s `pwd` 365 --push
```

> Gitfool is a trick, take care of what you are doing.

![](gitfool.png)

## USAGE

```bash
./gitfool [repo_path] [days] --push
```

**repo_path**

the repository path you want to add commits

**days**

the past days you wish to add these commits, for example : 365 means the past one year.

**--push**

with this option, Gitfool will push the commits to remote (execute `git push`)

> don't use `sh gitfool` syntax, and it will report an error.

## EXAMPLE

```bash
./gitfool ~/Code/acme 365 --push
```

## WARNING

you may be reported for abusing if you push these commits to Github.
