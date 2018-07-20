## DevTool
Mac OS X 10.9以上 开发调试小工具

[不需要代码，点击直接下载安装包](https://github.com/MxABC/Resource/blob/master/DataHandler.zip)


#### 当前完成

1. base64
2. hash(MD5,SHA1,SHA256,SHA3,SM3,HMAC)
3. 对称加解密(DES,3DES,AES,SM4)
`支持分组加密模式有： ECB、CBC、PCBC、CFB、OFB、CTR`
`填充方式(分组不足补位)有：PKCS7、zero、ANSIX923、ISO10126、0x80等`
4. der,cer证书文件解析

![image](https://github.com/MxABC/Resource/blob/master/macApp.jpg)


#### cocoapods安装
包含base64,数据转换，摘要算法，对称加解密

```
  pod 'LBXDataHandler',git:'https://github.com/MxABC/DevDataTool.git',tag:'1.0.1'
```

