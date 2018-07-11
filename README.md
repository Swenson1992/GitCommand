…or create a new repository on the command line
```linux
echo "# testGitCommand" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/songjian925/testGitCommand.git
git push -u origin master
```
…or push an existing repository from the command line
```linux
git remote add origin https://github.com/songjian925/testGitCommand.git
git push -u origin master
```
