# windows hadoop-2.7.0
## 1、这是一个编译好的 win7 + x64 的 hadoop-2.7.0，如果需要下载可以直接下载bin目录下的内容，替换我们在其他网站上下载的hadoop-2.7.0/bin目录内容，然后配置etc/hadoop/hadoop-env.cmd中的JAVA_HOME环境变量，以及将%HADOOP_HOME%\bin目录加入Path环境变量。
## 2、是在windows上运行的hadoop,而不是linux。
## 3、不用担心运行时缺少或找不到winutils.exe。
## 4、替换成功之后，就可以直接运行sbin/start-all.cmd，启动hadoop四个服务namenode,datanode,nodemanager,resourcemanager。
## 5、不用安装Cygwin，也不用担心ssh免密登录。
