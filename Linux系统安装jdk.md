# Linux系统安装jdk

## 一：下载jdk包

![](C:\Users\HI\Desktop\Linux系统\237.png)

## 二：解压压缩包

![](C:\Users\HI\Desktop\Linux系统\238.png)

![](C:\Users\HI\Desktop\Linux系统\239.png)

![](C:\Users\HI\Desktop\Linux系统\240.png)

## 三：配置环境变量

![](C:\Users\HI\Desktop\Linux系统\241.png)

![](C:\Users\HI\Desktop\Linux系统\242.png)

```shell
# 环境变量配置
export JAVA_HOME=/usr/local/java/jdk-21
export JRE_HOME=${JAVA_HOME}/jre
export CLASSPATH=.:${JAVA_HOME}/lib:${JRE_HOME}/lib
export PATH=${JAVA_HOME}/bin:$PATH
```

四：验证安装

![](C:\Users\HI\Desktop\Linux系统\243.png)