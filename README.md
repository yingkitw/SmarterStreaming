# SmarterStreaming
国内外为数不多不依赖开源框架、不依赖CDN实现秒开、公网毫秒级延迟、跨平台(windows/android/iOS)rtmp推流、rtmp/rtsp直播播放利                 器"SmarterStreaming"，系daniulive(大牛直播)出品的跨平台视频采集、直播SDK(支持rtmp推流/rtmp播放/rtsp播放，如windows推流(windows pusher)/android推流(android pusher)/iOS推流(iOS pusher)/windows播放器(windows player)/android播放器(android player)/iOS播放器(iOS player))，也许是最靠谱的视频直播推流、播放SDK之一，助您轻松实现类似于花椒、映客、斗鱼手机直播推送与播放。

===========================
SmarterStreaming, which is an excellent cross-platform Live Streaming publisher/playback SDK, based on RTMP/RTSP protocol, developed by daniulive.

Currently, it has already covered Windows/android/iOS platform with millisecond latency and great scalability.

***For commercial support, please contact 89030985@qq.com.***

<img src="http://218.25.89.108:8080/files/image/SmarterStreaming.png" width="313" alt="SmarterStreaming" />

**Android publisher/iOS publisher**

- [x] Audio encoding: AAC;
- [x] Video encoding: H.264;
- [x] Protocol: RTMP;
- [x] Different resolution settings;
- [x] Front and back camera switching;
- [x] Stream adaptive;
- [x] Software/Hardware encoding;
- [x] Low latency and automatic network connection.
- [x] Push audio only;
- [x] Push video only;
- [x] real-time mute/un-mute;
- [x] YUV interface before encoding;
- [x] AAC interface after encoding;
- [x] H.264 interface after encoding;

**windows player/android player/iOS player**

- [x] Audio decoding: AAC/G.711;
- [x] Video decoding: H.264;
- [x] Protocol: RTMP/RTSP;
- [x] Support RTSP TCP / UDP mode switch;
- [x] Support buffer settings;
- [x] support for customized layout;
- [x] Multi-mode of audio/video render mechanism;
- [x] Real-time mute/unmute;
- [x] Support software/hardware decoding;
- [x] Perfectly support multi-instance playback(even playback rtmp/rtsp stream at the same time);

**[SmarterStreaming SDK调用说明]**

