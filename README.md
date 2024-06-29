# Java Setup

### 查看环境变量
```
echo $JAVA_HOME

echo $JRE_HOME

echo $PATH

echo $CLASSPATH
```

### Java版本
```
java -version
```

### Maven版本
```
mvn -v
```

### 打包
```
mvn clean package -P dev
```

### 后台启动
```
nohup java -jar *.jar > nohup.log 2>&1 &
```
