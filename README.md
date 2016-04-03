# 星际长途何时开始-wxgayhub
first page in gayhub

Git Bash 退出输入状态  
首先Esc退出输入状态，然后Shift+;，再输入q!或wq!（不保存改动，wq!是保存文件的写入修改）退出

$ git clone https://github.com/wxj66666628/wxgayhub.git
$ git branch gh-pages
$ git checkout gh-pages
查看分支$ git branch
合并到主干
$ git checkout master
$ git merge gh-pages
提交分支
$ git add .
$ git commit -a    、 $ git commit -m "second change"
$ git push origin gh-pages


 合并冲突
git fetch origin master
git log -p master..origin/master
git merge origin/master
