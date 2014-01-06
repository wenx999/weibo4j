记录
=======

### 操作记录 ###
1) git remote -v

origin  https://github.com/wenx999/weibo4j (fetch)
origin  https://github.com/wenx999/weibo4j (push)

2) git remote add belerweb git@github.com:belerweb/weibo4j.git

3) git remote -v

belerweb  git@github.com:belerweb/weibo4j.git (fetch)
belerweb  git@github.com:belerweb/weibo4j.git (push)
origin  https://github.com/wenx999/weibo4j (fetch)
origin  https://github.com/wenx999/weibo4j (push)

4) git fetch belerweb

From github.com:belerweb/weibo4j
 * [new branch]      master     -> belerweb/master

5) git merge belerweb/master

Already up-to-date.

6) git commond 
 * git add NOTE.md
 * git status
 * git commit -m "add NOTE.md"
 * git push  origin master


### 参考 ###
 * http://my.eoe.cn/curious/archive/3563.html
 * http://my.eoe.cn/iceskysl/archive/3195.html
