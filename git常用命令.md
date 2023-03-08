pwd :显示当前终端会话所在的目录位置

ls :  显示当初目录的所有文件

git init : 初始化

 a 进入编辑

Ecs 退出然后英文冒号: wq  保存并退出

  git config   配置git信息
（
git config --global ![img](file:///C:\Users\hang\AppData\Roaming\Tencent\QQTempSys\%W@GJ$ACOF(TYDYECOKVDYB.png)user.name "Your Name"
git config --global user.email "email@example.com"
）
git init        初始化仓库-把当前的项目目录使用git软件进行管理，得到一个.git的隐藏文件夹
git status      查看当前仓库的状态，是否有文件没有被管理起来
git add 指定文件/.        把文件从工作区添加到暂存区
git commit -m ‘备注’        把文件从暂存区添加到本地仓库，只有本地仓库里面的东西才会被放到服务器
git remote add origin 项目地址        把本地仓库和远程仓库进行关联
git push -u origin "master"       把本地仓库里面的内容上传到远程仓库
git clone 远程仓库地址          把已经托管到服务器的代码克隆下来
git log --oneline         查看提交的历史记录
git reset --hard 版本号         回滚


分支

什么是分支：就在git的管理下，允许使用不同的代码来分别开发，然后再最终合并到一起

分支的操作：

\```js
0  查看分支   git branch
\1. 创建分支   git branc -c 分支名称  /  git switch -c 分支名称
\3. 切换分支   git checkout 分支名称  /  git switch 分支名称
\4. 合并分支   git merge 分支名称
\5. 删除分支   git branch -D 分支名称  