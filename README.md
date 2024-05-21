# baidu-test
1. git clone 下载项目
2. git branch 创建分支，git branch -a 查看所有分支，git branch -a -v 查看所有分支详细信息
3. git checkout 切换分支
4. git remote 本地仓库对应的远程仓库信息，git remote -v 查看详细信息
5. git remote update origin 拉取远程仓库的变更到本地
6. git log --oneline --graph 图标形式显示日志
7. git merge origin/develop 合并远程仓库的develop分支到当前分支
8. git fetch origin develop 拉取远程仓库的develop分支到本地
9. git pull = git fetch + git merge
10. git push origin develop 推送本地分支到远程仓库的develop分支
11. git status 查看当前分支状态

# qc 考核：
1. 创建一个云IDE
2. 使用 Comate 生产并采纳一段注释或单测用例
3. 合并一个 git 分支：将当前这个代码库的feature_print_my_name_on_demo_app合并到master，解决冲突发评审，合入master。
    1. 拉取远程分支到本地：git fetch origin feature_print_my_name_on_demo_app
    2. 切换到master分支：git checkout master
    3. 更改加入缓存区：git add .
    4. 提交到本地仓库：git commit -m "第一次提交"
    5. 若此时进行合并操作会出现代码冲突：git merge origin/feature_print_my_name_on_demo_app
    6. 解决冲突文件并标记冲突已解决：git add 文件名
    7. 最后，提交合并结果：git commit -m '解决冲突'
    8. 更改提交到远程仓库的主分支审阅队列：git push origin HEAD:refs/for/master
4. 
