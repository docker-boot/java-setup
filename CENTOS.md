# CentOS

### Java下载
```
https://www.oracle.com/java/technologies/javase/javase-jdk8-downloads.html

Linux x64 | jdk-8u271-linux-x64.tar.gz
```

### Java安装
```
cd /usr/local

mkdir java

cd java

拷贝 jdk-8u271-linux-x64.tar.gz 到 /usr/local/java

tar -xzvf jdk-8u271-linux-x64.tar.gz

mv jdk1.8.0_271 jdk1.8
```

### Java环境变量
```
sudo vim /etc/profile

export JAVA_HOME=/usr/local/java/jdk1.8
export JRE_HOME=${JAVA_HOME}/jre
export PATH=$PATH:${JAVA_HOME}/bin:${JRE_HOME}/bin
export CLASSPATH=.:${JAVA_HOME}/lib/dt.jar:${JAVA_HOME}/lib/tools.jar:${JRE_HOME}/lib

source /etc/profile
```

### Java命令
```
ln -s /usr/local/java/jdk1.8/bin/java /usr/bin/java
```

### Maven
```
http://maven.apache.org/download.cgi

下载 Binary tar.gz archive

tar -xzvf apache-maven-{版本}-bin.tar.gz
```

### Maven环境变量
```
sudo vim /etc/profile

export MVN_HOME=Gz解压目录/apache-maven-{版本}
export PATH=$PATH:${MVN_HOME}/bin

source /etc/profile
```
