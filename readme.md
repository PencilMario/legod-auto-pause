# ·legod-auto-pause
雷神加速器时长自动暂停

      之前的在网上的脚本发现用不了了，
      所以自己写了一个脚本放在这里。

## 下载和教程

下载地址：[点我](https://github.com/6yy66yy/legod-auto-pause/releases)

配置和使用教程：[点我](https://github.com/6yy66yy/legod-auto-pause/wiki/新手上路)

## 一、用前须知

1. 源码只是放上来看看，想要程序去[**release**](https://github.com/6yy66yy/legod-auto-pause/releases)里面下载zip（只提供exe文件）

2. 下载后先用记事本打开config.ini配置一下用户名和密码，其他配置项可选，注释很清楚

```config
[config]
# 雷神路径
path = "C:\Program Files (x86)\LeiGod_Acc\leigod.exe"
# 用户名/手机号
uname = 
# MD5加密，1为开启，0为关闭。如果开启，密码请填写MD5加密后的密码。#感谢aW3ikun完善此功能
md5 = 0
# 密码（登录后会替换为md5）
password = 
# 游戏名称（游戏程序在任务管理器中的名称）
games = GTA5,Overwatch,notepad
# 允许游戏关闭的时间（在此时间内切换游戏不会关闭加速器）单位：秒
looptime = 30
# 检测时间，多少秒检测一次程序
update = 1
# token，优先度大于密码，
# 不填会选择用户密码验证，
# 如果怕泄露密码可以自己去官网获取token
# 注意：token会过期，需要时常手动获取
account_token = 
```

3. token的优先级大于用户名密码，所以不填账户密码只填token也是可以用的

4. token会过期，如果填入用户名密码会自动获取新的token

## 二、目前已知bug：

+ 更新完token会导致config.ini的注释消失
+ 如果删除config.ini的内容并不会自动恢复，请重新下载

## 三、免责
本项目为仅为兴趣使然，边学边写，如有雷同，纯属巧合。
禁止商用！

    可以转载使用以及帮忙优化，发布时记得署名就好啦(●ˇ∀ˇ●)

## · 觉得好用给可以点个星星
## Star History

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=6yy66yy/legod-auto-pause&type=Date)](https://star-history.com/#6yy66yy/legod-auto-pause&Date)
