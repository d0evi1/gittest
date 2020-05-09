# branch练习

1.下载代码: 

	git clone https://github.com/d0evi1/gittest

2.修改代码：
	
	hello world => hello china

3.修改完代码后：

	git add *
	git commit -m "up to china."

4.创建分支，并切换分支
	
	git branch china
	git branch china

5.将更新提交到分支china
	
	格式：git push <远程主机名> <本地分支名>:<远程分支名>
	git push origin china:china

6.提交pull request给master
 
	在github上切换到branch下，点击new pull request.

7.merge request
	
a.查看是否有冲突，如果没有冲突，直接merge。
