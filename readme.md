# лаболаторная работа Бастраков С.А. 
```
git add readme.md 
[master (root-commit) 3cc53ae] первый репозиторий
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 readme.md
 ```
 ```
 git clone https://github.com/kolei/oap
 Cloning into 'oap'...
remote: Enumerating objects: 123, done.
remote: Counting objects: 100% (123/123), done.
remote: Compressing objects: 100% (103/103), done.
Receivingotal 737 (delta 46), reused 89 (delta 20), pack-reused 614Receiving objects:  98% (723/737), 59.80 MiB | 727.00 KiB/s
Receiving objects: 100% (737/737), 59.84 MiB | 752.00 KiB/s, done.
Resolving deltas: 100% (337/337), done.
Updating files: 100% (185/185), done.
```
```
git status
On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        oap/

nothing added to commit but untracked files present (use "git add" to track)
```
```
git add README
fatal: pathspec 'README' did not match any files 
```
```
git status
On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        oap/

nothing added to commit but untracked files present (use "git add" to track)
```
```
git remote
origin
```
```
git stash
No local changes to save
```
