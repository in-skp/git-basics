01. create git-basics folder
02. open vs code with git-basics folder
03. add index.html file
04. open terminal and enter git init command
05. empty repository will be initalized
06. create account in github and create repository with name git-basics
07. use ssh mode 
08. create public key using ssh-keygen -t rsa
09. open user\.ssh\ folder and copy .pub file contents
10. paste contents into github account setting -> ssh key -> add new key
11. make changes in index.html 
12. commit changes using git add . and git commit -m "comment"
13. you can check commit log using git log
14. add remote repository using git remote ssh url 
15. you can check remote repository using git remote -v
16. push local repository using git push -u remote origin master
17. project will be pushed into github
18. add css folder and add style.css file
19. make changes in index.html using style.css
20. commit folder and changes using git add --all and git commit -m "comment"
21. push changes using git push -u remote origin master
22. folder will be added in remote repository
