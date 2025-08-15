```sh
/Applications/XAMPP/xamppfiles/htdocs/tmu-lab ❯ git init                                                                                     14:35:30
hint: Using 'master' as the name for the initial branch. This default branch name
hint: is subject to change. To configure the initial branch name to use in all
hint: of your new repositories, which will suppress this warning, call:
hint:
hint:   git config --global init.defaultBranch <name>
hint:
hint: Names commonly chosen instead of 'master' are 'main', 'trunk' and
hint: 'development'. The just-created branch can be renamed via this command:
hint:
hint:   git branch -m <name>
Initialized empty Git repository in /Applications/XAMPP/xamppfiles/htdocs/tmu-lab/.git/

/Applications/XAMPP/xamppfiles/htdocs/tmu-lab master* ❯ git remote add origin https://github.com/NguyenPhuDuc307/tmu-lab.git                 14:35:33

/Applications/XAMPP/xamppfiles/htdocs/tmu-lab master* ❯ git status                                                                           14:37:53
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        index.php
        style.css

nothing added to commit but untracked files present (use "git add" to track)

/Applications/XAMPP/xamppfiles/htdocs/tmu-lab master* ❯ git add .                                                                            14:38:05

/Applications/XAMPP/xamppfiles/htdocs/tmu-lab master* ❯ git status                                                                           14:38:42
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   index.php
        new file:   style.css


/Applications/XAMPP/xamppfiles/htdocs/tmu-lab master* ❯ git commit -m "create index page"                                                    14:38:47
[master (root-commit) 4ad5b64] create index page
 2 files changed, 25 insertions(+)
 create mode 100644 index.php
 create mode 100644 style.css

/Applications/XAMPP/xamppfiles/htdocs/tmu-lab master ❯ git push origin master                                                                14:39:13
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (4/4), 523 bytes | 523.00 KiB/s, done.
Total 4 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/NguyenPhuDuc307/tmu-lab.git
 * [new branch]      master -> master
```