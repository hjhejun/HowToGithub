关于怎样使用GitHub的问题，有如下几个值得学习的好去处

http://www.worldhello.net/gotgithub/

http://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000   //Git教程-廖雪峰的官方网站

http://www.zhihu.com/question/20070065

另外，讲下简易的使用方法
大致有以下几个步骤,
mkdir test
cd test
git init   //初始化，本地建立空仓

git add aa.c
git add bb.c
....
git add *   //添加文件到本地仓

git commit -m "描述本次提交"

最后将本地仓推到server上即可
publish repository //非命令行
