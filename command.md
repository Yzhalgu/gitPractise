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