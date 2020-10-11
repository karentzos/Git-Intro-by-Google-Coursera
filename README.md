# Git-Intro-by-Google-Coursera

This is the first step on working with Git and Github.

A. In order to start working use command: git clone <https:// the link of your git-repo>
B. If you change sth directly from the web-repo use the command :  "git pull" directly from your local repo to update it accordingly with the master.
   However, be careful of how you use it.
   
C. Create localy a new directory: 
   mkdir checks |
   cd checks |
   git init   (Initialized empty Git repository in /Users/karentzos/Desktop/GitAll/Git-Intro-by-Google-Coursera/checks/.git/)
   Copy a file in it and then use the command: "git add <filename>" or "git add ." (. = all) to stage it. 
   
   * if you want to unstage the cached file use the command : " git rm --cached 'file' "
   * if you want to unstage a full directory after a "git rm" use the command : git reset HEAD <file>
   
D. In order to COMMIT it use the command git commit -m "your message" and then the command : git push origin master
   
   

   
