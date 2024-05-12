# 说明文档

### 修改接口地址
Url.smali 文件  第701行
~~~ smali
    const-string v0, "xxxxx"  #改成你的接口地址
~~~

### 反编译
~~~
    java -jar .\apktool.jar  -r -f d tv.apk
~~~

### 打包
~~~
    java -jar .\apktool.jar  b tv
~~~

### 签名
~~~
    .\apksigner.bat sign --ks tv.jks tv.apk  #apksigner.bat 在android-sdk build-tools目录下
~~~


### 下载地址
[下载页面](https://github.com/larbing/mytv/releases/tag/v1)
