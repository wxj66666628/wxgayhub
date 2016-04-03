# 星际长途何时开始-wxgayhub
##个人记录

Git Bash 退出输入状态  
首先Esc退出输入状态，然后Shift+;，再输入q!或wq!（不保存改动，wq!是保存文件的写入修改）退出

$ git clone https://github.com/wxj66666628/wxgayhub.git                 <br>
$ git branch gh-pages                 <br>
$ git checkout gh-pages                 <br>
查看分支$ git branch                 <br>
合并到主干                     <br>
$ git checkout master                 <br>
$ git merge gh-pages                 <br>
提交分支                 <br>
$ git add .                 <br>
$ git commit -a    、 $ git commit -m "second change"                 <br>
$ git push origin gh-pages                 <br>


 合并冲突                 <br>
git fetch origin master                 <br>
git log -p master..origin/master                 <br>
git merge origin/master                 <br>
