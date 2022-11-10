# git对一个目录进行版本控制
+ 进入要管理的文件夹
+ 执行初始化命令  
  ```
    git init
  ```
+ 管理目录下的文件状态  
  ```
    git status    
    注：新增的文件和修改过后的文件都是红色
  ```   
+ 管理指定文件(红变绿)
  ```
    git add 文件名  
    git add .
  ```
+ 个人信息配置：用户名、邮箱(最初执行一次)
  ```
    git config --global user.email "you@example.com"  
    git config --global user.name "Your Name"
  ``` 
+ 生成版本
  ```
    git commit -m '描述信息'
  ```
+ 查看版本记录
  ```
    git log
  ```
- 版本回滚  
  1. 回滚到之前的版本
  ```
    git log //查找版本号
    git reset --hard 版本号
  ``` 
  2.  回滚到之后的版本
  ```
    git reflog
    git reset --hard 版本号
  ```


`git branch`

开发进度100%

