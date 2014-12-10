##git使用心得

- git服务需要绑定账号
- github需要绑定另一账号（此账号与git账号不可搞混）
- 从github上fork一个开源的项目
- 在工作目录使用`git init`初始化git缓存区
- 使用`git clone`命令fork好的项目克隆到本地，也可克隆自已的项目到本地
- 修改完成后使用`git add` '文件名'提交到缓存区
- 然后再使用`git commit -m'注释‘提交更改
- 使用`git status`查看修改及提交状态
- 使用`git push`把工作区修改好的文件推送到github（或服务器）
- 使用`git pull`请求合并修改（前提是fork的第三方资源）

```
以上就是我的使用心得，请求合并
```

##Mac 常用命今
- cd 返回主目录
- cd ..返回上级目录
- cd xx进入某一目录
- ls 查看当前目录文件
- pwd 查看当前目录路径
- cat filename 查看当前文件
