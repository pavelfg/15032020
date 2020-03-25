# 15-03-2020 GIT basics
- 'init' : make current folder a git repository
- 'status' : see the status of current repository
- 'add' : put files into the index (stagging area)
- 'commit' : commit the files from staging area
    - 'commit -m "MESSAGE" ' :  direclty put in  single line commit message
- 'diff' : look at differences between 2 commit states 
- 'log' : look at the history
    + 'log --oneline' : only get  the oneline  view  
    + 'log  --oneline --all --graph --decorate' : see everything in history
- 'checkout <hash> <file>' : restore a single file from a point in history
-  'checkout <hash>': restore the entire folder to that point in time

- index/stagging area: files in here will be commited
This is my first file to check GIT

- HEAD : where you are looking at in git hisotry