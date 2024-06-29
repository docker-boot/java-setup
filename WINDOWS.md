# Windows

### 查看Java版本
```
java -version
```

### Java下载
```
https://www.oracle.com/java/technologies/javase/javase-jdk8-downloads.html

Windows x64 | jdk-8u261-windows-x64.exe
```

### Java环境变量
```
1、新增
变量名(N)：JAVA_HOME
变量值(V)：C:\Program Files\Java\jdk1.8.0_261

2、新增
变量名(N)：JRE_HOME
变量值(V)：C:\Program Files\Java\jdk1.8.0_261\jre

3、新增
变量名(N)：CLASSPATH
变量值(V)：C:\Program Files\Java\jdk1.8.0_261\lib\dt.jar:C:\Program Files\Java\jdk1.8.0_261\lib\tools.jar:C:\Program Files\Java\jdk1.8.0_261\jre\lib

4、编辑，变量名(N)：Path
新增，变量值(V)：C:\Program Files\Java\jdk1.8.0_261\bin
新增，变量值(V)：C:\Program Files\Java\jdk1.8.0_261\jre\bin

注：
CLASSPATH 和 Path 中的 C:\Program Files\Java\jdk1.8.0_261 和 C:\Program Files\Java\jdk1.8.0_261\jre
可用 %JAVA_HOME% 和 %JRE_HOME% 替换
```

### Maven
```
http://maven.apache.org/download.cgi

下载 Binary tar.gz archive | apache-maven-3.6.3-bin.tar.gz

解压
```

### Maven环境变量
```
1、新增
变量名(N)：MVN_HOME
变量值(V)：C:\Program Files\Apache\Maven

2、编辑，变量名(N)：Path
新增，变量值(V)：C:\Program Files\Apache\Maven\bin

注：
Path 中的 C:\Program Files\Apache\Maven
可用 %MVN_HOME% 替换
```
