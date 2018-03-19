git init				创建git管理仓库（文件会多出一个.git目录）
git add 文件名 				把文件添加到仓库
git status				查看状态
git commit -m '本次提交的说明'	把文件提交到仓库
git diff				查看上次修改内容

git log（如果嫌输出信息太多，看得眼花缭乱的，可以试试加上--pretty=oneline参数）							查看提交的历史记录
git reset --hard 版本号（commit后面的表示版本号，取前7位即可）
git reset --hard HEAD^		回退到上一个版本
git reset --hard HEAD^^		回退到上上一个版本
git reset --hard HEAD~100		回退到第100次的版本
cat ding/readme.txt			查看文本内容
git reflog				查看命令历史
