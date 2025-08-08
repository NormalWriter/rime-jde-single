# Rime 简单鹤·单字流

---

## 介绍
基于 [简单鹤](https://flauver.github.io/jdh/)词库和Could开发的[rime简单鹤](https://github.com/rimeinn/rime-JDhe)进行开发

简单鹤有着极其优秀的字根拆分，四码定长，单字低重。

但是简单鹤注重打词，所有四码单字统一在次选位，有占位符存在，无法单字四码上屏。

这么优秀的单字性能到底能不用来打单呢？

于是便有了本方案。

#### 核心
- 删除占位符
- 删除所有与四码单字重码的四码词

## 优势

追求极致的单字确认感。

四码单字上屏，如果四码出词是因为这个词没有和任何四码单字重码，所以保留了。

## 使用
先下载安装[rime简单鹤](https://github.com/rimeinn/rime-JDhe)

然后

[default.yaml](default.yaml) 

[jde_single.dict.yaml](jde_single.dict.yaml)

[jde_single.schema.yaml](jde_single.schema.yaml)

放到rime的用户目录

[block_words.lua](block_words.lua)

放到 rime用户目录/lua/

以上文件有重复的就直接替换掉

点击重新部署，等待一段时间

按 Ctrl + ` 呼出方案菜单选择「简单鹤·单字流」 即可使用!

![WX20250808-111716@2x.png](other/WX20250808-111716%402x.png)

输入yyup 云字自动上屏就是安装成功了

输入`双拼反查

![WX20250808-113013@2x.png](other/WX20250808-113013%402x.png)

更多功能移步[rime简单鹤](https://github.com/rimeinn/rime-JDhe)进行了解





