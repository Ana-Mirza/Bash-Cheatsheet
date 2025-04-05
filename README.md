## Random bash commands

**1. List all different first words from all files names in a directory**

```console 
$ ls $dir | awk '{print $1}' | uniq
```

**2. Daily inspirational quotes**

```console
$  fortune | cowsay -f calvin.cow | lolcat
```

**3. Recover VMWare stuck in initframs prompt**
```console
$ fsck -y /dev/sda2
$ reboot -y
```

---
### Git commands

**1. Commit with custom date**
```console
$ git commit --amend --no-edit --date "17/08/24 20:19:19 +0200"
```

**2. Multiple commits fix**

```console
$  git rebase -i HEAD~7
```
**3. Add current changes to prev commit**

```console
$ git commit --amend --no-edit
$ git push -f origin <branch>
```

**4. See changes made**

```console
$ git diff origin/<branch_name>
```

**5. Get files changed in last commit**
```console
$ git diff --name-only HEAD HEAD~1
```

**6. Updatea submodules**
```console
$ git submodule update --recursive --remote --force
```
