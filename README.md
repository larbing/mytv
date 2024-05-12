# mytv
mytv 源码


修改 Url.smali 文件  第701行
~~~ smali
.method protected static getSDKVersion()Ljava/lang/String;
    .locals 1

    .line 60
    const-string v0, "xxxxx"  #改成你的接口地址

    return-object v0
.end method
~~~

### 下载地址
[下载页面](https://github.com/larbing/mytv/releases/tag/v1)
