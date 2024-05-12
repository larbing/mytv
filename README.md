# mytv
mytv 源码


更改 smali目录下 com\ifno\tomorrowmovies\net\Url.smali  701行
~~~ smali
.method protected static getSDKVersion()Ljava/lang/String;
    .locals 1

    .line 60
    const-string v0, "xxxxx"  #改成你的接口地址

    return-object v0
.end method
~~~
