$ git init
Initialized empty Git repository in D:/my_git/codeProj/.git/
User@laptop-bor MINGW64 /d/my_git/codeProj (master)
$ git add mycod.txt
$ git commit -m "first code"
$ git branch -M main //change master
$ git remote add origin https://github.com/broject/myGitTest.git //set server
$ git push -u origin main //push to main
$ git pull
$ git commit -am "merged my cod"
$ git push

$ git branch
$ git checkout -b boroo //create branch
$ git add mycod.txt //change on boroo
$ git commit -m "s[]" //boroo commit
$ git checkout main
$ git checkout boroo
$ git push --set-upstream origin boroo //push to boroo
$ git merge boroo //to main