## 1.IPTV Logo 
iptv-pro 项目：该项目搜罗了几乎所有的中文电视台的 logo，在制作 m3u 文件时可以使用。https://iptv-pro.github.io/
Meroser 的 IPTV 项目：其 Logo 来源为https://github.com/wanglindl/TVlogo，这里面可能包含丰富的电视台图标资源，你可以前往该 GitHub 仓库查看具体内容。

## 2.A curated list of resources related to IPTV.
https://github.com/iptv-org/awesome-iptv

## 3.Github加速
将GitHub链接转换为多区域加速链接，解决GitHub访问慢、下载失败等问题
https://raw.githack.com/
https://gh-proxy.com/https://raw.githubusercontent.com/gqzhu9909/myiptv/refs/heads/main/ipv4.m3u

## 4.实现对多个直播源的检测，并帮助你选择出相对较快且稳定的直播源
https://github.com/zhimin-dev/iptv-checker/releases/tag/v4.1.7
https://github.com/Guovin/iptv-api/releases/tag/1.7.3

## 5.直播源相关资源汇总
https://github.com/imDazui/Tvlist-awesome-m3u-m3u8

## 6.关于my-tv
my-tv是一个基于模块化通信架构的电视应用，其通信系统设计遵循了高效、安全和易于维护的原则。在my-tv中，数据加密是通过自定义加密工具Encryptor.kt实现的，该工具提供了AES和RSA混合加密方案，确保敏感数据在传输过程中的安全性。AES加密在my-tv中用于保护数据不被未授权访问，它与JCE（Java Communication Engine）协议结合使用，用于二进制数据的序列化与反序列化。此外，my-tv的加密机制还包括使用Retrofit构建RESTful API服务，以实现直播信息获取和用户认证等功能。在my-tv的通信架构中，Encryptor.kt负责执行加密操作，而JceInputStream.java则负责解码逻辑，支持多种基础数据类型和复杂结构体的解析。整个系统通过统一的API管理和全局异常处理策略来增强数据安全性和系统稳定性。开发者在使用my-tv的模块化通信方案时，可以参考这些设计原则，以构建安全且易于维护的TV应用通信系统。
