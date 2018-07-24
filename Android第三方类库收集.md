# Android 开发第三方开源库收集
---

## 一 、网络请求
1. Android Async HTTP
        Android异步HTTP库
      https://github.com/loopj/android-async-http
2. AndroidAsync
        异步Socket，HTTP(客户端+服务器)，WebSocket，和socket.io库。基于NIO而不是线程
      https://github.com/koush/AndroidAsync
3. OkHttp
        一个Http与Http/2的客户端 
      https://github.com/square/okhttp
4. Retrofit
         类型安全的Http客户端，okhttp和retrofit做网络通讯是绝配
      https://github.com/square/retrofit
5. Volley
         Google推出的Android异步网络请求框架和图片加载框架
      https://android.googlesource.com/platform/frameworks/volley

## 二、JSON解析
1. Gson
        一个Java序列化/反序列化库，可以将JSON和java对象互相转换,Google出品
        https://github.com/google/gson
2. Jackson
        Jackson可以轻松地将Java对象转换成json对象和xml文档，同样也可以将 json、xml转换成Java对象
        https://github.com/codehaus/jackson
3. Fastjson
        Java上一个快速的JSON解析器/生成器,功能同gson，有些地方gson不能处理可以试试这个，阿里巴巴出品
        https://github.com/alibaba/fastjson

## 三、响应式编程
- RxJava
            JVM上的响应式扩展，一个实现异步操作的库，现在非常火
            https://github.com/ReactiveX/RxJava
- RxJavaJoins
            为RxJava提供Joins操作，
            https://github.com/ReactiveX/RxJavaJoins
- RxAndroid
            Android上的响应式扩展，用于Android的Rxjava绑定库，在RxJava基础上添加了Android线程调度
            https://github.com/ReactiveX/RxAndroid
- RxLifecycle
            防止RxJava中subscription导致内存泄漏
- RxPermissions
            基于RxJava开发的用于帮助在Android 6.0中处理运行时权限检测
- RxBinding
            提供用RxJava绑定Android UI的API，配合Rxjava处理控件异步调用
            https://github.com/JakeWharton/RxBinding
- Agera
            Android上的响应式编程
            https://github.com/google/agera

## 四、事件总线
- EventBus
            安卓优化的事件总线，简化了活动、片段、线程、服务等的通信
            https://github.com/greenrobot/EventBus
- Otto
            一个基于Guava的增强的事件总线
            https://github.com/square/otto

## 五、性能优化/内存检测
- LeakCanary
            内存泄漏检测工具，Facebook出品
             https://github.com/square/leakcanary
- ACRAAndroid
             应用程序崩溃报告
             https://github.com/ACRA/acra

## 六、网页数据抓取/Html解析
1. HtmlPaser
            一种用来解析单个独立html或嵌套html的方式
            https://sourceforge.net/projects/htmlparser
2. Jsoup
            一个以最好的DOM，CSS和jQuery解析html的库
            https://github.com/jhy/jsoup

## 七 、图片加载
1. Android Universal Image Loader
            一个强大的加载，缓存，展示图片的库
            https://github.com/nostra13/Android-Universal-Image-Loader
2. Picasso
            一个强大的图片下载与缓存的库https://github.com/square/picasso
3. Fresco

            一个用于管理图像和他们使用的内存的库，facebook出品
            https://github.com/facebook/fresco
4. Glide
            Google出品的图片加载和缓存的库，这里有非常好的指导文档：https:// mrfu.me/2016/02/27/Glide_Getting_Started/ https://github.com/bumptech/glide

## 八、图片处理
1. Picasso-transformations
        一个为Picasso提供多种图片变换的库
        https://github.com/wasabeef/picasso-transformations
    2、Glide-transformations
        一个为Glide提供多种图片变换的库
        https://github.com/wasabeef/glide-transformations
    3、Android-gpuimage
        基于OpenGL的Android过滤器
        https://github.com/CyberAgent/android-gpuimage

## 九、数据库
1. OrmLite
        JDBC和Android的轻量级ORM java包
        https://sourceforge.net/projects/ormlite/files/releases/com/j256/ormlite
    2、Sugar
        用超级简单的方法处理Android数据库
         https://github.com/satyan/sugar
    3、GreenDAO
        一种轻快地将对象映射到SQLite数据库的ORM解决方案,能配合rxjava使用
        https://github.com/greenrobot/greenDAO
    4、ActiveAndroid
        以活动记录方式为Android SQLite提供持久化
        https://github.com/pardom/ActiveAndroid
    5、SQLBrite
        SQLiteOpenHelper 和ContentResolver的轻量级包装
        https://github.com/square/sqlbrite
    6、Realm
        移动数据库：一个SQLite和ORM的替换品
        https://github.com/jhy/jsoup

