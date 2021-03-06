SAF
===
1.1.4之前的开发都是在google code上托管的，从1.1.4开始记录版本日志。

Version 1.1.19
---
2016-05-17
 *  针对android6.0的权限需求,imageloader做了修改
 *  新增NoEmptyHashMap
 *  优化RxImageLoader
 *  新增aspectj的支持, 增加了@LogMethod @Trace @Cacheable @Safe @Async @Prefs 等注解,这些注解无需使用反射
 *  新增RxAsyncTask

Version 1.1.18
---
2016-02-15
 *  修复底层的bug 优化代码
 *  项目结构由原先的eclipse转变成android studio
 *  增加工具类Preconditions
 *  增加RxEventBus RxImageloader,这2个模块还处于试验阶段,不推荐使用
 *  增加android5.0以后判断app是否处于前台的方法
 *  增加cache类
 *  增加SAFRecycleAdapter类
 *  去掉原先插件化的类,打算重新设计这个模块

Version 1.1.17
---
2015-08-28
 *  增加HttpRetryStrategy接口
 *  imageloader的线程数,由当前手机的cpu数量决定
 *  增加新型的反射工具类

Version 1.1.16
---
2015-08-04
 *  删除RestClient的BinaryResponseHandler
 *  RestClient增加response的header支持
 *  修复android L以后版本无法使用imageloader的bug

Version 1.1.15
---
2015-07-21
 *  增加下载模块
 *  修复删除图片缓存时,报的空指针bug

Version 1.1.14
---
2015-06-18
 *  增加AbstractParcelable
 *  精简SAFActivity、SAFFragmentActivity
 *  删除cn.salesuite.saf.net包,减少saf包的大小

Version 1.1.13
---
2015-05-06
 *  RestClient增加https的支持
 *  修复L的bug
 *  InjectExtra增加默认值
 *  AsyncTaskExecutor增加android.os.AsyncTask的支持

Version 1.1.12
---
2015-03-11
 *  增加OnClick的hocker接口，before和after方法，用于埋点
 *  增加OnItemClick的hocker接口，before和after方法，用于埋点
 *  增加工具方法
 *  增加RestClient的BinaryResponseHandler（曹亚民）
 *  增加全新的AsyncTask（曹亚民）

Version 1.1.11
---
2015-02-24
 *  增加工具类
 *  优化Router，Router增加便于埋点的接口
 *  修复ToastUtils的bug

Version 1.1.10
---
2014-12-24
 *  eventbus增加线程模式ScheduleBackgroundThread
 *  增加List的帮助类Lists
 *  BasePrefs中各个put方法，都包含save()方法，避免BasePrefs再调用save（）
 *  修复bug

Version 1.1.9
---
2014-11-12
 *  完善工具类命名规范

Version 1.1.8
---
2014-11-10
 *  完善SAFAdapter
 *  Injector增加Adapter的支持
 *  完善多个工具类

Version 1.1.7
---
2014-10-10
 *  优化ImageLoader
 *  增加@OnTouch
 *  增加SAFAdapter
 *  完善L、ToastUtil

Version 1.1.6
---
2014-09-17
 *  优化RestClient，增加重试机制
 *  增加@OnLongClick

Version 1.1.5
---
2014-09-11
 *  优化ImageLoader，disklrucache升级到2.0.3

Version 1.1.4
---
2014-09-06
 *  增加@InjectViews、@OnClick、@OnItemClick
 *  增加日志框架L
 *  优化@InjectView
