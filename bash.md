## Random bash commands

**1. List files with unique first word in a directory**

```console 
$ ls $dir | awk '{print $1}' | uniq
```

**2. Daily inspirational quotes**

```console
$  fortune | cowsay -f calvin.cow | lolcat
```
