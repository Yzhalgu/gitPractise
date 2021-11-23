`git commit -m <message>>`


Using readme file commit as an example
* -m represents the illustration of this specific commit.
* 1 file changed: the readme file we just added
* 2 insertions: the two lines of new code we added. 

`git log`

Check the commit log starts from the latest one.

`git reset --hard HEAD^`

回退倒上一次提交, hard 后也可以添加指定版本号回退到特定commit

`git reflog`

to check the reference number of each commit

## Working Directory (工作区)

Is the directory you can see such as gitPractise

## Repository （版本库）
'.git' is a repository, and the most important part of it is called stage (index):暂存区; the first branch git automatically created, and a pointer called HEAD pointing at master branch.

`git add`： 把文件修改添加到暂存区
`git commit`: 把暂存区的内容提交到当前分支



# git管理的是修改，而非文件本身
Git管理的是修改，当你用git add命令后，在工作区的第一次修改被放入暂存区，准备提交，但是，在工作区的第二次修改并没有放入暂存区，所以，git commit只负责把暂存区的修改提交了，也就是第一次的修改被提交了，第二次的修改不会被提交。

