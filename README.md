 一 安卓工具
Ddms
  ![github](http://github.com/cherry1116/mobiletest8/week2/src/common/images/ddms.png)

Hierarchyviewer
![github](http://github.com/cherry1116/mobiletest8/week2/src/common/images/hi.png)

Uiautomatorviewer
 ![github](http://github.com/cherry1116/mobiletest8/week2/src/common/images/ui.png)

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
 ![github](http://github.com/cherry1116/mobiletest8/week2/src/common/images/devices.png)
 ![github](http://github.com/cherry1116/mobiletest8/week2/src/common/images/adbin.png)
 ![github](http://github.com/cherry1116/mobiletest8/week2/src/common/images/packages.jpg)
 ![github](http://github.com/cherry1116/mobiletest8/week2/src/common/images/adbunin.png)
 ![github](http://github.com/cherry1116/mobiletest8/week2/src/common/images/adbp.png)
 ![github](http://github.com/cherry1116/mobiletest8/week2/src/common/images/adbshell.png)
 ![github](http://github.com/cherry1116/mobiletest8/week2/src/common/images/logcat.png)
 ![github](http://github.com/cherry1116/mobiletest8/week2/src/common/images/dir.png)
 ![github](http://github.com/cherry1116/mobiletest8/week2/src/common/images/rm.png)
 ![github](http://github.com/cherry1116/mobiletest8/week2/src/common/images/ls.png)
 ![github](http://github.com/cherry1116/mobiletest8/week2/src/common/images/dump.png)
 
 三 Monkey三种不同策略的的脚本 ，并阐述策略
 ![github](http://github.com/cherry1116/mobiletest8/week2/src/common/images/monkey1.png)

 四 安装 ideviceinstaller 下载一个任意open source的xcode project ,在simulator上面运行
     
