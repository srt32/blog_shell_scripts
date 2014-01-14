blog_shell_scripts
==================

Run this script in the shell to get a 'real-time' look at your git log:

```
#!/bin/bash
while(true)
do
  clear
  git log --oneline --abbrev-commit --branches=* --graph --decorate --color
  sleep 1
done
```
