# 工程说明
1. 本工程为android入门学习工程
2. 教学B站视频：https://www.bilibili.com/video/BV19U4y1R7zV/?spm_id_from=333.788.videopod.episodes&vd_source=5eaafe8b8fc6af8f099a9aa9a9ff9995&p=37
# 新建工程
1. 由于新版的导航empty activity创建的工程默认语言为kotlin，不适合新手。 
2. 建议选择 empty views activity，然后选择语言java.

编译配置文件build.gradle
1. 项目级别的build.gradle 指定了当前项目的总体编译规则 
2. 模块级别的build.gradle,，对应于具体模块，每个模块都有自己的build.gradle，它指定了当前模块的详细编译规则。
清单文件
1. 每个模块都必须包含一个AndroidManifest.xml,并且文件名必须一模一样。
activity
1. 应用程序组件
界面显示与逻辑处理
1. 利用XML标记描绘应用界面，使用java代码来书写程序逻辑。
2. 好处：一个界面布局可以在被多处代码复用。
## android有四大组件
1. activity,屏幕组件
# 数据存储
1. 共享参数SharedPreferences 
   2. Android轻量级存储工具，存储结构key-value的键值对方式。
2. 数据库SQLite
3. 存储卡文件操作
4. 应用组件Application
# Fragment
1. 传统的activity并不能很好的处理大屏问题，需要一个碎片化的东西能够划区域的展示内容。且有属于自己的独立可操作空间。 
2. fragment注册 
   1. 静态注册 
   2. 动态注册
