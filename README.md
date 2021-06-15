## 当前项目的说明书
# git操作的具体步骤
   # 1、cd 路径进入当前目录
   # 2、配置git基本操作
   >     注没有消息就是好消息
   # 3、git init 在本地进行初始化（建立暂存区）
   >     .git 文件存储当前项目的所有版本信息
   # 4、工作区 => 暂存区
   >     git add 文件名
   >     git add * 提交所有的文件

   >     git commit -m "描述"
   # 5、查看当前工作区的状态
   >     git status
   # 6、从暂存区恢复文件到工作区
   >     git checkout 文件名
   # 7、查看工作区和暂存区版本的区别
   >     git diff
   # 8、clear 清屏操作
   # 9、git log
   >     查看已经提交到暂存箱的历史版本
   # 10、恢复文件到指定版本
   >     git reset --hard HEAD^退回上个版本^^两个是退回两个版本
   >     git reset --hard 版本号 退回指定版本
   # 11、生成ssh密匙
   >     ssh-keygen -t rsa -C "github邮箱"
   >     Windows电脑查找：我的电脑 》 用户 》用户名 》.ssh隐藏文件夹 》id_rsa.pub(里面就是密匙)
   # 12、github账户配置密匙
   # 13、暂存区 》 远程仓库
   >     git remote add origin https://github.com/1450080342/Demo1.git
   >     git push -u origin master
   >     注 提交可能需要输入账号密码
   # 14、git clone
   >     从远程仓库克隆项目到本地
   # 16、git pull
   >     从远程仓库同步本地代码