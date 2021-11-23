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

