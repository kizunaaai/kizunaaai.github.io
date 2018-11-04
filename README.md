# 实战学习心得

## First 代码笔记

### About github

#### 本地 upload 到服务器和github pages托管
`git init`	初始化为 git 仓库文件夹  
`git remote add origin git@github.com:kizunaaai/kizunaaai.github.io.git`	 设置 git 仓库文件夹的远程地址  
`git add .`	三部曲  
`git commit -m "first commit"`  
`git push -u origin master`  

#### 服务器 clone 到本地
`get clone git@github.com:<username>/<repository>.git`  
示例： `git clone git@github.com:kizunaaai/kizunaaai.github.io.git`  

#### git托管 三连发
`git add .`  
`git commit -m " 备注内容 "`  
`git push`  

#### 仓库命名规范
讲仓库设置为 < repository_name >.github.io  
之后可直接通过访问 https://< repository_name >.github.io 直接访问到仓库
  
### About command
#### 一些基本常用的命令
* pwd    查看所在目录
* dir    浏览目录
* ls 
   * ls/	查看目录下的子节点
   * ls -a	显示隐藏文件
   *　ls -l	显示详情
* cd 
   * cd ..	返回上级目录
   * cd <folder_name>	打开相对路径
   * cd /<folder_name>	打开绝对路径
   * cd ~/	打开user路径
* mkdir 
   * mkdir 	删除空目录
   * mkdir -r <folder_name>	删除文件夹以及里面所有子节点
   * mkdir -rf <folder_name>	强制删除文件夹或文件
* touch
   * touch <filename>	创建文件
   * 拓展
      * echo	重定向
      * echo " content " > 123		将 content 覆盖到文件名为 123 的文件中
      * echo " content  " >> 123 	讲 content 追加到文件名为 123 的文件中
* mv 
   * mv 123.txt 321.txt		将文件名为123的txt重命名为321
   * mv 123.txt download	将文件123.txt移动到相对路径的download文件夹中
* vi		文本编辑器
   * vi <filename>		打开文件
   * i		启用编辑
   * esc	退出编辑
   * :wq!	保存

---

## Second 心得
这次应该算是真的入门了8 ，一直在徘徊犹豫 ，通过这次实践也学习到了许多平常经常接触却不怎么了解的东西 ，很开心能赶上自此活动 ，大家一起加油吧！  
~报名之后犹豫过，但是很开心还是投入进来了~  
最后一段猛如虎的操作之后就要去睡觉觉了  
2018/11/4	2:00

## 经验&教训
README.md 文件一定一定要用 UTF-8 编码写，不然无法托管到 github pages  
5分钟又过去了  
2018/11/4	2:05  
