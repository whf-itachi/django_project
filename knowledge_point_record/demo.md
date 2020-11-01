# git 命令
git branch : 查看当前分支
git checkout -b dev : 切换并创建dev（自定义）分支
git push origin dev:dev 推送内容到远端分支
- 注：默认是从哪克隆的代码就会提交到哪，如果要指定分支的话使用上述命令
- 第一个dev表示推送本地的dev分支，第二个dev表示推送到远端的dev分支（如果没有会自动创建）

