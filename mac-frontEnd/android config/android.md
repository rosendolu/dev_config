# android 开发环境配置

本机环境：

- shell zsh

步骤：

- 下载安装jdk
- 下载安装 android studio
- 插件
  - Genymotion

## 安装jdk

- 下载安装
- 配置环境变量

```shell
## open zsh config file
open -t .zshrc 

## add 
export JAVA_HOME=`/usr/libexec/java_home`

## source ～/.zshrc

## test 
echo $JAVA_HOME   
##  /Library/Java/JavaVirtualMachines/jdk-11.0.6.jdk/Contents/Home

```



## 安装android studio

参考

1. [mac 搭建 Android开发环境](https://cloud.tencent.com/developer/article/1037780)
2. 