$ git init
Initialized empty Git repository in D:/Works/itSchool/mySwTrait/my_git/codeProj/.git/

User@laptop-bor MINGW64 /d/Works/itSchool/mySwTraining/SW/weekeProj (master)
$ git add mycod.txt

User@laptop-bor MINGW64 /d/Works/itSchool/mySwTraining/SW/weekGit/my_git/codeProj (master)
$ git commit -m "first code"
[master (root-commit) c83e303] first code
 1 file changed, 1 insertion(+)
 create mode 100644 mycod.txt

User@laptop-bor MINGW64 /d/Works/itSchool/mySwTraining/SW/weekGit/my_git/codeProj (master)
$ git branch -M main

User@laptop-bor MINGW64 /d/Works/itSchool/mySwTraining/SW/weekGit/my_git/codeProj (main)
$ git remote add origin https://github.com/broject/myGitTest.g

User@laptop-bor MINGW64 /d/Works/itSchool/mySwTraining/SW/weekGit/my_git/codeProj (main)
$ git push -u origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 230 bytes | 230.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/broject/myGitTest.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.