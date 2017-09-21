# open_source_team
## 概述
想跟着大神走吗,想学习大神的步伐吗,想使自己的项目变得简单吗,那就看一看个大公司团队的代码吧,下面主要写的就是各大公司团队的开源地址,可以尽情的学习,现在是单纯的中国的团队,有时间把外国的团队补上,欢迎持续关注,欢迎 "Star"

## 此页面会持续更新, 如果您发现还有的团队可以提出来告诉我

## 目录(中国)
## 外国的团队地址请看[外国](https://github.com/niezhiyang/open_source_team/blob/master/%E5%A4%96%E5%9B%BD.md)

### 1.阿里巴巴
#### 1.1  [阿里巴巴主团队](https://github.com/alibaba/)
 主要开源的大项目真的太多了，那我就找几个主要的大项目说一下把
 - [weex](https://github.com/alibaba/weex)   star 14.9k<br>      Weex能够完美兼顾性能与动态性，让移动开发者通过简捷的前端语法写出Native级别的性能体验，并支持iOS、安卓、YunOS及Web等多端部署.简单来说,一段代码可以在任何设备上跑,如果这个你没有听说过的话,那你应该听说过React Native吧,这个跟React Native相差不大,但是Facebook前几天出了一个条例,基本上大公司都已经放弃React/React Native了,再说句题外话,Google还未正式发布的[Flutter](https://github.com/flutter/flutter),跟weex和React Native有异曲同工之妙,但我感觉Flutter将来会火(纯属个人想法)
 - [fastjson](https://github.com/alibaba/fastjson)  star 10.7k<br>
 Fastjson是一个Java语言编写的高性能功能完善的JSON库,速度最快，测试表明，fastjson具有极快的性能，超越任其他的Java Json parser。包括自称最快的JackJson；功能强大，完全支持JavaBean、集合、Map、日期、Enum，支持范型，支持自省；无依赖，能够直接运行在Java SE 5.0以上版本；支持Android；开源 (Apache 2.0) 
 - [dubbo](https://github.com/alibaba/dubbo)   star 11.4k<br>Dubbo是阿里巴巴公司开源的一个高性能优秀的服务框架，和spring框架无缝集成.Dubbo是一个分布式服务框架，致力于提供高性能和透明化的RPC远程服务调用方案，以及SOA服务治理方案。简单的说，dubbo就是个服务框架，如果没有分布式的需求，其实是不需要用的，只有在分布式的时候，才有dubbo这样的分布式服务框架的需求。
 -  [druid](https://github.com/alibaba/druid)   star 7.9k<br>用官网github的一句话总结:Druid是Java语言中最好的数据库连接池。Druid能够提供强大的监控和扩展功能。
   
 
#### 1.2  [阿里巴巴前端团队](https://github.com/thx)
  -  [RAP](https://github.com/thx/RAP)   star 6.2k<br>用官网上的总结:Web接口管理工具，开源免费，接口自动化，MOCK数据自动生成，自动化测试，企业级管理。阿里妈妈MUX团队出品！阿里巴巴都在用！1000+公司的选择！一直被抄袭，从未被超越
  
  
### 2.腾讯
 #### 2.1 [AlloyTeam](https://github.com/AlloyTeam) 
 -  [AlloyImage](https://github.com/AlloyTeam/AlloyImage)   star 1.7k<br>AlloyImage是一个使用Javascript语言开发的项目，在Web的在线图像处理引擎的基础上，不仅仅是核心底层图像处理引擎，同样还集成了一些方便快捷的图像处理API，您可以将它简单快捷的引用到您的Web网页中，做出与PhotoShop一样的优美效果。甚至，你可以用AlloyImage来开发一个Web在线图像处理软件，如：Web版的PhotoShop——AlloyPhoto 
 -  [Mars](https://github.com/AlloyTeam/Mars)  star  5.7k<br>腾讯移动Web前端知识库,在这里可以找到前端的任何知识,不过最近7个月都没有更新了
   
 
 #### 2.2 [微信团队](https://github.com/tencent-wechat) 好像此地址已经作废
 -  [libco](https://github.com/tencent-wechat/libco) star  2.7k<br> 这个项目地址已经移址[libco](http://github.com/Tencent/libco)<br>libco是微信后台大规模使用的c/c++协程库，2013年至今稳定运行在微信后台的数万台机器上。无需侵入业务逻辑，把多进程、多线程服务改造成协程服务，并发能力得到百倍提升;支持CGI框架，轻松构建web服务(New);支持gethostbyname、mysqlclient、ssl等常用第三库(New);可选的共享栈模式，单机轻松接入千万连接(New);
 
 
 #### 2.3 [主团队](https://github.com/tencent)
这个开源团队的项目也非常多,就列出几个重大的开源地址吧
-  [tinker](https://github.com/Tencent/tinker) star  10.1k<br>Tinker是微信官方的Android热补丁解决方案，它支持动态下发代码、So库以及资源，让应用能够在不需要重新安装的情况下实现更新。当然，你也可以使用Tinker来更新你的插件,同样热修复的框架还有[QZone](),[AndFix](https://github.com/alibaba/AndFix),[Robust](https://github.com/Meituan-Dianping/Robust)
-  [VasSonic](https://github.com/Tencent/VasSonic) star 5.6k(大约2017年7月开源的) <br>VasSonic取名于世嘉游戏形象音速小子，俗称H5首屏秒开,支持android,ios,后端.是腾讯VAS(SNG增值产品部QQ会员)团队研发的一个轻量级的高性能的Hybrid框架，专注于提升页面首屏加载速度，完美支持静态直出页面和动态直出页面，兼容离线包等方案。该框架使用终端应用层原生传输通道取代系统浏览器内核自身资源传输通道来请求页面主资源，在移动终端初始化的同时并行请求页面主资源并做到流式拦截，减少传统方案上终端初始化耗时长导致页面主资源发起请求时机慢或传统并行方案下必须等待主资源完成下载才能交给内核加载的影响。
-  [wcdb](https://github.com/Tencent/wcdb) star 4k(2017年6月2号开源的)<br>WCDB 是一个高效、完整、易用的移动数据库框架，基于 SQLCipher，支持 iOS、macOS 和 Android。
-  [angel](https://github.com/Tencent/angel) star 2.4k<br>Angel是一个基于参数服务器（Parameter Server）理念开发的高性能分布式机器学习平台，它基于腾讯内部的海量数据进行了反复的调优，并具有广泛的适用性和稳定性，模型维度越高，优势越明显。 Angel由腾讯和北京大学联合开发，兼顾了工业界的高可用性和学术界的创新性。
-  


 #### 2.4 [前端](https://github.com/WechatFE)
 
 感觉这个地址就是腾讯占个位置,并没有什么重大开源项目,大家可以稍微看一下
 
 #### 2.5 [后台](https://github.com/TencentOpen)
-  [JX](https://github.com/TencentOpen/JX) <br>一个类似 Google Closure Library 的 Web 前端开发框架，JX 框架同时适用于 Web Page 和 Web App 项目的开发，特别适合构建和组织大规模、工业级的Web App，腾讯 WebQQ - http://web.qq.com、腾讯 Q+ http://www.QPlus.com 等产品都是采用JX框架开发，兼容目前所有主流浏览器。
  

 
 #### 2.6 [腾讯移动端UI](https://github.com/frozenui)
 -  [frozenui](https://github.com/frozenui/frozenui) star 2.2k <br>FrozenUI的CSS组件库,基于腾讯手Q样式规范 
 
### 3.百度
#### 3.1 [主团队](https://github.com/baidu)
 -  [bfs](https://github.com/baidu/bfs) star 2.1k <br>百度的核心业务和数据库系统都依赖分布式文件系统作为底层存储，文件系统的可用性和性能对上层搜索业务的稳定性与效果有着至关重要的影响。现有的分布式文件系统（如HDFS等）是为离线批处理设计的，无法在保证高吞吐的情况下做到低延迟和持续可用，所以我们从搜索的业务特点出发，设计了百度文件系统。
 -  [sofa-pbrpc](https://github.com/baidu/sofa-pbrpc) star 1.4k<br>sofa-pbrpc是基于Google Protocol Buffers 实现的RPC网络通信库，在百度公司各部门得到广泛使用，每天支撑上亿次内部调用。sofa-pbrpc基于百度大搜索高并发高负载的业务场景不断打磨，成为一套简单易用的轻量级高性能RPC框架。
   
 
#### 3.2 [主团队2](https://github.com/ecomfe)
-  [echarts](https://github.com/ecomfe/echarts) star 20k<br>ECharts 是指 Enterprise Charts（商业产品图表库），提供商业产品常用图表库，底层基于 ZRender，创建了坐标系，图例，提示，工具箱等基础组件，并在此上构建出折线图（区域图）、柱状图（条状图）、散点图（气泡图）、K线图、饼图（环形图）、地图、力导向布局图，同时支持任意维度的堆积和多图表混合展现。纯Javascript 的图表库，提供直观，生动，可交互，可个性化定制的数据可视化图表
-  [zrender](https://github.com/ecomfe/zrender) star 2.1k<br>一个轻量级HTML5 Canvas类库，MVC封装，数据驱动，提供类Dom事件模型，让canvas绘图大不同！

#### 3.3 [web前端1](https://github.com/fex-team)
-  [ueditor](https://github.com/fex-team/ueditor) star 2.9K<br> 富文本编辑器\
-  [fis3](https://github.com/fex-team/fis3) star 2.1K<br> FIS3 面向前端的工程构建系统。解决前端工程中性能优化、资源加载（异步、同步、按需、预加载、依赖管理、合并、内嵌）、模块化开发、自动化工具、开发规范、代码部署等问题。
-  [webuploader](https://github.com/fex-team/webuploader) star 4.8K<br>WebUploader是一个简单的以HTML5为主，FLASH为辅的现代文件上传组件。在现代的浏览器里面能充分发挥HTML5的优势，同时又不摒弃主流IE浏览器，延用原来的FLASH运行时，兼容IE6+，Andorid 4+，IOS 6+。两套运行时，同样的调用方式，可供用户任意选用。支持大文件分片并发上传，极大的提高了文件上传效率。


#### 3.4 [web前端2](https://github.com/baidufe)
   这个里面比较大的开源项目感觉没有什么,所以自己可以看一看,我就不在这里总结了

#### 3.5 [人工智能](https://github.com/baidu-research)
-  [warp-ctc](https://github.com/baidu-research/warp-ctc) star 2.9K<br>Warp-CTC是一个可以应用在CPU和GPU上高效并行的CTC代码库 （library） 介绍 CTCConnectionist Temporal Classification作为一个损失函数，用于在序列数据上进行监督式学习，不需要对齐输入数据及标签。比如，CTC可以被用来训练端对端的语音识别系统
  


### 4. 华为
 - [主团队](https://github.com/Huawei)
 感觉华为没开源什么玩意
 - [大数据团队](https://github.com/HuaweiBigData)
 自己看吧

### 5. 360

 #### 5.1 [主团队](https://github.com/Qihoo360)
 - [Atlas](https://github.com/Qihoo360/Atlas) star 3.0k <br>Atlas是由 Qihoo 360,  Web平台部基础架构团队开发维护的一个基于MySQL协议的数据中间层项目。它在MySQL官方推出的MySQL-Proxy 0.8.2版本的基础上，修改了大量bug，添加了很多功能特性。目前该项目在360公司内部得到了广泛应用，很多MySQL业务已经接入了Atlas平台，每天承载的读写请求数达几十亿条。
 - [DroidPlugin](https://github.com/Qihoo360/DroidPlugin) star 1.4k<br>感觉已过时
 DroidPlugin 是***360手机助手***在Android系统上实现了一种新的***插件机制***:它可以在无需安装、修改的情况下运行APK文件,此机制对改进大型APP的架构，实现多团队协作开发具有一定的好处。
 - [RePlugin](https://github.com/Qihoo360/RePlugin) star 3.6k (2017年06月30日开源)<br>RePlugin 其插件化方案是一套完整的、稳定的、适合全面使用的，占坑类插件化方案，于 2014 年中旬从 360 手机卫士团队产生，并正式在卫士上启用。360 表示 RePlugin 无论大小项目均可使用，稳定与灵活兼得，目前 360 公司几乎所有的亿级用户量的 APP ，以及多款主流第三方 APP ，都采用了 RePlugin 方案. 与其相媲美的还有滴滴的[VirtualAPK](https://github.com/didi/VirtualAPK),感觉滴滴的这个好像厉害点(我是从github的star看的)
 

 ### 6. 小米

#### 6.1 [主团队](https://github.com/xiaomi)
 - [minos](https://github.com/XiaoMi/minos)<br>Minos 是小米公司开发的一个分布式的发布和监控系统。最初是小米开发的用来在 Hadoop 和 ZooKeeper 集群上发布和管理的工具。Minos可轻松扩展来支持其他的系统，目前已经支持包括 HDFS、YARN 和 Impala 。
 - [open-falcon](https://github.com/XiaoMi/open-falcon) star 2.1k<br>用官网的话概述:监控系统业界有很多杰出的开源监控系统。我们在早期，一直在用zabbix，不过随着业务的快速发展，以及互联网公司特有的一些需求，现有的开源的监控系统在性能、扩展性、和用户的使用效率方面，已经无法支撑了。
因此，我们在过去的一年里，从互联网公司的一些需求出发，从各位SRE、SA、DEVS的使用经验和反馈出发，结合业界的一些大的互联网公司做监控，用监控的一些思考出发，设计开发了小米的监控系统
 
### 7. 58同城

### 7.1 [主团队](https://github.com/58code)
 感觉58同城的项目都比较老了,现在有很多其他项目比他的更完美,所以就不总结了
### 8. 美团 下面三个项目都
#### 8.1 [美团点评(新)](https://github.com/Meituan-Dianping)
 - [Robust](https://github.com/Meituan-Dianping/Robust) star 2.2k<br>新一代热更新系统Robust，对Android版本无差别兼容。无需发版就可以做到随时修改线上bug，快速对重大线上问题0.4.7作出反应，补丁修补成功率高达99.9%。
 - [walle](https://github.com/Meituan-Dianping/walle) star 1.9k<br>Android Signature V2 Scheme签名下的新一代渠道包打包神器,通过在Apk中的APK Signature Block区块添加自定义的渠道信息来生成渠道包，从而提高了渠道包生成效率，可以作为单机工具来使用，也可以部署在HTTP服务器上来实时处理渠道包Apk的升级网络请求。
 - [SQLAdvisor](https://github.com/Meituan-Dianping/SQLAdvisor) satr 1.7k<br>SQLAdvisor是由美团点评公司技术工程部DBA团队（北京）开发维护的一个分析SQL给出索引优化建议的工具。它基于MySQL原生态词法解析，结合分析SQL中的where条件、聚合条件、多表Join关系 给出索引优化建议。目前SQLAdvisor在美团点评内部广泛应用
 
#### 8.2 [美团点评(老)](https://github.com/Meituan)
 已经合并到8.1
#### 8.3 [大众点评(老)](https://github.com/dianping)
 - [cat](https://github.com/dianping/cat) star 1.9k<br> CAT基于Java开发的实时应用监控平台，包括实时应用监控，业务监控
 
 
### 9. 滴滴出行
#### 9.1 [主团队](https://github.com/didi) 
 - [VirtualAPK](https://github.com/didi/VirtualAPK) star 4.5k(2017年6月3号开源)<br>Android插件化技术是比较热门领域，VirtualAPK框架功能完备，支持Android四大组件，良好的兼容性，且入侵性较低，作为加载耦合插件方案是较好选择。兼容市面上几乎所有的Android手机，这一点已经在滴滴出行客户端中得到验证；
资源方面适配小米、Vivo、Nubia等，对未知机型采用自适应适配方案；极少的Binder Hook，目前仅仅hook了两个Binder：AMS和IContentProvider，hook过程做了充分的兼容性适配；插件运行逻辑和宿主隔离，确保框架的任何问题都不会影响宿主的

#### 9.2 [FE前端团队](https://github.com/DDFE) 
  - [DDFE-blog](https://github.com/DDFE/DDFE-blog) star 1.4k<br>这个项目也不是什么开源的项目,其实就是滴滴内部公司所分享的一些结束而已
   
  
### 10. 知乎
 - [主团队](https://github.com/zhihu)
  
 
### 11. 哔哩哔哩
 - [主团队](https://github.com/Bilibili)
 
 
### 12. 新浪微博
 - [主团队](https://github.com/weibocom)
  
 
### 13. 搜狐
 - [主团队](https://github.com/SOHUDBA)
 
### 14. 极光开发者(Jpush)
 - [主团队](https://github.com/jpush)
### 15. 开源中国
 - [主团队](https://github.com/oschina) 
### 16. 唯品会
 - [主团队](https://github.com/vipshop)
### 17. 当当
 - [主团队](https://github.com/dangdangdotcom)
### 18. 豆瓣
 - [主团队](https://github.com/douban)
 
### 19. 饿了么

 - [主团队](https://github.com/eleme)
 - [大前端](https://github.com/ElemeFE)

### 20. 有道词典
 - [主团队](https://github.com/netease)
### 21.网易
 - [主团队](https://github.com/netease)
### 22.七牛
 - [主团队](https://github.com/qiniu)
### 23. 环信
- [主团队](https://github.com/easemob)
### 24. YY
- [主团队](https://github.com/yyued)
### 25.芒果TV(or 湖南卫视)
 - [主团队](https://github.com/HunanTV)
### 24.坤腾畅联
 - [固件团队](https://github.com/KunTengRom)
 - [ApFree](https://github.com/liudf0716)
