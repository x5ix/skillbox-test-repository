the first module is completed

=====1.13
work with git using intellij idea
=====1.11
new file .gitignore
new file error.log
new file error.log > .gitignore
new file debug.log
*.log > .gitignore
new dir log
logs/ > .gitignore
new file template.log
!!!IMPORTANT!!! can't exclude a file from the folder that is completely excluded
!logs/template.log
-----
.gitignore
error.log
*.log
logs/
logs/*.log
!logs/special.log
!!!IMPORTANT!!!
not added to .gitignore logs, users, ide, OS files, external libs, configs
=====1.10
git status
git add <file(s)>
git commit -m 'comment'
git show

deleting files 1.txt, 2.txt
edit readme.txt, index.html
add new test.html, actions.js

git add 
only del 1.txt, edit readme, new actions.js