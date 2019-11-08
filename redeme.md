### 1. 创建版本库
第一步：创建版本库
    - mkdir learngit  (创建一个新的文件夹)
    - cd learngit (进入到这个文件夹)
    - pwd (`pwd`命令用于显示当前目录,本机地址`/d/owerDir/github/learngit`)
第二步：通过`git init`命令把目录变成git可以管理的仓库
    - git init
    (通过 `ls -ah` 可以查看影藏文件夹)
第三步：代码放入版本库
    - git add <文件名>  文件添加到仓库 
    - git commit -m '注释'  把文件提交到仓库

### 2. 时光穿梭机
- git diff <文件名> 查看该文件的变化
- git status 查看工作区状态
- git log 查看提交记录
- git log --pretty=oneline  单行查看文件
- git reset --hard HEAD^ 版本回退
- git reset --hard 1094a 再回到回退前的版本
- git reflog 记录每一次命令


