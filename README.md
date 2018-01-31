## git的用法

1. 链接远程的git 仓库
> git remote add origin https://github.com/leinizisky/mygit.git

2. 将本地的文件全部提交
> git add .

3. 提交
> git commit -m "这里是提交注释"

4. 提交到远程git 仓库
> git push -u origin master

5. 查看提交的状态
> git status

6. 仓库变成git可以管理的仓库
> git init 

7. s插入输入，esc 退出，:wq保存操作

8.解决git push 一直停留在writing objects 的问题
> git config --global http.postBuffer 524288000

