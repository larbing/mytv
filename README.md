# mytv
mytv 源码


更改 smali目录下 com\ifno\tomorrowmovies\net\Url.smali  701行
~~~ smali
.method protected static getSDKVersion()Ljava/lang/String;
    .locals 1

    .line 60
    const-string v0, "http://tv.sonainai.com/apiv2"

    return-object v0
.end method
