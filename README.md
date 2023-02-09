# Spark
Windows 本地配置spark开发环境 (Refer https://zhuanlan.zhihu.com/p/149469688)
1. 安装JDK <br>
   JDK下载路径 ： https://www.oracle.com/cn/java/technologies/downloads/ <br>
   安装好后配置环境变量：<br>
    新建JAVA_HOME <br>
    ![image](https://user-images.githubusercontent.com/28624027/210785889-6bb5eb1e-72dd-4041-bf53-ca53946f000e.png) <br>
    在Path中添加JAVA_HOME/bin <br>
    ![image](https://user-images.githubusercontent.com/28624027/210792989-03ec94dd-8619-4897-b1d4-68a593c58555.png) <br>
   设置完成后在CMD命令窗口输入java -version验证是否安装成功 <br>
   ![image](https://user-images.githubusercontent.com/28624027/210793293-646633ce-3a81-48f2-b266-e0d9457166e2.png) <br>


2. 安装Spark
   到官网https://spark.apache.org/downloads.html选择合适的版本下载，注意Spark与Hadoop版本选择要相对应，建议下载预编译（Pre-built）好的版本，省得麻烦 <br>
   ![image](https://user-images.githubusercontent.com/28624027/210798496-b1894a4e-d6b4-4fbe-b3a1-d2ce94b0693b.png) <br>
   下载完成后解压到你喜欢的目录，然后配置环境变量，例如解压在C:\Users\dell\Documents\Env\spark-3.0.3-bin-hadoop3.2目录下，则环境变量如下配置 <br>
   配置变量名为SPARK_HOME，值为C:\Users\dell\Documents\Env\spark-3.0.3-bin-hadoop3.2 <br>
   在Path变量下新建%SPARK_HOME%\bin <br>

4. 安装Scala
5. 安装Hadoop
   到官网https://hadoop.apache.org/releases.html下载与上边的Spark对应的版本 <br>
   ![image](https://user-images.githubusercontent.com/28624027/210801523-de76f8c0-5f83-47db-9911-3707f00f95c7.png) <br>
   下载完成后解压到你喜欢的目录，然后配置环境变量，例如解压在C:\Users\dell\Documents\Env\hadoop-3.2.2目录下，则环境变量如下配置 <br>
   配置变量名为HADOOP_HOME，值为C:\Users\dell\Documents\Env\hadoop-3.2.2 <br>
   在Path变量下新建%HADOOP_HOME%\bin <br>
   到这里https://github.com/cdarlint/winutils对应版本的bin目录下载hadoop.dll和winutils.exe，复制到hadoop目录的bin目录下 <br>

