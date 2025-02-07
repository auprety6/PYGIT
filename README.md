PS C:\Users\oakto\OneDrive\Documents\PYGIT> git add .
PS C:\Users\oakto\OneDrive\Documents\PYGIT> git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   leetcodenestedloop.py

PS C:\Users\oakto\OneDrive\Documents\PYGIT> git commit - m "testing with print statement"
error: pathspec '-' did not match any file(s) known to git
error: pathspec 'm' did not match any file(s) known to git
error: pathspec 'testing with print statement' did not match any file(s) known to git
PS C:\Users\oakto\OneDrive\Documents\PYGIT> git commit -m "testing with print statement" 
[main d7690ab] testing with print statement
 1 file changed, 1 insertion(+)
PS C:\Users\oakto\OneDrive\Documents\PYGIT> git push origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 374 bytes | 374.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/auprety6/PYGIT.git
   5e18769..d7690ab  main -> main
PS C:\Users\oakto\OneDrive\Documents\PYGIT> 
