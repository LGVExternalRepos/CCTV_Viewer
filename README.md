<p align="center"> <img src="https://github.com/Eanya-Tonic/CCTV_Viewer/blob/master/app/src/main/res/drawable/icon.png" style="width:200px;" /> </p>  <h1 align="center">电视浏览器</h1>  <p align="center">一个电视机顶盒及Android TV收看电视直播的浏览器 </p>


## 下载安装包
从Github Release下载：https://github.com/Eanya-Tonic/CCTV_Viewer/releases/latest
<br>
从百度网盘下载：https://pan.baidu.com/s/1e5wMCorJIp9oi5yN8mJ1KA?pwd=qozp 提取码：qozp

## 演示视频
**B站：**

[央视浏览器v1.2更新——支持遥控器的电视直播观看软件](https://www.bilibili.com/video/BV1Gc41187D6)

[央视浏览器——一款支持遥控器的便捷电视直播观看软件](https://www.bilibili.com/video/BV1Cg4y1r7Hv)

## 使用方法
**电视盒子：**

![Screenshot_20240127-213312](https://github.com/Eanya-Tonic/CCTV_Viewer/assets/74545593/13e1c752-15e0-40bc-9a58-4138bc93dd8f#pic_center)

<div align=center><p>频道切换列表界面</p></div>

![Screenshot_20240127-213326](https://github.com/Eanya-Tonic/CCTV_Viewer/assets/74545593/4624aa07-503d-4cbf-b274-2efa5516d63c#pic_center)

<div align=center><p>菜单键功能菜单</p></div>

使用上下键切换频道，使用确认键显示当前频道和节目信息、并打开频道切换列表，单击菜单键打开功能菜单，输入数字键换到指定台，双击返回键退出程序。

**其他设备：**

使用键盘方向键上下控制切换频道，使用Enter键显示当前频道和节目信息、并打开频道切换列表，单击键盘M键打开功能菜单，输入数字键换到指定台。

## 目前可看频道 

1 CCTV-1 综合

2 CCTV-2 财经

3 CCTV-3 综艺

4 CCTV-4 中文国际（亚）

5 CCTV-5 体育

6 CCTV-6 电影

7 CCTV-7 国防军事

8 CCTV-8 电视剧

9 CCTV-9 纪录

10 CCTV-10 科教

11 CCTV-11 戏曲

12 CCTV-12 社会与法

13 CCTV-13 新闻

14 CCTV-14 少儿

15 CCTV-15 音乐

16 CCTV-16 奥林匹克

17 CCTV-17 农业农村

18 CCTV-5+ 体育赛事

19 CCTV-4 中文国际（欧）

20 CCTV-4 中文国际（美）

21 北京卫视

22 江苏卫视

23 东方卫视

24 浙江卫视

25 湖南卫视

26 湖北卫视

27 广东卫视

28 广西卫视

29 黑龙江卫视

30 海南卫视

31 重庆卫视

32 深圳卫视

33 四川卫视

34 河南卫视

35 福建东南卫视

36 贵州卫视

37 江西卫视

38 辽宁卫视

39 安徽卫视

40 河北卫视

41 山东卫视

## 更新日志

**v1.6.1 更新日志 (2024.06.06)**

1. 修复闪退的问题

**v1.6.1 更新日志 (2024.06.06)**

1. 修复无限全屏的问题

**v1.6 更新日志 (2024.06.06)**

1.【严重】无法打开地方频道

2.修复无法在程序内修改音量的问题

3.不再自动切换清晰度

4.启用网页缓存（仅系统 WebView）

5.显示系统 WebView 版本号（安卓 7及以上版本才能显示）

6.支持在 GitHub Action 构建，方便调试发版，或者魔改

7.加载网页时禁用自动加载图片，减少卡顿（仅系统 WebView）

**v1.5 更新日志（2024.01.27）**

1.更新菜单键事件逻辑，加入一个底部菜单，并取消原本复杂的双击、单击等机制，使程序更加易用。

2.修改换台菜单逻辑，将原本的弹出界面调整为二级抽屉式菜单，同时改为按确认键触发，更加符合用户的使用习惯；在打开换台界面时，自动切换到目前正在播放的频道。

3.增加一个提示，在换台时会提示目前调用的是系统Webview内核还是腾讯X5内核。

4.修复偶发性的卫视频道播放静音问题。

5.额外更新一个调用系统WebView的版本

**v1.4 更新日志（2024.01.21）**

1.增加央视频的北京卫视、江苏卫视等21个地方卫视频道。

2.尝试修复视频播放暂停的问题，暂时恢复确认键的暂停功能，但是暂停后会自动重新开始播放，仅用于增强兼容性。

3.增加双击确认键可以调整全屏/退出全屏的功能。

4.遥控器左右键可以缩放网页，增强应用兼容性。

5.修改图标、应用名称、增加leanback设置，在原生Android TV启动器上也可以正常显示图标。

6.增加频道选择界面的台号显示，方便数字键换台使用。

7.最低安装限制调整为安卓4.4，API 19。

8.本次更新中，出现了偶发性的卫视频道缩放不正常问题，经测试退出应用再重新打开后可以解决；由于较难复现，我目前不知道问题产生的原因。

**v1.3 更新日志（2024.01.20）**

1.调用本地x5内核，将x5内核集成到安装包中，提高x5内核调用的成功率。

2.自动播放视频，并且禁用确认键暂停功能。

3.修复清晰度选择导致的无法全屏和播放的问题，解决CCTV-6、CCTV-3两个频道由于没有超清清晰度无法选择导致不能全屏和正常播放的问题。 

4.增加频道选择菜单，按菜单键激活后可直接选择需要切换的频道。 

5.修改操作逻辑，按确定键显示当前频道信息、单击菜单键显示频道列表、双击菜单键刷新当前网页。 

**v1.2 更新日志（2024.01.05）**

1.在换台时显示一个“正在切换频道”覆盖层，优化使用体验

2.增加换台后当前频道和当前频道节目预告提示

3.修改按键逻辑，单击菜单键改为显示当前频道和节目信息，长按菜单键改为刷新当前页面

4.改为使用腾讯x5内核，提高程序兼容性

> 下载并安装本软件，即代表您已阅读并同意[腾讯浏览服务X5网页引擎隐私保护规则](https://rule.tencent.com/rule/preview/1c4e2b4b-d0f6-4a75-a5c6-1cfce00a390d)

**v1.1 更新日志（2024.01.04）**

1.优化返回退出逻辑，需要按两次返回键才会退出，避免误触

2.增加数字键换台功能，用户可以通过遥控器上的数字键直接输入台号换台。备注：18号 CCTV-5+ 体育赛事、19号 CCTV-4 中文国际（欧）、20号 CCTV-4 中文国际（美）

