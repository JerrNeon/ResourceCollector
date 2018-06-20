# Android新特性、问题及AS

***
## 目录
* [AndroidSupportDesign兼容库](#androidsupportdesign兼容库)
* [6.0](#60)
* [7.0+](#70)
* [常见控件问题及属性介绍](#常见控件问题及属性介绍)
* [AndroidStudio](#androidstudio)
* [适配](#适配)
* [学习知识](#学习知识)
* [Log颜色](#log颜色)

***

### [AndroidSupportDesign兼容库](#android新特性问题及as) 	
* [Material Design UI Widgets - 张兴业的博客 - 博客频道 - CSDN.NET](http://blog.csdn.net/xyz_lmn/article/details/35644799)
* [Android L中的RecyclerView 、CardView 、Palette的使用 - 张兴业的博客 - 博客频道 - CSDN.NET](http://blog.csdn.net/xyz_lmn/article/details/38735117)
* Toolbar
	* [Android 5.x Theme 与 ToolBar 实战 - Hongyang - 博客频道 - CSDN.NET](http://blog.csdn.net/lmj623565791/article/details/45303349)
	* [Toolbar自定义布局 - lxfeng1098751554的专栏 - 博客频道 - CSDN.NET](http://blog.csdn.net/lxfeng1098751554/article/details/50662886)
* [Android RecyclerView 使用完全解析 体验艺术般的控件 - Hongyang - 博客频道 - CSDN.NET](http://blog.csdn.net/lmj623565791/article/details/45059587)
* [Android应用Design Support Library完全使用实例 - OPEN 开发经验库](http://www.open-open.com/lib/view/open1433385856119.html)
	* [Material Design之CollapsingToolbarLayout使用 - 【博客地址永久迁移到】：http://zhengxiaoyong.me - 博客频道 - CSDN.NET](http://blog.csdn.net/u010687392/article/details/46906657)
	* [Android 自己实现 NavigationView 	* [Design Support Library(1)]  - Hongyang - 博客频道 - CSDN.NET](http://blog.csdn.net/lmj623565791/article/details/46405409)
	* [FloatingActionButton 完全解析	* [Design Support Library(2)]  - Hongyang - 博客频道 - CSDN.NET](http://blog.csdn.net/lmj623565791/article/details/46678867)
	* [android CoordinatorLayout使用 - 张兴业的博客 - 博客频道 - CSDN.NET](http://blog.csdn.net/xyz_lmn/article/details/48055919)
	* [Android Design Support Library（三）用CoordinatorLayout实现Toolbar隐藏和折叠 - 刘望舒的专栏 - 博客频道 - CSDN.NET](http://blog.csdn.net/itachi85/article/details/50492695)
	* [Android support library支持包常用控件介绍(一) - 积少成多，努力，谦逊，进取。 - 博客频道 - CSDN.NET](http://blog.csdn.net/zhangke3016/article/details/51752635)
	* [Android support library支持包常用控件介绍(二)](http://blog.csdn.net/zhangke3016/article/details/51771860)
* NestedScrollView
	* [Android Material Design：CoordinatorLayout与NestedScrollView - Zhang Phil - 博客频道 - CSDN.NET](http://blog.csdn.net/zhangphil/article/details/48877865)
* BottomNavigationView
	* [Android Support 25中BottomNavigationView与ViewPager结合实现material Tab标准效果](http://www.jianshu.com/p/46c629841803)
	* [BottomNavigationView 的使用](http://blog.csdn.net/wl9739/article/details/52875710)
* [BottomNavigationBar](https://github.com/Ashok-Varma/BottomNavigation)
* Bottom Sheet实现底部菜单
	* [使用Bottom Sheet实现底部菜单](http://www.jianshu.com/p/1024ad202683)
* TextInputLayout
	* [Material Design 之 TextInputLayout和TextInputEditText - 依然饭特稀西 - 掘金专栏](https://gold.xitu.io/post/58663bca570c3500688b5272) 
* Android UI(Switch和SwithcCompact)
	* [Android UI(Switch)详解](http://blog.csdn.net/qq_28057577/article/details/52261641)
* BottomNavigationBar
	* [UI-BottomNavigationBar-底部导航栏 - 简书](http://www.jianshu.com/p/134d7847a01e)
                

### [6.0](#android新特性问题及as) 
* 权限
	* [android 6.0权限全面详细分析和解决方案](http://blog.csdn.net/hudashi/article/details/50775180)
	* [Android 6.0RunTime Permission完美解决方案](http://blog.csdn.net/u011068996/article/details/50602100)
	* [Android 6.0 运行时权限处理 - forlong401的专栏--有问题上：http://www.androidren.com - 博客频道 - CSDN.NET](http://blog.csdn.net/forlong401/article/details/49787305)
	* [谈谈Android 6.0运行时权限理解 - cryAllen - 博客园](http://www.cnblogs.com/cr330326/p/5181283.html)
	* [Android开发——Android 6.0权限管理机制详解](http://blog.csdn.net/seu_calvin/article/details/52163456)
	* [GitHub - hotchemi/PermissionsDispatcher: Provides simple annotation-based API to handle runtime permissions.](https://github.com/hotchemi/PermissionsDispatcher)
	* [Android6.0权限管理PermissiDispater](http://blog.csdn.net/quan356270259/article/details/50876272)
	* [Android6.0动态权限申请步骤以及需要注意的一些坑](http://www.jianshu.com/p/a51593817825)
	* [RxPermissions源码解析](http://www.jianshu.com/p/c8a30200e6b2)
	* [Android M 权限最佳实践](http://chen-wei.me/2016/11/10/android-permission-best-practice/)                
                
### [7.0+](#android新特性问题及as) 
* 7.0文件使用/7.1快捷方式              
	* [Android7.0适配教程，心得 - 简书](http://www.jianshu.com/p/56b9fb319310)
	* [实践](http://blog.feng.moe/2016/11/03/android-new-shortcut-api/)
* 7.0拍照问题
	* [Android7.0拍照失败FileUriExposedException,你的拍照代码升级了吗](http://www.jianshu.com/p/a1eb3ad79ef6)
	* [如何在Android7.0系统下通过Intent安装apk | Alvin-一座小楼](http://www.czhzero.com/2016/12/21/how-to-install-apk-on-Android7-0/)
                

### [常见控件问题及属性介绍](#android新特性问题及as) 
* 软键盘               
	* [【Android】android:windowSoftInputMode属性详解 - Rex.. - 博客园](http://www.cnblogs.com/rayray/p/3380917.html)
	* [Android 爬坑之旅：软键盘挡住输入框问题的终极解决方案 - DiyCode](http://www.diycode.cc/topics/383)
	* [Android小技巧](http://fish119.site/2016/12/01/Android%E5%B0%8F%E6%8A%80%E5%B7%A7-Part-II/)
		* [android editText 软键盘enter键图标的设置 - Crazy Android - 博客频道 - CSDN.NET](http://blog.csdn.net/howlaa/article/details/36895021)
		* [Android 如何监听输入法关闭事件](http://blog.csdn.net/johnny901114/article/details/51471729)
* ImageView
	* [Android 设置ImageView宽度固定，其高度按比例缩放适应 - findsafety的专栏 - 博客频道 - CSDN.NET](http://blog.csdn.net/findsafety/article/details/51287642)
* 图片
	* [Android4.4中获取资源路径问题 - huangyanan1989的专栏 - 博客频道 - CSDN.NET](http://blog.csdn.net/huangyanan1989/article/details/17263203)
* drawable
	* [drawable不居中问题](http://blog.csdn.net/dreamintheworld/article/details/45243663)
* weiget
	* [自定义weiget大小属性详解](http://blog.csdn.net/kkkvvv123/article/details/9029381)
* Android抽象布局include
	* [Android抽象布局——include、merge 、ViewStub - 张兴业的博客 - 博客频道 - CSDN.NET](http://blog.csdn.net/xyz_lmn/article/details/14524567)
* fitsystemwindow
	* [fitsSystemWindows_果汁O_O哈哈_新浪博客](http://blog.sina.com.cn/s/blog_15e1702d40102w9e0.html)
* webview
	* [Android-WebView在ScrollView中高度不稳定末尾有大段空白问题解决 - qq_32452623的博客 - 博客频道 - CSDN.NET](http://blog.csdn.net/qq_32452623/article/details/52304628)
	* [还在用 Android 自带的 WebView 组件？太 Out 了！](http://gold.xitu.io/entry/57bd8c25df0eea005c708667)
	* [FinestWebView：可自定义的WebView](http://www.jianshu.com/p/f88c723d3d87)
* 优化
	* [一些你需要知道的布局优化技巧](http://blog.csdn.net/qq_17766199/article/details/52863741)
	* [Android性能优化的方方面面](http://www.jianshu.com/p/b3b09fa29f65)


### [AndroidStudio](#android新特性问题及as) 
* 配置             
	* [Android](http://liukun.engineer/2016/04/10/Android-Studio-advanced-configuration/)
	* [AndroidStudio入门之第三方引用 - 简书](http://www.jianshu.com/p/f33a1f413ab3)
	* [Gradle配置最佳实践](http://gold.xitu.io/post/582d606767f3560063320b21)
	* [Android常用的Gradle配置和加速编译](http://www.jianshu.com/p/81231a82f83c)
* 常见问题                
	* [学习Android Studio里的Gradle - Kenny tian - 博客园](http://www.cnblogs.com/Kennytian/p/4923993.html)
	* [Error:Gradle version 2.2 is required. Current version is 2.10. If using the gradle wrapper - Lennie的博客 - 博客频道 - CSDN.NET](http://blog.csdn.net/weixin_35789435/article/details/52119008)
	* [org.gradle.api.publication.maven.internal.DefaultMavenFactory错误 - 木头平 - 博客园](http://www.cnblogs.com/lping/p/5474954.html)
	* [Gradle version 2.10 is required. Current version is 2.2.1. If using the grad - lwh690140814的博客 - 博客频道 - CSDN.NET](http://blog.csdn.net/lwh690140814/article/details/51783594)
	* [Android studio gradle配置 - OPEN 开发经验库](http://www.open-open.com/lib/view/open1415793464648.html)
	* [Android Studio导入第三方类库的方法 - 阿新 - 博客园](http://www.cnblogs.com/neozhu/p/3458759.html)
	* [Android实战技巧之十二：Android Studio导入第三方类库、jar包和so库 - 懒人的技术笔记 - 博客频道 - CSDN.NET](http://blog.csdn.net/lincyang/article/details/43951527/)
	* [AndroidStudio导出jar包 - beijingshi1的专栏 - 博客频道 - CSDN.NET](http://blog.csdn.net/beijingshi1/article/details/38681281)
	* [Cannot reload AVD list - 吃素只吃肉的博客 - 博客频道 - CSDN.NET](http://blog.csdn.net/qq_28919337/article/details/50899282)
	* [android出现注: 某些输入文件使用或覆盖了已过时的 API。 注: 有关详细信息, 请使用 -Xlint:deprecation 重新编译。 注: 某些输入文件使用了未经检查或不安全的操作。 注 - u012416928的专栏 - 博客频道 - CSDN.NET](http://blog.csdn.net/u012416928/article/details/47356887)
	* [Error:warning: Ignoring InnerClasses attribute for an anonymous inner class - lvshuchangyin的专栏 - 博客频道 - CSDN.NET](http://blog.csdn.net/lvshuchangyin/article/details/51803154)                 
* 优化                 
	* [30秒让你加速Android Studio/Gradle构建 - 51CTO.COM](http://mdsa.51cto.com/art/201503/469038.htm)
	* [AndroidStudio编译提速，快过eclipse](http://blog.csdn.net/zero_and_one/article/details/42009487)
	* [【译】我每周在构建Gradle时是如何节约出5小时的](http://www.jianshu.com/p/f9b0592383b8)
* 代码混淆和多渠道打包
	* [Android Studio多渠道打包和代码混淆教程 - leeo1010的专栏 - 博客频道 - CSDN.NET](http://blog.csdn.net/leeo1010/article/details/49903759)
	* [写给Android开发者的混淆使用手册](http://mp.weixin.qq.com/s?__biz=MzI4NTQ2OTI4MA==&mid=2247483651&idx=1&sn=85f0d6c6a0f6c4f2ece97429f423c51c&chksm=ebeafe0cdc9d771a31344d0d6861e3b864bfe36d46652770aa522631eb0115a754e1be579d3b#rd)
	* [proguard](http://blog.csdn.net/yuhanghate/article/details/51656804)
	* [AndroidStudio中代码混淆以及打包操作 - classTC的博客 - 博客频道 - CSDN.NET](http://blog.csdn.net/ttccaaa/article/details/47687241)
	* [深入学习ProGuard之：ProGuard简介与android的应用](https://gold.xitu.io/post/5854fbc98d6d810065a006c4)
* 调试
	* [Android 高效调试神器 JRebel](http://blog.csdn.net/googdev/article/details/53288564)
	* [Freeline](https://yq.aliyun.com/articles/59122?spm=5176.8091938.0.0.1Bw3mU)
* 签名
	* [Android Gradle signing 编译打包apk的几种办法](http://blog.csdn.net/ylbf_dev/article/details/52399083)

### [适配](#android新特性问题及as)
* autolayout适配
	* [Android AutoLayout全新的适配方式 堪称适配终结者 - Hongyang - 博客频道 - CSDN.NET](http://blog.csdn.net/lmj623565791/article/details/49990941)
	* [GitHub - hongyangAndroid/AndroidAutoLayout: Android屏幕适配方案，直接填写设计图上的像素尺寸即可完成适配，最大限度解决适配问题。](https://github.com/hongyangAndroid/AndroidAutoLayout) 
	* [Android解决AutoLayout不能设置多种设计稿尺寸的问题](http://blog.csdn.net/qq199208/article/details/52815831)
* 屏幕适配(values和百分比)
	* [Android 百分比布局库(percent-support-lib) 解析与扩展 - Hongyang - 博客频道 - CSDN.NET](http://blog.csdn.net/lmj623565791/article/details/46695347)


### [学习知识](#android新特性问题及as) 
* Android手势以及MotionEvent
	* [Android手势以及MotionEvent](http://blog.jiangtao.tech/2016/10/03/Android%E6%89%8B%E5%8A%BF%E4%BB%A5%E5%8F%8AMotionEvent/)
* Framework
	* [android/platform_frameworks_base](https://github.com/android/platform_frameworks_base)
* kotlin开发Android
	* [Android开发必备知识：为什么说Kotlin值得一试](http://www.jcodecraeer.com/a/anzhuokaifa/androidkaifa/2016/0226/4000.html)
* jar和aar
	* [android中.aar文件与.jar文件的区别](http://blog.csdn.net/justinnick/article/details/52421234)
	* [获取开源框架的jar或aar](https://jitpack.io/)
* js和java的交互库
	* [Android中极简的js与java的交互库－SimpleJavaJsBridge](http://www.jianshu.com/p/de6331c9958f)
* Material design规范
	* [Android Design Support Library使用](http://mp.weixin.qq.com/s?__biz=MzI4MTQyNDg3Mg==&mid=2247483752&idx=1&sn=e5a12a53d12dbe80c27ae78af9660b12&chksm=eba827efdcdfaef999ac120869fb3b32508d76f883d1c9b2701c840834a9feef53d0ed9669a3#rd)
	* [Android Material风格的Dialog的使用 - 简书](http://www.jianshu.com/p/6caffdbcd5db)
	

### [Log颜色](#android新特性问题及as)
	Assert:   #AA66CC
	Debug: 	  #33B5E5
	Error: 	  #FF4444
	Info: 	  #99CC00
	Verbose:  #FFFFFF
	Warning:  #FFBB33
