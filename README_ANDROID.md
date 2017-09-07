# AndroidResource

***
## 目录
* [网络请求框架](#网络请求框架)
* [Rx系列](#rx系列)
* [常用框架](#常用框架)
* [常用控件](#常用控件)
* [仿IOS控件](#仿ios控件)
* [与媒体有关](#与媒体有关)
* [RecyerView、ListView、GridView、ScrollView](#recyerviewlistviewgridviewscrollview)
* [布局相关](#布局相关)
* [插件](#插件)
* [自定义View系列](#自定义view系列)
* [Activity和Fragment](#activity和fragment)
* [工具类](#工具类)
* [知识点](#知识点)
* [动画](#动画)
* [开发框架和开源项目](#开发框架和开源项目)
* [第三方](#第三方)
* [优质资源查找和学习site](#优质资源查找和学习site)
* [大神、著名公司主页](#大神著名公司主页)

***
### [网络请求框架](#androidresource)
* [Retorfit](https://github.com/square/retrofit)
* [OkGo](https://github.com/jeasonlzy/okhttp-OkGo)
	* [廖子尧](https://github.com/jeasonlzy)
	* [OkGo，一个专注于让网络请求更简单的框架，与RxJava完美结合，比Retrofit更简单易用。 - 简书](http://www.jianshu.com/p/6aa5cb272514)
* [OkHttp](https://github.com/square/okhttp)
	* [源码解析文章](http://frodoking.github.io/2015/03/12/android-okhttp/)
	* [拦截并记录所有的HTTP请求与响应](https://github.com/jgilfelt/chuck)
	* [Bridge是一个简单但是强大的HTTP网络操作库。提供链式调用的API，为了最大的兼容性和最快的速度，用 Java/Android的URLConnection类实现](https://github.com/afollestad/bridge)

### [Rx系列](#androidresource)
* [RxJava](https://github.com/ReactiveX/RxJava)
	* [文档](https://github.com/mcxiaoke/RxDocs)
	* [文章](https://gold.xitu.io/post/57d8b4b0c4c97100610509c6)	
	* Retrofit + Rxjava + okhttp
		* [使用Retrofit2.0+OkHttp3.0实现缓存处理 | Werb&#39;s Blog](http://werb.github.io/2016/07/29/%E4%BD%BF%E7%94%A8Retrofit2+OkHttp3%E5%AE%9E%E7%8E%B0%E7%BC%93%E5%AD%98%E5%A4%84%E7%90%86/)
		* [RxJava系列1(简介)](http://www.jianshu.com/p/ec9849f2e510)
		* [用工厂流水线的方式来理解 RxJava 的概念](http://www.jcodecraeer.com/a/anzhuokaifa/androidkaifa/2016/0429/4196.html)
		* [RxJava 与 Retrofit 结合的最佳实践](http://gank.io/post/56e80c2c677659311bed9841)
		* [RxJava 详解(扔物线)](http://gank.io/post/560e15be2dca930e00da1083)
		* [RxJava 和 RxAndroid 四（RxBinding的使用）](http://blog.csdn.net/zyj1609wz/article/details/51523835)
	* 文件上传与下载
		* [Retrofit+Rxjava 下载文件(带进度显示) - JokAr - 博客频道 - CSDN.NET](http://blog.csdn.net/a1018875550/article/details/51832700)
	* [使用Retrofit2 RxJava 文件上传](http://blog.csdn.net/soslinken/article/details/51274327)
	* [关于 RxJava 最友好的文章—— RxJava 2.0 全新来袭 - 拉丁吴 - 掘金专栏](https://gold.xitu.io/post/582b2c818ac24700618ff8f5)
* [RxPermission](https://github.com/tbruyelle/RxPermissions)
* [RxLifecycle](https://github.com/trello/RxLifecycle)


### [常用框架](#androidresource)
* 注解
	* [ButterKnife](https://github.com/JakeWharton/butterknife/)
		* [插件](https://github.com/avast/android-butterknife-zelezny)
	* [Dragger](https://github.com/google/dagger)
* 通信
	* [EventBus](https://github.com/greenrobot/EventBus)
* 图片加载
	* [Glide](https://github.com/bumptech/glide)
		* [Glide多种形状](https://github.com/wasabeef/glide-transformations)
		* [Glide 一个专注于平滑滚动的图片加载和缓存库](http://www.jianshu.com/p/4a3177b57949)
		* [详谈高大上的图片加载框架Glide](http://blog.csdn.net/xiehuimx/article/details/52349317)
		* [详谈高大上的图片加载框架Glide](http://gold.xitu.io/post/57df609767f3560056b03672)
		* [Android之Glide使用详解](http://blog.csdn.net/qq_19711823/article/details/51243918)
* 数据库
	* [ObjectBox](https://github.com/greenrobot/ObjectBox)
		* [文章](http://www.tuicool.com/articles/biQ3Anm)
	* [greenDAO](https://github.com/greenrobot/greenDAO)
	* [realm不基于Sqlite](https://github.com/realm/realm-java)
* 缓存
	* [RxCache](https://github.com/VictorAlbertos/RxCache)
	* [异步加载和缓存库](https://github.com/NYTimes/Store)
* lambda表达式
	* [retrolambda](https://github.com/evant/gradle-retrolambda)
	* [Java Lambda表达式入门](http://blog.csdn.net/renfufei/article/details/24600507)
* 一款用心去做的Android 换肤框架, 极低的学习成本, 极好的用户体验. 只需要两行代码, 就可以实现换肤, 你值得拥有
	* [Android-skin-support](https://github.com/ximsfei/Android-skin-support)
* facebook出品，可以非常方便地查看应用的网络情况，监测应用中SQLite、SharedPreferences数据，查看当前Activity的布局结构，甚至修改布局中的文字等，可以实时生效，也可以借助JS执行一些命令，查看当前应用中的数据，功能比较强大
	* [stetho](https://github.com/facebook/stetho)
* 查看App数据库和sharepreference文件
	* [Android-Debug-Database](https://github.com/amitshekhariitbhu/Android-Debug-Database)
* 支持多种手势和动作检测
	* [sensey](https://github.com/nisrulz/sensey)
	
### [常用控件](#androidresource)
* Banner控件
	* [XBanner](https://github.com/xiaohaibin/XBanner)
	* [Android-ConvenientBanner](https://github.com/saiwu-bigkoo/Android-ConvenientBanner)
	* [banner动画](https://github.com/ToxicBakery/ViewPagerTransforms)
* 自动版本检测并更新库
	* [CheckVersionLib](https://github.com/AlexLiuSheng/CheckVersionLib)
* 底部导航栏
	* [BottomBar](https://github.com/roughike/BottomBar)
	* [BottomNavigation](https://github.com/Ashok-Varma/BottomNavigation)
	* [图标制作](https://romannurik.github.io/AndroidAssetStudio/icons-generic.html#source.type=image&source.space.trim=1&source.space.pad=0&size=24&padding=8&color=33b5e5%2C100&name=ic_icon_cdgx_on)
* 加载框进度条
	* [加载框](https://github.com/Kaopiz/KProgressHUD)
	* [Material风格对话框](https://github.com/afollestad/material-dialogs)
	* [圆角button点击后变成加载button](https://github.com/dmytrodanylyk/circular-progress-button)
	* [水平进度条](https://github.com/daimajia/NumberProgressBar)
	* [进度条来显示加载图片的进度](https://github.com/peng8350/LoadingProgress/blob/master/README_CN.md)
	* [一款漂亮简洁的广告计时组件](https://github.com/flyou/AdCountView)
	* [加载动画AVLoadingIndicatorView](https://github.com/81813780/AVLoadingIndicatorView)
* 表单验证
	* [android-edittext-validator](https://github.com/vekexasia/android-edittext-validator)
* 标签云
	* [TagCloudView](https://github.com/kingideayou/TagCloudView)
	* [3dTagCloudAndroid](https://github.com/misakuo/3dTagCloudAndroid)
	* [android-tagview](https://github.com/kaedea/android-tagview)
	* [FlowLayout](https://github.com/nex3z/FlowLayout)
* Toast
	* [Toasty](https://github.com/GrenderG/Toasty)
	* [StyleableToast](https://github.com/Muddz/StyleableToast)
* 可以预览电影的SeekBar
	* [PreviewSeekBar](https://github.com/rubensousa/PreviewSeekBar)
* 支持简单快速的文字输入，不管是来自语音，键盘，还是预设回复
	* [wearable-reply](https://github.com/klinker24/wearable-reply)
* 一个帮助你实现关于我界面的库
	* [MaterialAbout](https://github.com/jrvansuita/MaterialAbout)
* 谷歌启动器风格的开关图标
	* [Android-SwitchIcon](https://github.com/zagum/Android-SwitchIcon)
* 一个用RecyclerView实现的Material横向日历视图
	* [Horizontal-Calendar](https://github.com/Mulham-Raee/Horizontal-Calendar)
* 角标
	* 消息图标角标
		* [android-viewbadger](https://github.com/jgilfelt/android-viewbadger)
		* [BadgeView](https://github.com/qstumn/BadgeView)
	* [启动图标角标](ttps://github.com/leolin310148/ShortcutBadger)
	* [一个在浮动操作按钮的右上角显示数字标识的库](https://github.com/andremion/CounterFab)
* 图表库
	* 曲线图、折线图、柱形图
		* [MPAndroidChart](https://github.com/PhilJay/MPAndroidChart)
		* [BadgeView](https://github.com/qstumn/BadgeView)
	* 日程表
		* [ScrollablePanel](https://github.com/Kelin-Hong/ScrollablePanel)
	* RecyclerView实现的二维表格，不仅可以加载历史数据，还能加载新数据
		* [excelPanel](https://github.com/zhouchaoyuan/excelPanel)
* 验证码	
	* 随机图片验证码
		* [CheckFourMark](https://github.com/QQ986945193/CheckFourMark)
		* [VerificationCode](https://github.com/poberwong/VerificationCode)
	* 滑动滑块验证
		* [SwipeCaptcha](https://github.com/mcxtzhang/SwipeCaptcha)	
* jOOR反射封装		
	* [jOOR](https://github.com/jOOQ/jOOR)	
* 最最轻量级的新手引导库，能够快速为任何一个View创建一个遮罩层，支持单个页面，多个引导提示，支持为高亮区域设置不同的图形，支持引导动画，方便扩展,良好支持fragment
	* [GuideView](https://github.com/binIoter/GuideView)
* 带计数的输入框
	* [BufferTextInputLayout](https://github.com/bufferapp/BufferTextInputLayout)
* 日历和日期
	* [Android自定义控件之日历控件 - 泡在网上的日子](http://www.jcodecraeer.com/a/anzhuokaifa/androidkaifa/2015/0930/3538.html)
	* [android WheelView时间选择器 - a541006的专栏 - 博客频道 - CSDN.NET](http://blog.csdn.net/a541006/article/details/40212321)
	* [Android自定义控件之日历控件 - Mr_dsw的博客 - 博客频道 - CSDN.NET](http://blog.csdn.net/mr_dsw/article/details/48755993)
* 双向SeekBar
	* [android-range-seek-bar](https://github.com/anothem/android-range-seek-bar)	

### [仿IOS控件](#androidresource)	
* 开关
	* [SlideSwitch](https://github.com/Leaking/SlideSwitch)
* 底部弹出框
	* [Android-PickerView](https://github.com/saiwu-bigkoo/Android-PickerView)
* 对话框
	* [Android-AlertView](https://github.com/saiwu-bigkoo/Android-AlertView)
* 日历
	* [material-calendarview](https://github.com/prolificinteractive/material-calendarview)
* 一步集成侧滑(删除)菜单
	* [SwipeDelMenuLayout](https://github.com/mcxtzhang/SwipeDelMenuLayout)
* 悬浮菜单
	* [BoomMenu](https://github.com/Nightonke/BoomMenu)
* 3DTouch(shortcut)
	* [shortbread](https://github.com/MatthiasRobbers/shortbread)
	
### [与媒体有关](#androidresource)
* 图片相关处理(拍照、相册、裁剪、压缩)
	* 一款用于在Android设备上获取照片（拍照或从相册、文件中选择）、裁剪图片、压缩图片的开源工具库
		* [TakePhoto](https://github.com/crazycodeboy/TakePhoto)
	* 裁剪
		* [android-crop](https://github.com/jdamcd/android-crop)
		* [uCrop](https://github.com/Yalantis/uCrop)
	* 鲁班压缩
		* [Luban](https://github.com/Curzibn/Luban)
	* 一个基于MVP模式的Android多媒体选择器
		* [boxing](https://github.com/Bilibili/boxing)
	* 一个集成了拍照功能的Fragment
		* [CameraFragment](https://github.com/florent37/CameraFragment)
* 播放器
	* [ijkplayer](https://github.com/Bilibili/ijkplayer)
	* [GSYVideoPlayer](https://github.com/CarGuo/GSYVideoPlayer)
	* [jjdxm_ijkplayer](https://github.com/jjdxmashl/jjdxm_ijkplayer/)
* VR实战
	* [googleVR](https://github.com/googlevr/gvr-android-sdk)
	* [图片](https://github.com/linglongxin24/VRDevelopImage)
	* [视屏](https://github.com/linglongxin24/VRDevelopVideo)

### [RecyerView、ListView、GridView、ScrollView](#androidresource)	
* Recycler和ViewPager结合
	* [RecyclerViewPager](https://github.com/lsjwzh/RecyclerViewPager)
* 常用的RecyclerView的各种需求封装进库
	* [EasyRecyclerView](https://github.com/Jude95/EasyRecyclerView)
* ListView滑动到顶部时头部置顶不动
	* [StickyListHeaders](https://github.com/emilsjolander/StickyListHeaders)
* 支持下拉刷新和下拉加载的RecyclerView
	* [XRecyclerView](https://github.com/jianghejie/XRecyclerView)
* 一个可以在加载数据的时候显示闪烁（Shimmer）的RecyclerView
	* [ShimmerRecyclerView](https://github.com/sharish/ShimmerRecyclerView)
* 与adapter有关
	* [Android复杂的列表视图新写法](https://github.com/drakeet/MultiType/blob/master/README.md)
	* [RecyerView适配器封装](https://github.com/CymChad/BaseRecyclerViewAdapterHelper)	
	* [GitHub - hongyangAndroid/baseAdapter: Android 万能的Adapter for ListView,RecyclerView,GridView等，支持多种Item类型的情况。](https://github.com/hongyangAndroid/baseAdapter)
* 可拖拽的ListView
	* [可拖拽listview基本使用技巧（DragSortListView） - forrey的专栏 - 博客频道 - CSDN.NET](http://blog.csdn.net/forrey/article/details/41355457/)
	* [ListView拖动（或长按拖动）子项item，更改位置，且可以左右滑删除子项item - u012658005的专栏 - 博客频道 - CSDN.NET](http://blog.csdn.net/u012658005/article/details/44041235)
	* [拖拽滑动DragSortListview](http://blog.csdn.net/u010436741/article/details/9419167)
	
### [布局相关](#androidresource)
* MaterialDesign风格的ViewPager
	* [MaterialViewPager](https://github.com/florent37/MaterialViewPager)
* 快速实现滑动隐藏标题栏和导航栏
	* [ByeBurger](https://github.com/githubwing/ByeBurger)
* 一个Android TabLayout库(包含SlidingTabLayout、CommonTabLayout、SegmentTabLayout)
	* [FlycoTabLayout](https://github.com/H07000223/FlycoTabLayout/blob/master/README_CN.md)
* 一些自定义的LayoutManager，仿探探、人人影视 炫动滑动 卡片层叠 和流式布局等
	* [ZLayoutManager](https://github.com/mcxtzhang/ZLayoutManager)
* Tab导航栏，与ViewPager配合使用
	* [ViewPagerIndicator](https://github.com/JakeWharton/ViewPagerIndicator)
	* [PagerSlidingTabStrip](https://github.com/astuetz/PagerSlidingTabStrip)
* 类似js中FlexBox布局	
	* [flexbox-layout](https://github.com/google/flexbox-layout)
* 列表和头部标题滑动特效,类似于AndroidSupportDesign中CoordinatorLayout
	* [Android-ObservableScrollView](https://github.com/ksoichiro/Android-ObservableScrollView)
* 快速实现TabLayout与CoordinatorLayout相结合
	* [CoordinatorTabLayout](https://github.com/hugeterry/CoordinatorTabLayout)
* 一种 top bar 的新设计，与DrawerLayout一起协同工作
	* [AwesomeBar](https://github.com/florent37/AwesomeBar)
* 一个弧形的抽屉导航(侧滑)
	* [ArcNavigationView](https://github.com/rom4ek/ArcNavigationView)
* android可视化界面和流式布局               
	* [了解使用Android ConstraintLayout - 享受技术带来的快乐 - 博客频道 - CSDN.NET](http://blog.csdn.net/jdsjlzx/article/details/51460581)
	* [android流式布局：FlexboxLayout用法探析(一) - FightSeeker的专栏 - 博客频道 - CSDN.NET](http://46aae4d1e2371e4aa769798941cef698.devproxy.yunshipei.com/tabolt/article/details/51799226)
* tagFlowLayout(流式布局)
	* [GitHub](https://github.com/hongyangAndroid/FlowLayout)
* Hongyang	
	* [神奇的Android Studio Template - Hongyang - 博客频道 - CSDN.NET](http://blog.csdn.net/lmj623565791/article/details/51592043)
	* [Android ORMLite 框架的入门用法 - Hongyang - 博客频道 - CSDN.NET](http://blog.csdn.net/lmj623565791/article/details/39121377)
	* [Android屏幕适配姿势](http://www.jianshu.com/p/5d5494dd6dbe)
	
	
### [插件](#androidresource)
* 实体类parcelable序列化插件
	* [android-parcelable-intellij-plugin](https://github.com/mcharmas/android-parcelable-intellij-plugin)
* 转换value中Strings中文为其他语言的插件
	* [AndroidLocalizationer](https://github.com/westlinkin/AndroidLocalizationer)
* 自动生成selector资源文件插件
	* [android-selector-chapek](https://github.com/inmite/android-selector-chapek)
* 通过json格式建立实体类的插件
	* [Json2Class](https://github.com/anzewei/Json2Class)
* 一键生成项目混淆代码插件
	* [AndroidProguardPlugin](https://github.com/zhonghanwen/AndroidProguardPlugin)
* 批量地压缩你项目中的图片插件
	* [TinyPngPlugin](https://github.com/waynell/TinyPngPlugin/blob/master/README.zh-cn.md)
* Chrome插件
	* [Chrome插件,Chrome商店,谷歌浏览器插件下载 - Chrome插件网](http://www.cnplugins.com/)
* 在线查看Github上的项目插件
	* [【Octotree Chrome插件】Octotree Chrome插件下载](http://www.cnplugins.com/devtool/octotree/)
* 插件合集
	* [合集1](https://mp.weixin.qq.com/s?__biz=MzI3MDE0NzYwNA==&mid=2651433634&idx=1&sn=e5f65d8a0a2b85f7c22d8ccd4cf96a39&scene=1&srcid=0721vQcDls3Ak34dZY1y3h7o&key=77421cf58af4a653e4f55f04cf114492e73a17a2a7d56a0e523c62f16c003b19cdab0cf3a902023d7cbe2af60a58c71d&ascene=0&uin=MjAyNzY1NTU%3D&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.3+build(15D21)&version=11020201&pass_ticket=ihQKTSTYwhIquv1%2B6HyhJs3I0vZz0qtIoTVci3l%2BikU%3D)
	* [合集2](https://github.com/dreamlivemeng/androidstudio-plugins)
	* [合集3](https://ydmmocoo.github.io/2016/06/28/Android-Studio%E6%8F%92%E4%BB%B6%E6%95%B4%E7%90%86/)
* 插件查找
	* [jetbrains](https://plugins.jetbrains.com/?idea)

### [自定义View系列](#androidresource)
* 一个功能强大的TextView，可以满足日常大部分布局方式(常用于个人中心)
	* [SuperTextView](https://github.com/lygttpod/SuperTextView)
* 显示富文本
	* [html-textview](https://github.com/SufficientlySecure/html-textview)
	* [XRichText](https://github.com/limedroid/XRichText)
* 一个可以用代码设置selector背景（按下去背景颜色更改，样式变化等等）的button
	* [StateButton](https://github.com/niniloveyou/StateButton)
* 迷你版轻量级Label辅助类(一般用于图片左上角的标签)
	* [AvatarLabelView](https://github.com/yanbober/AvatarLabelView)
* 可收缩展开的TextView
	* [ExpandableTextView](https://github.com/Carbs0126/ExpandableTextView)
* Android 自定义View合集
	* [博客](http://www.jianshu.com/p/a5040fcfe8cb)
* 自定义TextView(自适应，水平垂直滚动)
	* [安卓AutoFitTextView实例Dmeo分享自适应 - Su_tianbiao的专栏 - 博客频道 - CSDN.NET](http://blog.csdn.net/su_tianbiao/article/details/44704261)
	* [Android:TextView的垂直滚动效果,和上下滚动效果 - ZhengJiao - 博客频道 - CSDN.NET](http://blog.csdn.net/zheng_jiao/article/details/51546356)
	* [Android 文字自动滚动（跑马灯）效果的两种实现方法 - 任海丽(3G/移动开发) - 博客频道 - CSDN.NET](http://blog.csdn.net/rhljiayou/article/details/7068614)
* ViewDragHelper自定义ViewGroup神器
	* [Android ViewDragHelper完全解析 自定义ViewGroup神器](http://blog.csdn.net/lmj623565791/article/details/46858663)
* TextView文字滚动效果
	* [Android 文字自动滚动（跑马灯）效果的两种实现方法 - chenshi011的专栏 - 博客频道 - CSDN.NET](http://blog.csdn.net/chenshi011/article/details/7792326)
* 图片阴影效果(https://github.com/yingLanNull/ShadowImageView)
* 图形锁(https://github.com/aritraroy/PatternLockView)
	
### [Activity和Fragment](#androidresource)	
* 为"单Activity ＋ 多Fragment","多模块Activity + 多Fragment"架构而生，帮你大大简化使用过程，轻松解决各种复杂嵌套等问题
	* [Fragmentation](https://github.com/YoKeyword/Fragmentation)
* 设置不同主题
	* [Colorful](https://github.com/garretyoder/Colorful)
* 与路由跳转有关
	* [DeepLinkDispatch](https://github.com/airbnb/DeepLinkDispatch)
	* [ARouter](https://github.com/alibaba/ARouter) 
* 打不死的小强,永不crash的Android	
	* [Cockroach](https://github.com/android-notes/Cockroach)
* ViewPager懒加载                
	* [实现ViewPager懒加载的三种方法 - 如琢如磨 - 博客频道 - CSDN.NET](http://blog.csdn.net/baidu_26654149/article/details/50992748)
	* [GitHub - lianghanzhen/LazyViewPager](https://github.com/lianghanzhen/LazyViewPager)
	* [【Android】Fragment懒加载和ViewPager的坑](http://www.jianshu.com/p/311c7ffdb85b)
	* [lvzishen/ViewPagerLazyLoad:](https://github.com/lvzishen/ViewPagerLazyLoad/tree/master)
	* [Viewpager动画](http://blog.csdn.net/lmj623565791/article/details/40411921/)
	* [关于ViewPager的懒加载问题 - jys1115的专栏 - 博客频道 - CSDN.NET](http://blog.csdn.net/jys1115/article/details/41862019?utm_source=tuicool)

### [工具类](#androidresource)	
* 常用合集
	* [Lazy](https://github.com/l123456789jy/Lazy)
	* [AndroidUtils](https://github.com/WuXiaolong/AndroidUtils)
	* [AndroidUtilCode](https://github.com/Blankj/AndroidUtilCode/blob/master/README-CN.md)
	* [CommonUtilLibrary](https://github.com/AbrahamCaiJin/CommonUtilLibrary)
* 判断App位于前台或者后台的6种方法	
	* [AndroidProcess](https://github.com/wenmingvs/AndroidProcess)
* 中国各大银行卡号查询CNBankCard	
	* [cnbankcard](https://github.com/digglife/cnbankcard)
	* [文章](http://blog.csdn.net/u013334392/article/details/52495363)
* 状态栏一体化	
	* [StatusBarUtil](https://github.com/laobie/StatusBarUtil)
	* [SystemBarTint](https://github.com/jgilfelt/SystemBarTint)
* 简化和JSON的交互	
	* [ason](https://github.com/afollestad/ason)
* android特殊转义字符
	* [android strings.xml的特殊字符 - 点滴积累成就技术梦想 - 博客频道 - CSDN.NET](http://blog.csdn.net/leiming32/article/details/8135513)
* 定时
	* [ScheduledExecutorService执行周期性或定时任务 - tianxiangshan的专栏 - 博客频道 - CSDN.NET](http://blog.csdn.net/tianxiangshan/article/details/8599337)
* Json格式转化成Model
	* [JSONModel解析数据成Model - Jacky Shin的专栏 - 博客频道 - CSDN.NET](http://blog.csdn.net/smking/article/details/40432287)
* 正则表达式
	* [Android正则表达式 - TristanSmile的专栏 - 博客频道 - CSDN.NET](http://blog.csdn.net/tristansmile/article/details/8313802)
* dp和px互转
	* [labs.rampinteractive.co.uk/android_dp_px_calculator/](http://labs.rampinteractive.co.uk/android_dp_px_calculator/)
* Android流氓代码
	* [Android流氓代码块(亲测可行）](http://blog.csdn.net/qq_22329521/article/details/52704661)       
	
### [知识点](#androidresource)	
* [iOS/Android 微信及浏览器中唤起本地APP](http://blog.csdn.net/linshijun33/article/details/71429669)

### [动画](#androidresource)
* lottie高级动画库	
	* [lottie](https://github.com/airbnb/lottie-android/blob/master/README.md)
* Activity跳转动画
	* [Material-Animations](https://github.com/lgvalle/Material-Animations)
* 一个带伸缩位移旋转动画的购物车按钮	
	* [AnimShopButton](https://github.com/mcxtzhang/AnimShopButton#)
* 图片波浪加载动画	
	* [WaveLoading](https://github.com/race604/WaveLoading)
* 带漂浮动画自定义控件	
	* [文字FloatingText](https://github.com/UFreedom/FloatingText)
	* [图片FloatingView](https://github.com/UFreedom/FloatingView)
* 实现1-7阶贝塞尔曲线的形成动画
	* [BezierMaker](https://github.com/venshine/BezierMaker)
* View动画库	
	* [AndroidViewAnimations](https://github.com/daimajia/AndroidViewAnimations)
* 搜索框动画库	
	* [JJSearchViewAnim](https://github.com/android-cjj/JJSearchViewAnim)	
* 简便易用的动画库
	* [ExpectAnim](https://github.com/florent37/ExpectAnim)
* Android Transition Framework详解---超炫的动画框架
	* [文章](http://www.jianshu.com/p/e497123652b5)
* 图片->SVG->PATH
	* [PathAnimView](https://github.com/mcxtzhang/PathAnimView)
* [running-the-animation](https://github.com/willowtreeapps/spruce-android#running-the-animation)

### [开发框架和开源项目](#androidresource)
* Android 快速开发库，主要想实现一条属于自己的开发框架。包括网络访问，数据，UI等等	
	* [AndroidRapidLibrary](https://github.com/lidong1665/AndroidRapidLibrary)
* 一个整合了大量主流开源项目的Android Mvp快速搭建框架
	* [MVPArms](https://github.com/JessYanCoding/MVPArms/wiki)
* 仿网易云音乐	
	* [remusic](https://github.com/aa112901/remusic)
* 来疯直播	
	* [SopCastComponent](https://github.com/LaiFeng-Android/SopCastComponent)
* Retrofit + Rxjava + okhttp开源项目	
	* [LookLook](https://github.com/xinghongfei/LookLook)
* 支付宝 Android 版使用的开源组件
	* [支付宝 Android 版使用的开源组件](http://www.jianshu.com/p/844e338319af#)
* 项目常用库
	* [项目中用到的那些方便流行的库](http://www.jianshu.com/p/6db1a5e84d67)
* [Android Studio、Eclipse多平台支持。MVP架构的Android开发框架，丰富的功能、简单的实现、详细的注释、规范的风格。OKHttp、UIL图片加载、ZXing二维码、沉浸状态栏、下载安装、自动缓存以及各种Base、Demo、UI、Util直接用。全新的手势，侧滑返回、全局](https://github.com/TommyLemon/Android-ZBLibrary#readme)
* [AppMethodOrder 一个能让你了解所有函数调用顺序以及函数耗时的Android库（无需侵入式代码）](https://github.com/zjw-swun/AppMethodOrder)
* [一个快速和易于使用的即插即用的动态主题引擎](https://github.com/afollestad/aesthetic)
* [这是一种不使用 ViewHolder 来编写适配器的方法](https://github.com/MEiDIK/SlimAdapter)
* [Chips 是 Material Design 中组件，他们被描述为：小却相对复杂的个体](https://github.com/pchmn/MaterialChipsInput)


### [第三方](#androidresource)
* [QQ](http://wiki.open.qq.com/wiki/创建并配置工程)
* [QQ互联](http://wiki.connect.qq.com/%e7%89%b9%e6%ae%8a%e9%97%ae%e9%a2%98-top10)
* [微信](https://open.weixin.qq.com/cgi-bin/showdocument?action=dir_list&t=resource/res_list&verify=1&id=1417751808&token=&lang=zh_CN)
* [支付宝](https://doc.open.alipay.com/docs/doc.htm?spm=a219a.7629140.0.0.d3bK7C&treeId=204&articleId=105296&docType=1)
* [银联](https://open.unionpay.com/ajweb/help/file/techFile?productId=3)
* [新浪微博](https://github.com/sinaweibosdk/weibo_android_sdk)
* 百度地图 
	* [SDK](http://lbsyun.baidu.com/index.php?title=androidsdk)
	* [Api文档](http://developer.baidu.com/map/reference/index.php?title=Class:android%E6%80%BB%E7%B1%BB/android%E6%A0%B8%E5%BF%83%E7%B1%BB)
* [JPush](http://docs.jiguang.cn/jpush/client/Android/android_guide/)
* 视频监控
	* [众云视频](http://www.zvcloud.com/sdkDevelop)
	* [海康威视频监控文档1](http://blog.csdn.net/lihong08/article/details/9355691)
	* [海康威视频监控文档1](http://blog.csdn.net/lihong08/article/details/9363741)
* [云脉科技名片扫描](http://www.yunmai.com/)
* [白分点大数据践行者](http://www.baifendian.com/)
* [shareSDK](https://github.com/MobClub/ThirdPartyLoginDemo)
* [友盟](http://dev.umeng.com/social/android/quick-integration)
* [诸葛IO,用户统计分析平台](http://help.zhugeio.com/hc/kb/article/113326/)
* [异常及热更新、热修复](https://bugly.qq.com/v2/index)

	
### [优质资源查找和学习site](#androidresource)	
* 自定义View	
	* [awesome-view](https://github.com/xinghongfei/awesome-view)
* Java的23种设计模式	
	* [JavaPattern](https://github.com/HaoTianYi/JavaPattern)
* 反射
	* [Java反射研究和实践](http://www.devio.org/2015/12/02/Java%E5%8F%8D%E5%B0%84%E7%A0%94%E7%A9%B6%E5%92%8C%E5%AE%9E%E8%B7%B5/)
* 非官方的 Google Actions Java SDK	
	* [Google-Actions-Java-SDK](https://github.com/frogermcs/Google-Actions-Java-SDK)
* Android开源项目分类整理	
	* [文章](http://www.jianshu.com/p/a9b46dcaec3a)
* 资源搜索	
	* [androidblog](http://androidblog.cn/index.php/Source/newSourceList/p/1)
* 他人整理的一些Android资源库	
	* [Android_Resources](https://github.com/wkxwkx101/Android_Resources)
* 学习资料收集	
	* [Android_Data](https://github.com/Freelander/Android_Data)
* github上优质资源	
	* [Awesome-Android](https://github.com/Mike-bel/Awesome-Android)
* 优质文章	
	* [xitu-gold](https://github.com/xitu/gold-miner/blob/master/TODO/11-top-designers-give-11-pieces-of-realistic-ux-advice.md)
* Android开源项目分类汇总	
	* [android-open-project](https://github.com/Trinea/android-open-project)
	* [android-common](https://github.com/Trinea/android-common)
	* [android-open-project](https://github.com/Trinea/android-open-project)
* Android开源项目源码解析	
	* [codekk](http://a.codekk.com/)
* Android 优秀文章	
	* [Android-注解详解](http://blog.csdn.net/wzgiceman/article/details/53483665)
	* [深入理解Android之Gradle](http://blog.csdn.net/innost/article/details/48228651)
	* [深入理解Android之AOP](http://blog.csdn.net/innost/article/details/49387395)
	* [阿里巴巴 JAVA 开发手册](https://img.hacpai.com/file/2017/1/eb0998bac7664496b2f1af98e07b08e5-Java.pdf)
* 一些图标网站	
	* [阿里巴巴图标库](http://www.iconfont.cn/plus/home/index?spm=a313x.7781069.1998910419.2.iVBhOV)
	* [easyicon](http://www.easyicon.net/566311-Minus_Circle_Green_icon.html)
	* [findicons](http://findicons.com/)
	* [前端工程师必备实用网站](http://www.jianshu.com/p/53a7da454057)
* Android学习资源网站索引大全
	* [Android-Learning-Resources](https://github.com/zhujun2730/Android-Learning-Resources)
* [极客学院](http://wiki.jikexueyuan.com/list/android/)
* [git教程](http://www.yiibai.com/git/home.html)
* [GoogleSamples/android-architecture](https://github.com/googlesamples/android-architecture)

### [大神、著名公司主页](#androidresource)	
* [张鸿洋](https://github.com/hongyangAndroid)
	* [博客](http://blog.csdn.net/lmj623565791?viewmode=contents)
* [贾鹏辉](http://www.devio.org/)
* [wingjay](https://github.com/wingjay)
* [Jake Wharton](https://github.com/JakeWharton)
* [Square](https://github.com/square)
* [Google](https://github.com/google)
* [Alibaba](https://github.com/alibaba)
* [Some Famous Android Developers Information](https://github.com/android-cn/android-dev-com)


	
