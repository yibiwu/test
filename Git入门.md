### git入门

**1、下载git: **

**2、注册git:**

**3、将git和GitHub连接起来**

（1）获取ssh密匙 。先是生成.ssh文件，使用命令ssh-gen,可能出现以下生成不了.ssh文件，解决办法：https://blog.csdn.net/qq_41530816/article/details/100179808。按照git提示的文件路径找到id_rsa.pub，复制其代码（密匙）

   (2)在GitHub中，点击头像，选择personsal settings，在ssh and GPG keys 中填入密匙，将其连接起来

**4、上传文件**

（1）创建文件，点击git bash,在窗口中输入git init，生成.git文件。可能会出现看不到.git的情况,需要在控制面板中找到文件管理，将显示隐藏的文件打钩。

  (2) git remote add origin https://github.com/yibiwu/test 连接仓库  test是仓库名

（3）把东西放到本地的文件夹中 ：git pull origin master

**5、本地的东西放到仓库中**

 git push origin master   需要输入输入用户名和密码

**6、推荐git学习的东西**

廖雪峰视频













​     

