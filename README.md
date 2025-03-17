## Random bash commands

**1. List files with unique first word in a directory**

```console 
$ ls $dir | awk '{print $1}' | uniq
```

**2. Daily inspirational quotes**

```console
$  fortune | cowsay -f calvin.cow | lolcat
```

---
### Git

**1. Multiple commits fix**

```console
$  git rebase -i HEAD~7
```
**2. Add current commit to prev commit**

```console
$ git commit --amend --no-edit
$ git push -f origin <branch>
```

3. See changes made

```console
$ git diff origin/<branch_name>
```