[点击查看](http://daniulive.com:8080/files/SDK/SmarterStreaming SDK调用说明.pdf)

**NOTE：**很多开发者反应，由于项目庞大，github下载整个工程很慢，我们已经把相关demo文件和使用说明，全部上传到QQ群共享，下载有困难的同学，可以到QQ群(**大牛直播技术交流群1: [499687479](http:////shang.qq.com/wpa/qunwpa?idkey=e7686f68a39bf1b95dc2ac3b775867efc7d3cbaf3596daf6e12bc1df21e1dc59), 大牛直播技术交流群2: [294891451](http://shang.qq.com/wpa/qunwpa?idkey=476a9cc05db0b2924530ccbbf4fae78fa485d39418ef79c8ab71b24a8fee8a48)**)查看群共享文件。

**[Windows版RTMP/RTSP直播播放器下载]**

为了方便大家调试和产品对比，我们开放了Windows版的RTMP/RTSP直播播放器（Video：H.264/Audio: AAC, G.711），欢迎下载使用（支持buffer设置（0~10000ms）、RTSP(TCP/UDP设置)、实时静音/取消静音），也可能是最好用的**Windows RTMP/RTSP播放器**。

[点击下载](http://daniulive.com:8080/files/daniulive/windows-rtmp-rtsp-开放版-smartplayer-2016-12-20.zip)

**[Android后台推送摄像头/屏幕数据]**

SmartServicePublisherSDKDemo(考虑到特定用户需求，我们发布了后台service采集摄像头/屏幕数据的demo).

[点击下载](http://daniulive.com:8080/files/daniulive/SmartServicePublisher.zip)

1. 安装SmartServicePublisherSDKDemo；
* [推送类型] 可选“推送屏幕”或“推送摄像头”；
* [推送屏幕] 分辨率分“屏幕标准分辨率”和“屏幕低分辨率”；
* [推送摄像头] 分“摄像头高分辨率”、“摄像头中分辨率”、“摄像头低分辨率”、“摄像头超高分辨率”;
* [录像功能] 默认“本地不录像”，如需录像，请选择下来菜单“本地录像”；
* [录像管理] 针对录像数据的回放、删除等操作；
* [前后置摄像头选择] 默认后置摄像头，如需采集前置摄像头，请点击按钮，切换前后摄像头；
* [输入推流URL] 默认我们会自动随机生成推送到我们server的url，如需推送到自己server，请自行设置，并点击“确认”生效；
* [软硬编码切换] 默认软编码，如需硬编码，请点击此按钮选择；
* [推屏权限检测] 由于android屏幕采集需要android 5.0以上版本，如推送屏幕数据，需要先检测推屏权限，如检测通过，才可以推流；
* [开始推流] 推送数据到server端， 点击“开始推流”后，可切换到后台，采集屏幕或者摄像头数据，如需停止推送，点级"停止推送"按钮就可，NOTE: 开始推送后，后台会进入一直推流状态，测试结束后，记得点击“停止推送”。

===========================
# 功能支持
**[一对一实时音视频互动]**

- [x] 基于P2P或流媒体转发的一对一音视频互动产品；
- [x] 以秀场、在线教育、远程诊疗、智能门禁等为核心的跨平台音视频实时互动。

**[一对多，多对多直播、互动]**

适用于秀场直播、在线教育、应急指挥、可视化购物、远程专家指挥系统、企业内训、金融在线直播室、微信直播、监控对接、活动现场直播、游戏直播等场景。

**windows推流**

- [x] 摄像头采集；
- [x] 屏幕采集。

**windows播放器**

- [x] 基于C C++开发的低延迟低资源占用的windows cs架构的播放器（exe），支持RTSP/RTMP协议封装；
- [x] 基于flash控件开发的web播放器。

**android推流/iOS推流**

- [x] 多分辨率选择；
- [x] 支持横竖屏推送；
- [x] `音视频`推送、`纯音频`推送、`纯视频`推送；
- [x] 支持`边采集、边录像`；
- [x] 网络中断，本地录像继续，保证数据的完整性；
- [x] 支持本地录像文件回放、处理；
- [x] 采集过程中，前后摄像头切换；
- [x] 提供编码前(YUV/RGB)、编码后音视频(H.264/AAC)接口对接，方便AR/VR设备调用。
- [x] iOS自带美颜功能；
- [x] android完美支持`文字水印、实时时间水印和图片水印`；
- [x] 支持`推送端实时静音/取消静音`；
- [x] 支持软硬编码自适应；
- [x] android支持后台service推送摄像头或屏幕(推送屏幕需要5.0+版本)；
- [x] 完美支持各个厂家CDN。

**windows播放器/android播放器/iOS播放器**

- [x] 超低延迟的rtmp播放器；
- [x] 超低延迟的rtsp播放器；
- [x] 完美支持多实例播放（同时播放多路stream，可同时支持rtmp、rtsp stream播放）；
- [x] 支持RTSP TCP/UDP模式切换；
- [x] 支持播放端，buffer设置；
- [x] 支持自定义播放布局;
- [x] 音视频多种render机制;
- [x] 支持播放过程中，'实时静音/取消静音';
- [x] android/iOS支持软硬解码，业内真正靠谱的超低延迟、低资源占用播放rtsp/rtmp 1080p+。

**微信播放**

- [x] 支持android设备rtmp/hls播放；
- [x] 支持iOS设备hls播放；
- [x] 支持公众号集成。
 
公网环境下，**毫秒级延迟**，支持云服务部署、各类厂商的CDN产品对接；

支持**边推送边录像**（如执法记录或移动单兵场景），网络中断仍可继续录制，结束后可本地回放，并可对接第三方云服务，把录像数据保存到云端服务器；

支持跨平台**纯音频、纯视频、音视频推送**、**纯音频、纯视频、音视频播放**、**纯音频、纯视频、音视频实时存储**。

**[基于RTMP、RTSP安防摄像机、编码器、智能眼镜平台对接]**

无论rtsp、rtmp，我们提供高稳定性、超低延迟的跨平台（Windows/android/iOS）综合视频监控系统对接。

**[多对一实时通讯]**

适用于应急指挥、公安巡检等，以移动单兵设备为采集载体，实时上传音视频数据到指挥中心，并实现指挥中心对现场的实时指导。

您可以用网页进行播放测试：<a href="http://daniulive.com:8080/files/SmartPlayer/SmartPlayer.html" target="_blank">http://daniulive.com:8080/files/SmartPlayer/SmartPlayer.html</a>

**[SmarterStreamServer]**

- [x] 高并发，分布式部署，支持rtmp摄像机和采集设备完美对接，提供代建服务器或整套软硬件服务器方案；
- [x] 高性能的流媒体服务器，标准rtmp输入，多种方式流输出（rtmp/hls），并同步保存采集端数据；
- [x] 支持鉴权认证、各种信息展示；
- [x] 点播服务器：满足录像文件点播需求。

**SmarterStreaming SDK可供个人学习之用，企业及商用需要经过授权**；

## 公网环境下推流、直播效果展示 ##
<img src="http://daniulive.com:8080/files/image/windows_publisher.JPG" width="800" alt="Windows采集，跨平台播放" />

<img src="http://daniulive.com:8080/files/image/AndroidPublisher.JPG" width="800" alt="Android采集，跨平台播放" />

<img src="http://daniulive.com:8080/files/image/IOSPublisher.png" width="800" alt="iOS采集，跨平台播放" />

## 播放展示 ##

**1. Windows播放器：**

<img src="http://daniulive.com:8080/files/image/windowsplayer.jpg" width="600" alt="大牛直播Windows播放器" />

**2. Android播放器：**

<img src="http://daniulive.com:8080/files/image/android.jpg" width="600" alt="大牛直播android播放器" />

**3. iOS播放器：**

<img src="http://daniulive.com:8080/files/image/ios_player.jpg" width="600" alt="大牛直播iOS播放器" />

**4. 海思板子（4核低端版，同时播放4路720P rtmp流）：**

<img src="http://daniulive.com:8080/files/image/box.png" width="800" alt="海思box播放" />

## android推流端/iOS推流端 ##

**1. android边推送边录像(支持纯音频推送和播放)：**

<img src="http://daniulive.com:8080/files/image/android_publisher.jpg" width="600" alt="android边推送边录像" />

<img src="http://daniulive.com:8080/files/image/watermark.jpg" width="600" height="750" alt="windows播放水印推流" />

**2. iOS边推送边录像(支持纯音频推送和播放)：**

<img src="http://daniulive.com:8080/files/image/iOS_publisher.jpg" width="600" alt="iOS边推送边录像" />

<img src="http://daniulive.com:8080/files/image/iOS_publisher_2.jpg" width="600" alt="iOS边推送边录像2" />

**3. iOS录像管理：**

<img src="http://daniulive.com:8080/files/image/iOS_recorder.JPG" width="600" alt="iOS录像管理" />

## SmarterStreamServer url鉴权demo ##

<img src="http://daniulive.com:8080/files/image/url_generate.png" width="798" alt="url生成demo" />

## 使用说明 ##

**1. 推流:**

**1.1 Windows推流：**

选择“WindowsPusher&Player”文件，打开“SmartClientDemo.exe”（如需推送桌面，请使用SmartClientDeskDemo.exe，默认会采集PC屏幕左上角一块区域），进入系统后，左侧系推流端，右侧是播放端，推流依次点击:

1. Open;
* Login（输入用户名、密码)，如需Windows端推流测试，请联系QQ 89030985，或加入QQ群 499687479 和群主联系;
* 输入用户名、密码之后，会自动根据用户名生成对应的播放URL，如用户名daniulive，则生成的url为：rtmp://daniulive.com:1935/hls/streamdaniulive;
* 点击PushStream，完成Windows推流。

PushStream，如推流成功的话，会显示推流地址，如本URL对应的链接为：
rtmp://daniulive.com:1935/hls/streamdaniulive.

**1.2 Android推流：**

1. 安装SmartPublisher；
* [推流类型] 可选择推“纯音频”、“纯视频”、“音视频”；
* [水印类型] 可选择“图片水印”、“文字水印”、“全部水印”、“不加水印”；
* [分辨率] 可选择高、中、低、超高分辨率
* [录像] 可选择“本地录像”或不录像，如选择“本地录像”，支持边推流边录像；
* [录像管理] 可进入录像页面，比如，进行录像回放、文件管理；
* [静音] 支持推送过程中，主播端实时静音或取消静音；
* [硬编码/软编码] 默认软编码，如需硬编码，系统自动检测是否支持，如支持，优先采用硬编码；
* [输入推流URL] 可自定义推送url，如不输入，默认自动生成url，推送到daniulive服务器；
* [开始推流] 点击后，推送数据到流媒体服务器，如需停止，点击“停止推流”；
* [前后摄像头切换] 推流过程中，可点击前后摄像头切换图标，前后采集源。

**1.3 iOS推流：**

1. 安装SmartPublisher；
* [分辨率] 可选择高、中、低、超高分辨率；
* [推流类型] 可选择推“纯音频”、“音视频”、“纯视频”；
* [美颜] iOS推送端支持推送过程中，美颜设置，也可选择不美颜；
* [录像] 可选择“边推边录”或不录像，如选择“边推边录”，支持边推流边录像；
* [进入推流页面] 1~5步骤完成后，可进入推流页面；
* [进入回放页面] 可进入录像页面，比如，进行录像回放、文件管理；
* [静音] 支持推送过程中，主播端实时静音或取消静音；
* [美颜] 支持几种常规美颜；
* [前后摄像头切换] 推流过程中，可点击前后摄像头切换图标，前后采集源；
* [推流] 点击后，推送数据到流媒体服务器，如需停止，点击“停止”；
* [返回] 未推流状态，返回上层设置页面。
 
**1.4 iOS端边推流边录像：** 

1. [录像相关]设置推流过程中，是否录像（不录像 边推边录）；
* [录像相关]如有边推送边录像，直播结束后，点击“进入回放页面”，可显示录像文件名称，点击回放，可进行本地录像回放；
* [录像相关]点击“删除全部文件”，可删除本地录制的所有文件；
* [录像相关]回放过程中，点击“暂停”，进入播放暂停状态，点击“恢复”继续播放。

**2 播放：**

**2.1 Windows播放器：**

播放器下载：[点击下载](http://daniulive.com:8080/files/daniulive/windows-rtmp-rtsp-开放版-smartplayer-2016-11-24.zip)

1. 打开SmartPlayer.exe；
* 根据提示，在RTMP/RTSP播放地址处，输入需要播放的url，如“rtmp://live.hkstv.hk.lxdns.com/live/hks”；
* 在播放之前，可以设置缓冲时间（单位：毫秒），支持0~10000ms设置；
* 如果播放rtsp url，可以设置使用TCP/UDP播放；
* 播放过程中，可选择实时静音/取消静音。

**2.2 android播放器**

1. 安装SmartPlayer.apk；
* [大牛直播url] 进入系统后，在输入框输入“urlID”，stream后的部分(如“rtmp://daniulive.com:1935/hls/stream123456”,那就输入“123456”)，点击“进入播放页面”即可，停止的话，点击“返回”按钮，返回主页面，可重新选择其他url播放；
* [纯音频url] 如需播放纯音频，编译工程，SmartPlayerSetSurface第二个参数设置为null；
* [输入完整url] 如需测试自己服务器或者公网rtsp/rtmp的url，点击“输入完整url”，比如“rtmp://live.hkstv.hk.lxdns.com/live/hks”，在弹出框输入想播放的url；
* [开始播放/停止播放] 输入播放url后，可以点击开始播放，如需停止，点击停止播放按钮即可；
* [rtsp播放] rtsp模式下，支持TCP/UDP模式切换；
* [静音功能] 无论播放rtmp还是rtsp，播放过程中，可以实时静音/取消静音；
* [软解码/硬解码]播放页面，默认会显示“当前软解码”，如需用硬解码，请点击此按钮，页面会显示“当前硬解码”，点击开始播放，会以页面当前显示的软解或硬解运行。

**2.3 iOS播放器**

1. 安装SmartPlayer.ipa；
* [大牛直播url] 进入系统后，在输入框输入“urlID”，stream后的部分(如“rtmp://daniulive.com:1935/hls/stream123456”,那就输入“123456”)，点击“进入播放页面”即可，停止的话，点击“返回”按钮，返回主页面，可重新选择其他url播放；
* [纯音频url] 如需播放纯音频，请选择“纯音频”选项，然后，输入urlID，进入播放状态；
* [软解码/硬解码]如需用硬解码，请选择“硬解”，然后进入播放页面；
* [rtsp播放] 如需测试rtsp url，请编译工程，设置全的url即可；
* [rtsp播放] rtsp模式下，支持TCP/UDP模式切换；
* [静音功能] 无论播放rtmp还是rtsp，播放过程中，可以实时静音/取消静音；
* [返回] 播放另外一个url，点击返回按钮，到上级页面。

**2.4 Web播放器**

http://player.daniulive.com:8080/files/SmartPlayer1Stream/SmartPlayer.html

在输入框中，清除老的url，输入推流的url，如 rtmp://daniulive.com:1935/hls/stream123456（以推流端生成的URL为准）。

**[上层源码目录]**

1. android推流 SmartPublisher
https://github.com/daniulive/SmarterStreaming/tree/master/SourceCode/Android/SmartPublisher

2. android播放器 SmartPlayer:
https://github.com/daniulive/SmarterStreaming/tree/master/SourceCode/Android/SmartPlayer

3. iOS推流 SmartPublisher:
https://github.com/daniulive/SmarterStreaming/tree/master/SourceCode/IOS/SmartiOSPublisher

4. iOS播放器 SmartPlayer:
https://github.com/daniulive/SmarterStreaming/tree/master/SourceCode/IOS/SmartiOSPlayer

**[编译注意事项]**

1. 编译时找不到 libSmartPlayerSDK.a 时，请先到 SmartiOSPlayer/SmartiOSPlayer/libs 目录, 解压libSmartPlayerSDK.zip.
* 编译时找不到 libSmartPublisherSDK.a 时，请先到 SmartiOSPublisher/SmartiOSPublisher/libs 目录, 解压libSmartPublisherSDK.zip.
* iOS 需真机调试。
* 未授权版本，限制app-name，如果需要集成到自己工程里面调试，可以用以下名字：
 * android推送端：SmartPublisherSDKDemo
 * android后台Service推送：SmartServicePublisherSDKDemo
 * android播放器：SmartPlayerSDKDemo
 * iOS推送端：SmartiOSPublisher
 * iOS播放器：SmartiOSPlayer

## 获取更多信息 ##

商务合作：QQ：89030985 
技术支持：QQ: 2679481035

QQ群(大牛直播技术交流群1)：[499687479](http:////shang.qq.com/wpa/qunwpa?idkey=e7686f68a39bf1b95dc2ac3b775867efc7d3cbaf3596daf6e12bc1df21e1dc59)

<img src="http://daniulive.com:8080/files/image/erweima.png" width="302" alt="QQ交流群" />

QQ群(大牛直播技术交流群2 精英群)：[294891451](http://shang.qq.com/wpa/qunwpa?idkey=476a9cc05db0b2924530ccbbf4fae78fa485d39418ef79c8ab71b24a8fee8a48)

<img src="http://daniulive.com:8080/files/image/erweima2.png" width="302" alt="QQ交流群" />

想了解更多信息，点击 
[大牛直播十万个为什么](https://github.com/daniulive/SmarterStreaming/wiki/%E5%A4%A7%E7%89%9B%E7%9B%B4%E6%92%AD%E5%8D%81%E4%B8%87%E4%B8%AA%E4%B8%BA%E4%BB%80%E4%B9%88)
