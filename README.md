# Sonimei
音乐搜索器 - 多站合一音乐搜索安卓解决方案
[网页版](http://www.jbsou.cn/)

## 说明

#### 感谢[麦葱](https://github.com/maicong/music)提供的网页版、接口和服务器支持。

支持搜索试听以下网站音乐：

[网易云音乐](http://music.163.com) [QQ音乐](http://y.qq.com) [酷狗音乐](http://www.kugou.com) [酷我音乐](http://www.kuwo.cn) [虾米音乐](http://www.xiami.com) [百度音乐](http://music.baidu.com) [一听音乐](http://www.1ting.com)
 [咪咕音乐](http://music.migu.cn) [荔枝FM](http://www.lizhi.fm) [蜻蜓FM](http://www.qingting.fm) [喜马拉雅FM](http://www.ximalaya.com) [全民K歌](http://kg.qq.com) [5sing原创](http://5sing.kugou.com/yc) [5sing翻唱](http://5sing.kugou.com/fc)

数据调用的是各网站的 API 接口，有的接口并不是开放的，随时可能失效，本项目相关代码仅供参考。


## API doc
||多站合一音乐搜索接口|
| --- | --- |
|url|http://www.jbsou.cn/ |
|method|post|
|请求头|Ajex请求（必传）|
|X-Requested-With|XMLHttpRequest|
|参数列表||
| input | 搜索内容（音乐名称/音乐id/音乐地址） |
| type  | 音乐来源① |
| filter | name/id/url（与input类型对应）|
| page | 页码数量（搜索音乐名时有效）|

> 备注：

```
1、type 音乐来源 支持平台（netease，qq，kugou，kuwo，xiami，baidu，1ting，migu，lizhi，qingting，ximalaya，kg，5singyc，5singfc）
```


#### 编译报(xxx/Java/sonimei/key.properties (No such file or directory))错误怎么办
```
在项目根目录新建文件key.properties，内容如下：
storePassword=
keyPassword=
keyAlias=
storeFile=签名路径
buglyAppId=buglyId
buglyAppKey=buglyAppKey
umengAppKey=umengAppKey
------------------
等号后的内容可以随便填
```


## 免责声明

1. 音频文件来自各网站接口，本应用不会修改任何音频文件
2. 音频版权来自各网站，本应用只提供数据查询服务，不提供任何音频存储和贩卖服务

-----

#### 本项目仅供学习交流，禁止二次打包上传
