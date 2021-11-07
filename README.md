# 阿里云盘小白羊版

#### 项目说明

这是我个人基于阿里云盘网页版开发的PC客户端，支持win7-11 32位/64位，macOS，linux

> **11.07：[v2.11.07版已发布](https://github.com/liupan1890/aliyunpan/issues/363)，可以尝鲜了**

  <br />
  
v1.6.29：[https://wwe.lanzoui.com/b01npsg8h](https://wwe.lanzoui.com/b01npsg8h)

v2.11.07：[https://wwe.lanzoui.com/b01nqc4gd](https://wwe.lanzoui.com/b01nqc4gd)

MacOS：[https://www.macwk.com/soft/aliyun-drive-xiaobaiyang](https://www.macwk.com/soft/aliyun-drive-xiaobaiyang)

Mac版由macwk.com使用自有签名打包dmg，可以简单点击安装了(不需要输入终端命令)，推荐下载此版本，已测MacOS10.12-11.4,兼容M1
<br />

已经发布在小众软件发现频道，大爱小众[meta.appinn.net](https://meta.appinn.net)

<br />

``````
2021年10月31日 已完成功能：
多账号登录、常用文件操作（新建文件夹、收藏、重命名、复制、移动、删除、详情、视频雪碧图）、
MPV 播放视频、在线预览图片、在线预览文本、上传文件、上传文件夹、批量改名、在线解压、
回收站、收藏夹、连接到远程 Aria2 下载、导入阿里云分享链接、在线预览 word/excel/ppt/pdf、缩略图列表

等待完成的功能：
相册功能、网盘和相册间文件互相复制、分享文件、聚合搜索、网盘内文件搜索、文件同步盘、重复文件扫描、帐号间文件复制
``````

<br />

#

![Image](https://raw.githubusercontent.com/liupan1890/aliyunpan/main/v2.10.19.png)

#

#### 为什么要用小白羊？

#### 一：因为更快

##### 上传和下载4.4万个json格式小文件（共24GB）:	

| 程序 | 总用时 | 用时基准 |
| --- | ---: | ---: |
| 上传&小白羊版 v2.10 | 24分钟 | :zap:58% |
| 上传&PC客户端 v2.2.6 | 41分钟 | 100% |
|  ... |  |  |  |  |
| 下载&小白羊版 v2.10 | 25分钟 | :zap:42% |
| 下载&PC客户端 v2.2.6  | 59分钟 | 100% |


##### 上传和下载33个大文件（共90GB）:

| 程序 | 总用时 | 用时基准 |
| --- | ---: | ---: |
| 上传&小白羊版 v2.10 | 1分10秒 | :zap:44% |
| 上传&PC客户端 v2.2.6 | 2分40秒 | 100% |
|  ... |  |  |  |  |
| 下载&小白羊版 v2.10 | 38分钟 | :zap:52% |
| 下载&PC客户端 v2.2.6 | 72分钟 | 100% |

<br/>

详情参阅 ：[v2.10.19性能测试](https://github.com/liupan1890/aliyunpan/blob/main/v2.10.19%E6%80%A7%E8%83%BD%E6%B5%8B%E8%AF%95.md) 的性能测试文档

#### 二：因为更好

小白羊支持同时登录多个账号管理

小白羊特有文件夹树，可以快速方便的操作

小白羊支持直接在线播放网盘里的各种格式的视频并且是高清原画，支持外挂字幕/音轨/播放速度调整，比官方的格式更多更清晰

小白羊可以显示文件夹体积，可以文件夹和文件混合排序(文件名/体积/时间)，并且文件名排序时更准确！

小白羊可以通过远程Aria2功能把文件直接下载到远程的VPS/NAS上

小白羊可以批量的对 大量文件/多层嵌套的文件夹 一键重命名

小白羊可以快速复制文件，可以直接预览视频的雪碧图，可以直接删除文件

小白羊支持数万文件夹和数万文件的管理，支持一次性列出文件夹里包含的全部文件

小白羊仍在努力开发新功能，让大家使用起来更方便！


#

#### 常见问题
**1.Mac系统下载后提示：已损坏，您应该将它移到废纸篓？**

答：这是因为苹果系统要求程序被证书签名，一年688元，我没有买。请参照此链接方式二操作即可
https://blog.csdn.net/H_Zaiii/article/details/105730557

**2.怎样版本更新？怎样彻底卸载？**

答：版本更新：删除旧文件，下载新版解压即可。彻底卸载：删除小白羊的文件夹，删除C:\Users\用户名\AppData\Roaming\alipay这个文件夹即可

**3.可以选择多个文件后批量操作吗？**

答：当然可以，<br />
1.支持点击文件名前面的勾选按钮多选<br />
2.支持点击区间选择后，批量拖选<br />
3.支持配合Ctrl键、Shift键，实现自由选中多个文件，跟win10文件管理器多选操作是一样的<br />

**4.可以指定把文件下载到哪里吗？**

答：可以，<br />
在设置里可以选择下载保存的位置，<br />
默认的是按照阿里云盘的完整路径保存的，<br />
在设置里也可以去掉阿里云盘的完整路径直接保存


**5.可以一次下载整个文件夹吗？可以一次上传整个文件夹吗？支持断点续传吗？**

下载：可以批量下载多个文件夹，没有文件数量的限制！下载文件时也支持断点续传，可以随时暂停恢复继续下载

上传：直接拖动要上传的文件夹扔到小白羊窗口上就可以了！也可以点击上传按钮选择文件夹！没有上传数量的限制！支持单个体积几百GB的大文件，上传文件时支持秒传，支持断点续传，可以随时暂停恢复继续上传！

**6.支持在线预览哪些文件？**

1.支持预览所有的音视频格式（阿里云盘只支持部分常见视频格式，小白羊可以通过电脑上的播放器播放更多的格式）<br />
2.支持在线预览图片<br />
3.支持在线预览word/excel/ppt/wps/pdf/txt<br />
4.支持在线预览200多种格式的文本类型文件(.cpp .js .ini .csv ......)<br />



