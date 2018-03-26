git init				创建git管理仓库（文件会多出一个.git目录）
git add 文件名 				把文件添加到仓库
git status				查看状态
git commit -m '本次提交的说明'		把文件提交到仓库
git diff				查看上次修改内容
git log（如果嫌输出信息太多，看得眼花缭乱的，可以试试加上--pretty=oneline参数）		

查看提交的历史记录
git reset --hard 版本号（commit后面的表示版本号，取前7位即可）
git reset --hard HEAD^		回退到上一个版本
git reset --hard HEAD^^		回退到上上一个版本
git reset --hard HEAD~100	回退到第100次的版本
cat ding/readme.txt		查看文本内容
git reflog			查看命令历史
git checkout -- (文件名)		撤销工作区的修改
git reset HEAD (文件名)		撤销暂存区的修改
rm （文件名）			删除文件
git checkout -- (文件名)		恢复文件
git branch			查看分支
git branch <name>		创建分支
git checkout <name>		切换分支
git checkout -b <name>		创建+切换分支
git merge <name>		合并某分支到当前分支
git branch -d <name >		删除分支
git log --grap			查看分支合并图