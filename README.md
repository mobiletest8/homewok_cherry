 一 安卓工具
Ddms
  ![](https://github.com/rawcherry1116/mobiletest8/week2/raw/master/src/common/images/ddms.png)

Hierarchyviewer
![image](https://github.com/mobiletest8/week2/tree/master/src/common/images/hi.png)

Uiautomatorviewer
 ![image](https://github.com/mobiletest8/week2/tree/master/src/common/images/ui.png)

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
 ![image](https://github.com/mobiletest8/week2/tree/master/src/common/images/devices.png)
 ![image](https://github.com/mobiletest8/week2/tree/master/src/common/images/adbin.png)
 ![image](https://github.com/mobiletest8/week2/tree/master/src/common/images/packages.jpg)
 ![image](https://github.com/mobiletest8/week2/tree/master/src/common/images/adbunin.png)
 ![image](https://github.com/mobiletest8/week2/tree/master/src/common/images/adbp.png)
 ![image](https://github.com/mobiletest8/week2/tree/master/src/common/images/adbshell.png)
 ![image](https://github.com/mobiletest8/week2/tree/master/src/common/images/logcat.png)
 ![image](https://github.com/mobiletest8/week2/tree/master/src/common/images/dir.png)
 ![image](https://github.com/mobiletest8/week2/tree/master/src/common/images/rm.png)
 ![image](https://github.com/mobiletest8/week2/tree/master/src/common/images/ls.png)
 ![image](https://github.com/mobiletest8/week2/tree/master/src/common/images/dump.png)
 
 三 Monkey三种不同策略的的脚本 ，并阐述策略
 ![image](https://github.com/mobiletest8/week2/tree/master/src/common/images/monkey1.png)

 四 安装 ideviceinstaller 下载一个任意open source的xcode project ,在simulator上面运行
     
