# java-tool
jdk eclipse 开发工具

jdk1.8 下载地址：  
<http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html>

# jdk1.8环境配置   

新建系统变量：JAVA_HOME 、CLASSPATH 和Path
变量名：JAVA_HOME 
变量值：C:\Program Files\Java\jdk1.8.0_66

变量名：CLASSPATH 
变量值：.;%JAVA_HOME%\lib\dt.jar;%JAVA_HOME%\lib\tools.jar

变量名：Path 
变量值：%JAVA_HOME%\bin;%JAVA_HOME%\jre\bin;
注意： 变量名JAVA_HOME 的变量值是要根据你自己安装jdk的文件目录，因此如果你更改了安装文件目录，就可能和我所给出的不一样;

测试环境变量配置是否成功。  
同时按住Win和R键，桌面左下角弹出‘运行’窗口，输入cmd，再回车；
跳出DOS命令行窗口输入依次输入“JAVAC”、“java”、“java -version”，观察输出结果是否与截图相同，否则为环境变量配置失败。

# eclipse 下载 地址： 
<https://www.eclipse.org/downloads/download.php?file=/oomph/epp/oxygen/R/eclipse-inst-win64.exe>


