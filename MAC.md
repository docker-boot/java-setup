# MacOS

### 查看JavaHome目录
```
/usr/libexec/java_home -V
```

### Java环境变量
```
sudo vim /etc/profile

export JAVA_HOME=JavaHome目录
export JRE_HOME=${JAVA_HOME}/jre
export PATH=$PATH:${JAVA_HOME}/bin:${JRE_HOME}/bin
export CLASSPATH=.:${JAVA_HOME}/lib/dt.jar:${JAVA_HOME}/lib/tools.jar:${JRE_HOME}/lib

source /etc/profile
```

### Maven
```
http://maven.apache.org/download.cgi

下载 Binary zip archive

解压
```

### Maven环境变量
```
sudo vim ~/.bash_profile

export MVN_HOME=Zip解压目录/apache-maven-{版本}
export PATH=$PATH:${MVN_HOME}/bin

source ~/.bash_profile
```
