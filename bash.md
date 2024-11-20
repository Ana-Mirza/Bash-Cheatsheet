## Random bash commands

**1. List files with unique first word in a directory**

```console 
$ ls $dir | awk '{print $1}' | uniq
```
