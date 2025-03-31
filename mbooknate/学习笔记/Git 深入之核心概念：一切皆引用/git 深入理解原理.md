首先需要在远端创建一个仓库
![[Pasted image 20241009210708.png]]
 中央式:只有远端是最终版本
 分布式:所有方都有全部版本  
 ![[Pasted image 20241009213333.png]]
git commit  相当于已经在本地提交了
git push 
![[Pasted image 20241009213809.png]]
![[Pasted image 20241009214103.png]]
![[Pasted image 20241015230501.png]]
HEAD 当前分支
master 默认分支
创建新的分支
直接合并代码
git  merge  分支名   报错解冲突然后，git merge --continue

图形化界面 git log  graph

git status  查看红绿两个区域的变化
远端仓库的初始状态
![[Pasted image 20241015232408.png]]
<span style="background:rgba(240, 107, 5, 0.2)">clone 后本地的状态</span>
![[Pasted image 20241015232634.png]]
<span style="background:rgba(240, 107, 5, 0.2)">git pull 相当于两个指令的合体</span>
git fetch 从远端镜像复制所有远端的分支复制到本地
git merge  origin/master
![[Pasted image 20241015233545.png]]



