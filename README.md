```
PS C:\Programs\GitDemo\Local> git init
Initialized empty Git repository in C:/Programs/GitDemo/Local/.git/
PS C:\Programs\GitDemo\Local> git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        desktop.ini
        index.html
        style.css

nothing added to commit but untracked files present (use "git add" to track)
PS C:\Programs\GitDemo\Local> git remote add origin https://github.com/falgunyash6789/Demo.git
PS C:\Programs\GitDemo\Local> git branch
PS C:\Programs\GitDemo\Local> git -v  
git version 2.46.1.windows.1
PS C:\Programs\GitDemo\Local> git remote  -v
origin  https://github.com/falgunyash6789/Demo.git (fetch)
origin  https://github.com/falgunyash6789/Demo.git (push)
PS C:\Programs\GitDemo\Local> git branch  
warning: ignoring broken ref refs/heads/desktop.ini
PS C:\Programs\GitDemo\Local> git branch -M main
PS C:\Programs\GitDemo\Local> git branch
warning: ignoring broken ref refs/heads/desktop.ini
PS C:\Programs\GitDemo\Local> git add .  
>> 
PS C:\Programs\GitDemo\Local> git status
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   desktop.ini
        new file:   index.html
        new file:   style.css

PS C:\Programs\GitDemo\Local> git commit -m "Done"
[main (root-commit) 3c533d1] Done
 3 files changed, 2 insertions(+)
 create mode 100644 desktop.ini
 create mode 100644 index.html
 create mode 100644 style.css
PS C:\Programs\GitDemo\Local> git branch      
warning: ignoring broken ref refs/heads/desktop.ini
* main
PS C:\Programs\GitDemo\Local> git checkout -b 'feature1'
Switched to a new branch 'feature1'
PS C:\Programs\GitDemo\Local> git checkout -b 'feature2'
Switched to a new branch 'feature2'
PS C:\Programs\GitDemo\Local> git checkout feature1
Switched to branch 'feature1'
PS C:\Programs\GitDemo\Local> git branch -d feature2
Deleted branch feature2 (was 3c533d1).
PS C:\Programs\GitDemo\Local> git branch
warning: ignoring broken ref refs/heads/desktop.ini
* feature1
  main
PS C:\Programs\GitDemo\Local> git checkout main
Switched to branch 'main'
PS C:\Programs\GitDemo\Local>
```
