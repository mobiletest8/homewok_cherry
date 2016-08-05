 一 安卓工具
Ddms<br>
启动方法
这个工具存放在sdk-tools路径下，启动方法：
1）直接双击ddms.bat运行
2）在eclipse调试程序中启动ddms,在eclipse如下：
Window-Perspective-Open Perspective-Other-DDMS
<br>
![](https://github.com/mobiletest8/homewok_cherry/blob/master/week2/src/common/images/ddms.png)

Hierarchyviewer<br>
hierarchy viewer 是随android发布的工具，是android自带的非常有用而且使用简单的工具，可以帮助我们更好地检视和设计用户界面

1 从可视化的角度直观地获得ui布局设计结构和各种属性信息，帮助我们优化布局设计
2 结合debug帮助观察特定的ui对象进行invalidate 和requestLayout操作的过程
<br>
![](https://github.com/mobiletest8/homewok_cherry/blob/master/week2/src/common/images/hi.png)

Uiautomatorviewer<br>
uiautomatorviewer，一个用来来扫描和分析Android应用程序的UI组件的GUI工具
<br>
![](https://github.com/mobiletest8/homewok_cherry/blob/master/week2/src/common/images/ui.png)

MonkeyRunner
monkeyrunner是由google开发，用于android系统的自动化测试工具，由android系统自带，存在于android sdk中，monkeyrunner提供了一套api,用此api写出的程序可以在android代码之外控制android设备和模拟器。
启动方法：
android-sdk\tools\monkeyrunner.bat 
<br>

二 adb命令
adb(android debug bridge android)提供的一个通用调试工具，借助这个工具，我们可以更好地调试开发的程序。
<br>
adb devices //查看连接设备<br>
adb install ***.apk //安装apk<br>
adb shell pm list packages //列出所有包名<br>
adb uninstall 包名 //卸载apk<br>
adb logcat | grep ActivityManager 打印日志，筛选出含ActivityManager的信息<br>
adb shell dumpsys meminfo <br>
adb push <br>
adb pull <br>

 ![](https://github.com/mobiletest8/homewok_cherry/blob/master/week2/src/common/images/devices.png)
 <br>
 ![](https://github.com/mobiletest8/homewok_cherry/blob/master/week2/src/common/images/adbin.png)
 <br>
 ![](https://github.com/mobiletest8/homewok_cherry/blob/master/week2/src/common/images/packages.jpg)
 <br>
 ![](https://github.com/mobiletest8/homewok_cherry/blob/master/week2/src/common/images/adbunin.png)
 <br>
 ![](https://github.com/mobiletest8/homewok_cherry/blob/master/week2/src/common/images/adbp.png)
 <br>
 ![](https://github.com/mobiletest8/homewok_cherry/blob/master/week2/src/common/images/adbshell.png)
 <br>
 ![](https://github.com/mobiletest8/homewok_cherry/blob/master/week2/src/common/images/logcat.png)
 <br>
 ![](https://github.com/mobiletest8/homewok_cherry/blob/master/week2/src/common/images/dir.png)
 <br>
 ![](https://github.com/mobiletest8/homewok_cherry/blob/master/week2/src/common/images/rm.png)
 <br>
 ![](https://github.com/mobiletest8/homewok_cherry/blob/master/week2/src/common/images/ls.png)
 <br>
 ![](https://github.com/mobiletest8/homewok_cherry/blob/master/week2/src/common/images/dump.png)
 
 三 Monkey三种不同策略的的脚本 ，并阐述策略<br>
 ![](https://github.com/mobiletest8/homewok_cherry/blob/master/week2/src/common/images/monkey1.png)
<br>

 四 安装 ideviceinstaller 下载一个任意open source的xcode project ,在simulator上面运行
     
