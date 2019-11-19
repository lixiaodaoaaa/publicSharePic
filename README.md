# publicSharePic
分享图片，以github为图床的图片。生成image

## 参考这里 《PicGo + GitHub 搭建个人图床工具》

地址：[PicGo + GitHub 搭建个人图床工具](https://blog.csdn.net/yefcion/article/details/88412025)

版权声明：本文为博主原创文章，遵循 CC 4.0 BY-SA 版权协议，转载请附上原文出处链接和本声明。
本文链接：https://blog.csdn.net/yefcion/article/details/88412025
取代 七牛云+Mpic 方案

写在前面

    我以前用的 七牛云 + Mpic 的组合，后来由于七牛云测试域名收回，我的图床就废了。以前的好多图片都埋藏在七牛云的服务器上，又气又难过。思考好一段时间，想自己搭服务，但成本有点高，备案的域名 + 服务器一年几百块。对于我这种不靠写字谋生的人而言没有必要，所以就停摆了一段时间。直到今天用 GitHub 搭起了图床，可以说非常开心了。所以跟大家分享一下。

    方便程度：★★★★☆
    配置难度：★★☆☆☆
    适用环境：win + mac + linux
    需要工具：GitHub 账号 + PicGo 客户端
    稳定性：背靠 GitHub 和微软，比自建服务器都稳
    隐私性：这算是唯一缺点，你的图片别人可以访问

1. GitHub 仓库设置

    流程：新建 public 仓库 -> 创建 token -> 复制 token 备用

1.1 新建仓库

点击 git 主页右上角的 + 创建 New repository；

1.2 创建 token 并复制保存

此时仓库已经建立，点击右上角头像，然后进入设置；

在页面最下找到 Developer settings，点击进入；

创建 token；


2. PicGo 客户端配置

