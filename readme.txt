1)  first create .git  => git init

2)  cheack status      => git status
            short status => git status -s

3)  commit
            one file => git commit
                      to insert massage => i
                      to exit => :WQ
            commit in one line =>  git commit -m "<massage>"
        
4)  Stage area
        add file to stage area (single file)=> git add <file name>
        add to stage area (multi file)=> git add -A

5)  skip staging area and commit => git commit -a -m "<massage>"

6)  Restore file
        if we want restore our modified file to last commit (work only when we dont add file to staging area)=> git restore <file name> 
        if we want to restore all changes all file => git restore .

7) Log
        to see log => git log
        to see only some log => git log -<number specified>
        to see what we changed in commit => git log -p

8) Difference
        to show what we changed into file (work only when we dont add file to staging area) => git diff
                                            (nothing show if we add file in staging area bcoz 
                                                it compare file with the file present in staging area)

                if we wants to compare staging area with last commit =>git diff --staged

9)  create file => touch <hile name>

10) Remove file form stage area
        to remove file from commit (remove file from staging area)=> git rm --cached
                                             (delete file)=> git rm

11)
        .gitignore 
            create get ignore file => touch .gitignore
    
12) Branch
        to see all branch => git branch
        to create new branch => git branch <bname>
        to jump on new branch => git cheackout <bname>
        to create new branch and junp to that branch =>git cheackout -b <bname>

13) Merge                                            
    mearge two branch 
            => git merge <bname>

14) Add

    to add into file github 
            to connect local repository to remote repository 
                =>git remote add <short name> <url>
                =>git remote add origin https://github.com/JayBansod/github_tut.git
                                        (these url is refered as origin)    

            to see remote => git remote
            to see remote from where we fetch or push => git remote -v
            to change url => git <location name> set-url  <location> <url>
                            git origin set-url origin <url>

15) Push
        git push -u <location> <bname>
        git push -u origin master

    