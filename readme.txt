下载并安装http://aardio.com/

// 你好我是xiao_zheng看到这条信息我应该已经跑路了
// 之后不会或很少再维护这个项目了，我会写一些注释
// 因为项目还在测试新的功能直接运行没法正常运行的
// Aardio编程工具有超多标准库和扩展库，可以再IDE右下角工具-扩展库下载安装
/*目前画的饼有：
OK 单机、联机，原版、MOD游戏启动
OK MOD管理系统
OK 自动启动Swarm，一键联机，获取ip（极其暴力的手法
OK 快捷短语设置
OK 连机器，按键工具的汉化，修复游戏标题乱码
OK 游戏里弹出来的窗口的汉化
OK 复制ip时追加的前缀和后缀短语
X  更改游戏窗口的大小（有问题，并且无法单独控制（那样直接写单启动器多任务好了
X  一键下载安装游戏本体+MOD整合包
X  在工具内实现静默修改 游戏按键（核心功能快实现了，就差手柄不知道怎么办
X  侧边栏的使用教程，没写完。
X  兼容AML的MOD包格式（标准好严苛）
XX 更改游戏内联机信息字体（对不起做不到）
*/
/*文件们分别是什么
\main.aardio				程序的入口点
\res\build.date				编译时自动填充的编译日期。
\res\index.html				侧边栏导航的网页文件。
\dlg\configs.aardio			设置窗口
\dlg\config_mods.aardio		MOD管理（子窗口）
\dlg\config_online.aardio	联机设置（子窗口）
\dlg\config_phrases.aardio	快捷短语设置（子窗口）
\dlg\main - 测试.aardio		旧程序主页面
\dlg\ui1.0.aardio			UI设计废案1
\dlg\ui2.0.aardio			UI设计废案2
\dlg\ui3.0.aardio			现在使用的UI设计
config 配置文件	\lib\config.aardio			用户配置
Game			\lib\seiki\game.aardio		游戏
GSConfig		\lib\seiki\gsconfig.aardio	键位设置工具汉化
gskey			\lib\seiki\gskey.aardio		GS键位文件键名测试
GSOnline		\lib\seiki\gsonline.aardio	连机器汉化
MGSConfig		\lib\seiki\mgsc.aardio		封装了键位设置文件读写的Manager
MGSOnline		\lib\seiki\mgso.aardio		封装了连机器配置文件读写的Manager
MSwarm			\lib\seiki\mswarm.aardio	封装了后台管理Swarm的Manager
replace			\lib\seiki\replace.aardio	测试-汉化窗口用的函数，供需复制
Swarm			\lib\seiki\swarm.aardio		前台管理Swarm
test			\lib\seiki\test.aardio		测试
test2			\lib\seiki\test2.aardio		测试
默认库(seiki)	\lib\seiki\_.aardio			程序的初始化
DIK 键码表		\lib\seiki\dik\DIK.aardio	DirectInput使用的键码表
test			\lib\seiki\dik\test.aardio	测试
默认库(seiki.dik)\lib\seiki\dik\_.aardio		DirectInput库
*/