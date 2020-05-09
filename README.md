# branch练习

master代码：

	print("hello world.")
	
branch china代码，增加：

	print("hello china.")

两者会有冲突。

# 一、一个简单branch/merge过程

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
	
查看是否有冲突，如果没有冲突，直接merge。

	点击 merge pull request
	点击 confirm merge
	
8.测试有冲突的情况：

主干master在merge完成，新增一行hello usa，并提交修改.

	print("hello world.")
	print("hello china.")
	print("hello usa.")

8.是否需要删除branch。
