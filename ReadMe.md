this is first project
submit the data to database

== remove from the local git repository if you dont want to push that to github repository
git rm --cached file_Name
== it will be removed from the local git and it will be untracked in working directory

- later I have added that file into .gitignore file, so by default git will ignore those files which are in .gitignore file and push other files to git local repository

- Adding the tag:
  git tag -a v1.1 -m "2nd release"
  git tag
  git show v1.1

  git push origin v1.1

- if you want to work on the other respository

  - clone it to your local desktop
  - git clone "URL"
  - go to VS code and open the folder

- git log
- git log --pretty=onelone

- git branch
- git checkout -b feature1

- git switch -c feature2
- git branch --all
- git branch -d feature2
