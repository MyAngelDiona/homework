# Git教程   
##  git简介  
    - Git是目前世界上最先进的分布式版本控制系统，在处理各种项目时都十分高效，而且非常的高大上。  
    - SVN是集中式版本控制系统，版本库是集中放在中央服务器的，而干活的时候，用的都是自己的电脑，所以首先要从中央服务器哪里得到最新的版本，  
    - 然后干活，干完后，需要把自己做完的活推送到中央服务器。而且集中式版本控制系统是必须联网才能工作。  
    - Git是分布式版本控制系统，它就没有中央服务器的，每个人的电脑就是一个完整的版本库，这样，工作的时候就不需要联网了，因为版本都是在自己的电脑上。  
##  git安装  
    - （仅列出在Windows系统下的安装过程）  
    -打开Git官网下载安装程序，然后按照默认选项安装即可。  
    -安装完成后，打开Git bash软件，弹出一个类似cmd的命令行窗口，证明安装成功        
##  创建版本库   
    -版本库(repository)也叫仓库，可以看做一个目录，这个目录里的所以文件都由Git进行管理，每个文件的修改、删除，Git都能跟踪    
##  工作区和暂存区  
    -工作区（Working Directory）  
    -learngit 文件夹就是一个工作区。  
    -版本库（Repository）  
    -工作区有个隐藏目录 .git ，这个不算工作区，而是 Git 的版本库  
    -版本库里面的 index(stage) 文件叫暂存区，还有Git为我们自动创建的第一个分支 master ，以及指向 master 的一个指针叫做 HEAD  
##  Git 创建仓库

    -你可以使用一个已经存在的目录作为Git仓库。
    -git init
    -Git 使用 git init 命令来初始化一个 Git 仓库，Git 的很多命令都需要在 Git 的仓库中运行，所以 git init 是使用 Git 的第一个命令。
    -在执行完成 git init 命令后，Git 仓库会生成一个 .git 目录，该目录包含了资源的所有元数据，其他的项目目录保持不变。
我的github项目地址：https://github.com/Eliauk-kuroshio/xiaoyuandaohang  
