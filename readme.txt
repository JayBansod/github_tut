first create .git  => git init
cheack status => git status
    short status => git status -s
commit one file => git commit
                      to insert massage => i
                      to exit => :WQ
commit in one line =>  git commit -m "<massage>"
        
add to stage area (single file)=> git add <file name>
add to stage area (multi file)=> git add -A

skip staging area and commit => git commit -a -m "<massage>"
awdfa
if we want restore our modified file to last commit (work only when we dont add file to staging area)=> git restore <file name> 
        if we want to restore all changes all file => git restore .
to see log => git log
to see only some log => git log -<number specified>
to see what we changed in commit => git log -p

to show what we changed into file (work only when we dont add file to staging area) => git diff
                                    (nothing show if we add file in staging area bcoz 
                                        it compare file with the file present in staging area)
        if we wants to compare staging area with last commit =>git diff --staged

create file => touch <hile name>
to remove file from commit (remove file from staging area)=> git rm --cached
                                             (delete file)=> git rm

.gitignore 
    create get ignore file => touch .gitignore
    
branch
        to see all branch => git branch
        to create new branch => git branch <bname>
        to jump on new branch => git cheackout <bname>
        to create new branch and junp to that branch =>git cheackout -b <bname>
                                            
    mearge two branch 
            => git merge <bname>
        