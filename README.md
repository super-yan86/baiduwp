# baiduwp
PanDownload Web, built with CloudFlare Workers

需要Cloudflare的Workers

复制代码粘贴到编辑器

使用查找替换找到如下内容并替换

**INPUT YOUR BDUSS HERE**

**INPUT YOUR STOKEN HERE**

顾名思义，就是替换成SVIP账号的cookie等信息，建议找一个共享号的。

先登录SVIP的网页版百度云，chrome可以使用插件EditThisCookie很方便找到相应内容。


# Demo
No longer available due to abuse.
# Usage
```
headers:{
    'user-agent': 'Some UA',
    'Cookie': 'BDUSS=INPUT YOUR BDUSS HERE; STOKEN=INPUT YOUR STOKEN HERE'
  }
```
# Thanks

[PanDownload](https://pandownload.com): static pages

[KinhDown](https://t.me/kinhdown): client type

[PNL](https://www.lanzous.com/u/pnl): download method

[acgotaku/BaiduExporter](https://github.com/acgotaku/BaiduExporter): send to aria2
