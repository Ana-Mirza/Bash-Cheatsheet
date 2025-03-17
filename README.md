## Random bash commands

**1. List all different first words from all files names in a directory**

```console 
$ ls $dir | awk '{print $1}' | uniq
```

**2. Daily inspirational quotes**

```console
$  fortune | cowsay -f calvin.cow | lolcat
```

**3. Commit with custom date**
```console
$ git commit --amend --no-edit --date "17/08/24 20:19:19 +0200"
```

---
### Git commands

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