####git push force option
```
git push -f origin master
```

####git commit -a for all, -m for message
```
git commit -am 'added controllers'
```

####git add all from current directory
```
git add --all
```

####Revert previous commit
```
git reset --soft HEAD~1
```

####add single file
```
git add .gitignore 
```

####push to master without force
```
git push origin master
```

####modify origin (when forked from others)
```
git remote set-url origin https://github.com/@user/@repo.git
```


####Create a repo in github and follow below steps to add/commit files
```
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/@user/@repo.git
git push -u origin master
```

####push an existing repository from the command line
```
git remote add origin https://github.com/@user/@repo.git
git push -u origin master
```
