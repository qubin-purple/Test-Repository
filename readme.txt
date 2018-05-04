从远程库获取到本地  $ git clone https://github.com/qubin-purple/Test-Repository.git
获取后要在本地安装  $ git init
查看库状态          $ git status
在库中添加文件      $ git add readme.txt
提交修改            $ git commit -m add file readme.txt
查看修改            $ git diff readme.txt
向远程库推送修改    $ git push -u origin master
查看提交记录        $ git log --pretty
更新到历史版本，回溯到当前版本的上一个版本，Head当前版本      $ git reset --hard Head~1
查看所有历史版本    $ git relog
更新到某一历史版本  $ git reset --hard commit_id
查看文件            $ cat readme.txt


