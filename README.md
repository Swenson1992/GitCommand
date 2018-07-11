## Git Command
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
1、git 下如何把另外一个分支的某个文件改动merge 合并到这个分支，而不是把整个分支merge过来
```
git checkout <branch>
git checkout --patch <other_branch> <file>
```
