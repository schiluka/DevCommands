#git push force option
git push -f origin master

#git commit -a for all, -m for message
git commit -am 'added controllers'

#git add all from current directory
git add --all

#Revert previous commit
git reset --soft HEAD~1

#add single file
git add .gitignore 

#push to master without force
git push origin master

#modify origin (when forked from others)
git remote set-url origin https://github.com/schiluka/spring-rest-maven.git


