 一 安卓工具
Ddms<br>
![](https://github.com/mobiletest8/week2/blob/master/src/common/images/ddms.png)

Hierarchyviewer<br>
![](https://github.com/mobiletest8/week2/blob/master/src/common/images/hi.png)

Uiautomatorviewer<br>
![](https://github.com/mobiletest8/week2/blob/master/src/common/images/ui.png)

MonkeyRunner


二 adb命令
adb devices //查看连接设备
adb install ***.apk //安装apk
adb shell pm list packages //列出所有包名
adb uninstall 包名 //卸载apk
adb logcat | grep ActivityManager 打印日志，筛选出含ActivityManager的信息
adb shell dumpsys meminfo 
adb push 
adb pull 
 ![](https://github.com/mobiletest8/week2/blob/master/src/common/images/devices.png)
 ![](https://github.com/mobiletest8/week2/blob/master/src/common/images/adbin.png)
 ![](https://github.com/mobiletest8/week2/blob/master/src/common/images/packages.jpg)
 ![](https://github.com/mobiletest8/week2/blob/master/src/common/images/adbunin.png)
 ![](https://github.com/mobiletest8/week2/blob/master/src/common/images/adbp.png)
 ![](https://github.com/mobiletest8/week2/blob/master/src/common/images/adbshell.png)
 ![](https://github.com/mobiletest8/week2/blob/master/src/common/images/logcat.png)
 ![](https://github.com/mobiletest8/week2/blob/master/src/common/images/dir.png)
 ![](https://github.com/mobiletest8/week2/blob/master/src/common/images/rm.png)
 ![](https://github.com/mobiletest8/week2/blob/master/src/common/images/ls.png)
 ![](https://github.com/mobiletest8/week2/blob/master/src/common/images/dump.png)
 
 三 Monkey三种不同策略的的脚本 ，并阐述策略
 ![](https://github.com/mobiletest8/week2/blob/master/src/common/images/monkey1.png)

 四 安装 ideviceinstaller 下载一个任意open source的xcode project ,在simulator上面运行
     