## 十、依赖注入
1. ButterKnife
        将Android视图和回调方法绑定到字段和方法上，JakeWharton大神的力作
        https://github.com/JakeWharton/butterknife
    2、Dagger2
        一个Android和Java快速依赖注入库
        https://github.com/google/dagger
    3、AndroidAnotations
    快速安卓开发。易于维护
        https://github.com/androidannotations/androidannotations
    4、RoboGuice
        Android平台的Google Guice
        https://github.com/roboguice/roboguice

## 十一、图表
1. WilliamChart
        创建图表的Android库
        https://github.com/diogobernardino/WilliamChart
    2、HelloCharts
        兼容到API8的Android图表库
        https://github.com/lecho/hellocharts-android
    3、MPAndroidChart
        一个强大的Android图表视图/图形库
        https://github.com/PhilJay/MPAndroidChart

## 十二、热修复／插件化框架
- Tinker：微信Android热补丁方案，功能强大，和其它热修补方案对比看这里wiki 阿里百川HotFix：阿里百川推出的热修复HotFix服务，相对于QQ空间超级补丁技术和微信Tinker来说，定位于紧急bug修复的场景下，能够最及时的修复bug，下拉补丁立即生效无需等待。
- QQ空间超级补丁技术

## 十三、View
- BaseRecyclerViewAdapterHelper：很好用的RecyclerView多功能适配器库，项目里我并没有直接用这个库，而是按我自己使用习惯在它较早的代码上做了些改动
        recyclerview-animators：RecyclerView的动画库，内置了非常多的动画效果
        AndroidImageSlider：展示头部Banner的库，动画效果很多，不过需要依赖picasso和nineoldandroids这两个库
        CircleImageView：非常常用的用来显示圆形头像的库
        PhotoView：可根据手势进行缩放的图像库，这个也很常见
        NumberProgressBar：性感的数字进度条
        FlycoTabLayout：样式比TabLayout多样的Tab库
        FlycoDialog：多功能的Dialog
        FlycoLabelView：添加角标的库
        DanmakuFlameMaster：同样B站出品的弹幕库
        ShineButton：炫酷效果的点击按钮，主要用于显示收藏之类的动画
        RichText：富文本的处理库，用起来挺方便就是有内存泄漏- -
        Android-SpinKit：集成多种动画效果的Drawable，之前有看源码觉得代码封装得挺好，动画不仅仅只能用在View上
        filepicker：这个是用来处理PreferenceScreen的文件选中库，PreferenceScreen感觉平时不怎么看到使用，用法到时挺特别
        DragSlopLayout：一个辅助开发拖拽功能的库，这是我为了做这个App的某些功能封装的库- -，现在也有用在工作的项目上
        IjkPlayerView：基于ijkplayer开发的播放器，也是为了做这个App的视频播放功能封装的库- -，里面加了弹幕功能，感兴趣可以看下
        TagLayout：好吧不说了- -，主要是标签布局功能，还可以单独作为特殊点击效果的按钮，现在工作中需要点击效果的按钮我都直接用这个库来处理了，省的写Drawable

## 十四、视频框架
ijkplayer：B站出品的视频解码库

## 十五、测试框架
    1. Mockito
        Java编写的Mocking单元测试框架
        https://github.com/mockito/mockito
    2. Robotium
        Android UI 测试
        https://github.com/RobotiumTech/robotium
    3. Robolectric
        Android单元测试框架
        https://github.com/robolectric/robolectric
    另外Android还自带很多测试工具，如JUnit，Monkeyrunner，UiAutomator，Espresso等。

## 十六、缓存
    DiskLruCache
        Java实现基于LRU的磁盘缓存
        https://github.com/JakeWharton/DiskLruCache

## 十七、Log框架
    1. Logger
        简单，漂亮，强大的Android日志库，让打印的Log变得非常漂亮
        https://github.com/orhanobut/logger
    2. Hugo
        在调试版本上注解的触发方法进行日志记录
        https://github.com/JakeWharton/hugo
     3. Timber
        一个小的，可扩展的日志工具
        https://github.com/JakeWharton/timber

## 十八、调试框架
        Stetho
            调试Android应用的桥梁，使得可以利用Chrome开发者工具进行调试
            https://github.com/facebook/stetho

## 十九、后台处理
    1. Tape
        一个轻快的，事务性的，基于文件的FIFO的库
        https://github.com/square/tape
    2. Android Priority Job Queue
        一个专门为Android轻松调度任务的工作队列
        https://github.com/yigit/android-priority-jobqueue
