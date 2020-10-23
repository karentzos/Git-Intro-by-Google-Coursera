# Git-Intro-by-Google-Coursera

This is the first step on working with Git and Github.

A. In order to start working use command: git clone <https:// the link of your git-repo>
B. If you change something directly from the web-repo use the command :  "git pull" directly from your local repo to update it accordingly with the master.
   However, be careful of how you use it.
   
C. Create localy a new directory: 
   mkdir checks |
   cd checks |
   git init   (Initialized empty Git repository in /Users/karentzos/Desktop/GitAll/Git-Intro-by-Google-Coursera/checks/.git/)
   Copy a file in it and then use the command: "git add <filename>" or "git add ." (. = all) to stage it. 
   
   OR skip the init part and directly git add the directory including also the files contained in it.
    
    --
      * If you have modified a file  : git checkout -- "filename" will discard any changes of the working directory!
      * If you have already stage it : git reset HEAD "filename" to unstage it! 
    --
    
   * if you want to unstage the cached file use the command : "git rm --cached 'file' "
   * if you want to unstage a full directory after a "git rm" use the command : git reset HEAD <file>
   
D. In order to COMMIT it use the command git commit -m "your message" and then the command : git push origin master/main
   
E. Use "git config -l" in order to check our current configuration.    

F. Anatomy of a Commit Message : use the "git log" to check the commit messages!

G. Correct the error of the unpopulated submodule dirname. 
   On the most of the cases this error appears when you suddenly lose the .git file from the specific directory.
   Use "git rm --cached . -rf" inside the problematic directory.

H. Playing with branches:

git branch                  : check the branches

git branch new-name         : create new name

git checkout new-name       : navigate to the new branch

git checkout -b new-name    : create new branch and navigate to it. 

git branch -d new-name      : delete selected branch (if there isn't any changes, or merged)

git branch -D new-name      : force delete selected branch (if the changes aren't merged you can use this command)

   MERGING:

	combine data + history

        git merge new-name (checkout to master firstly)

 
