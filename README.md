# myfirstuse
第一次本地上传到GitHub
通过学习CSDN上的博客，自己尝试将本地代码上传到GitHub上，参考的文章链接如下：https://blog.csdn.net/qq_30092189/article/details/76468302；
https://blog.csdn.net/wangligong/article/details/53591593；
https://www.cnblogs.com/fnng/archive/2011/08/25/2153807.html；
https://blog.csdn.net/orange228/article/details/79365795；
https://blog.csdn.net/qq_23341529/article/details/79331519；

$ makdir ~/hello-world    //创建一个项目hello-world
$ cd ~/hello-world    //打开这个项目
$ git init    //初始化 
$ touch README
$ git add README   //更新README文件
$ git commit -m 'first commit'//提交更新，并注释信息“first commit” 
$ git remote add origin git@github.com:defnngj/hello-world.git   //连接远程github项目  
$ git push -u origin master   //将本地项目更新到github项目上去
