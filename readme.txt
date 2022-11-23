first create .git  => git init
cheack status => git status
commit one file => git commit
                      to insert massage => i
                      to exit => :WQ
commit in one line =>  git commit -m "<massage>"
        
add to stage area (single file)=> git add <file name>
add to stage area (multi file)=> git add -A

skip staging area and commit => git commit -a -m "<massage>"

if we want restore our modified file to last commit (work only when we dont add file to staging area)=> git restore <file name> 
        if we want to restore all changes all file => git restore .
to see log => git log
to see only some log => git log -<number specified>
to show what we changed into file (work only when we dont add file to staging area) => git diff
                                    (nothing show if we add file in staging area bcoz 
                                        it compare file with the file present in staging area)
        if we wants to compare staging area with last commit =>git diff --staged